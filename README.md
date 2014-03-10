Тесты к курсу "Парадигмы программирования (Java)"
====

[Условия домашних заданий](http://www.kgeorgiy.info/courses/java-intro/homeworks.html)

Домашнее задание 2. Бинарный поиск
----
* [Тесты к сложной версии задания](BinarySearchHard.java)
* [Тесты к простой версии задания](BinarySearchEasy.java)


Домашнее задание 3. Очередь на массиве
----
*  Сложная версия
   * Должна быть реализована очередь с двумя концами (дэк, deque)
   * Название классов: ``ArrayDequeSingleton`` (модуль), ``ArrayDequeuADT`` (абстрактный тип данных), ``ArrayDeque`` (обычный класс)
   * Методы:
      * Работа с началом очереди: ``addFirst``, ``removeFirst``, ``peekFirst``
      * Работа с концом очереди: ``addLast``, ``removeLast``, ``peekLast``
      * Размеры: ``size``, ``isEmpty``
   * [Тесты](ArrayDequeTest.java)
* Простая версия
   * Должна быть реализована FIFO-очередь
   * Название классов: ``ArrayQuqueSingleton`` (модуль), ``ArrayQuqueADT`` (абстрактный тип данных), ``ArrayQuque`` (обычный класс)
   * Методы:
      * Добавление элемента: ``enqueue``
      * Удаление элемента: ``dequeue``
      * Просмотр элемента: ``peek``
      * Размеры: ``size``, ``isEmpty``
   * [Тесты](ArrayQueueTest.java)
