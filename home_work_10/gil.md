Global Interpreter Lock (GIL) - механизм, контролирующий работу нитей.
Когда мы запускаем внутри своего процессора несколько нитей, у нас может исполняться только одна нить одновременно. 

Это особенность питона. Это нельзя обойти.

Библиотека multiprocessing позволяет организовать параллелизм вычислений за счет создания подпроцессов. 
Так как каждый процесс выполняется независимо от других, этот метод позволяет избежать проблем с GIL.


