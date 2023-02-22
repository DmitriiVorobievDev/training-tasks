# training-tasks
The classic problem about the Supplier and the Consumer

Given a LinkedList that is a store of integers.
The ProducerThread thread with some periodicity is infinite
adds random numbers to this list,
however, the maximum amount he can
add is 10.

The ConsumerThread thread endlessly reads numbers from some random
delay (from 0 to 10 ms).

Make the produce method add numbers only when
when the limit is not exceeded, and the consume method only took them
when something is on the list.
In this case, the methods should work correctly in a multithreaded
environment.

Create and run two different threads, one of which
calls produce and the other calls consume.
Demonstrate the correct operation of the repository using
output messages to the console about adding, getting and current
storage size during the add and get stages.


Классическая задача про Поставщика и Потребителя

Задан LinkedList, представляющий собой хранилище целых чисел.
Поток ProducerThread c какой-то периодичностью бесконечно
добавляет в этот список случайные числа,
однако максимальное количество, которое он может
добавить, равно 10.

Поток ConsumerThread бесконечно считывает числа с какой-то случайной
задержкой (от 0 до 10 мс).

Сделать так, чтобы метод produce добавлял числа только тогда,
когда не превышен лимит, а метод consume забирал их только
тогда, когда в списке что-нибудь есть.
При этом методы должны корректно работать в многопоточной
среде.

Создать и запустить два различных потока, один из которых
вызывает produce, а другой - consume.
Продемонстрировать корректность работы хранилища с помощью
вывода сообщений в консоль о добавлении, получении и текущем
размере хранилища на этапах добавления и получения.
