## Instructions 

Наименьшая единица измерения JaCoCo - это инструкции Java-байт-кода.
Счетчик Instruction предоставляет информацию о количестве кода, который был задействован тестами или пропущен.

## Branches 

JaCoCo также рассчитывает покрытие филиала для всех операторов if и switch. 
Эта метрика подсчитывает общее количество таких ветвей в методе и определяет количество выполненных или пропущенных ветвей.

## Lines

Для всех файлов классов, которые были скомпилированы с отладочной информацией, можно рассчитать информацию покрытия для отдельных строк. 
Строка источника считается выполненной, когда выполнена хотя бы одна инструкция, назначенная этой строке.

## Cyclomatic Complexity

JaCoCo также вычисляет цикломатическую сложность для каждого неабстрактного метода и суммирует сложность для классов, пакетов и групп. 
Цикломатическая сложность - это минимальное количество путей, которые в (линейной) комбинации могут генерировать все возможные пути 
через метод. Таким образом, значение сложности может служить индикатором количества случаев модульного тестирования, чтобы полностью 
охватить определенную часть программного обеспечения.
