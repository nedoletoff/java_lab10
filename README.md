Написать класс стек на основе cвязного списка (классом LinkedList пользоваться нельзя) с методами
модифицирующими: void push(int), int pop()
читающими: equals, toString
Класс должен быть пригоден к использованию в многопоточных программах. Написать две реализации:
SynchroStack --- со стеком одновременно работать может только один поток
SynchroStackFast --- со стеком одновременно может работать либо один модифицирующий поток, либо несколько читающих потоков

В main с помощью замеров времени показать преимущество SynchroStackFast при работе в многопоточной программе.

