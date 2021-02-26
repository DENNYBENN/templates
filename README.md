***Скриптовый язык EasyLogic -- это специализированный простой Си подобный язык со статической типизацией применяемый для расширения возможностей контроллеров Galileosky.***

**Основные возможности:**
- функции для работы с портами (RS232, RS485, CAN port) и входами / выходами.
- доступ к тегам (чтение / запись)
- доступ к переменным графического алгоритма (чтение / запись), из которого запущен скрипт
- доступ к глобальным переменным (только чтение)

Он поддерживает написание кода в функциональном и императивном стиле.

**Используемые типы данных:**
- bool
- int32 - знаковые целые числа с диапазоном от  -2 147 483 648  до  2 147 483 647
- одномерные и многомерные массивы int32[]
- строки символов в формате ASCII (которые хранятся как одномерные массивы символов)


**КОММЕНТАРИИ:**
Функциональное программирование предполагает обходиться вычислением результатов функций от исходных данных и результатов других функций, и не предполагает явного хранения состояния программы. 
Соответственно, не предполагает оно и изменяемость этого состояния (в отличие от императивного, где одной из базовых концепций является переменная, хранящая своё значение и позволяющая менять его по мере выполнения алгоритма).