# **Итоговая проверочная работа**

В ходе выполнения работы было сделано:

1. Создан репозиторий на GitHub

2. Нарисована блок-схема алгоритма

3. Оформлен файл Readme.md (c использованием синтаксиса Markdown)

4. Написана программа (С#), решающая поставленную задачу

5. Использован контроль версий 


## _Задача_:

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


## _Алгоритм решения_:

1. Объявляем два массива: исходный и второй (такой же длины, что и исходный)

2. Объявляем дополнительную переменную count, в которую заносится элемент из первого массива после проверки условия внутри цикла

3. Объявляем метод и с помощью цикла, пробегаем по длине массива №1

4. Если длина строк по условию совпадает с уловием (количество символов не превышает 3), эту строку вносим в count массива №2. Если нет, то count будет равен 0

5. После проверки выводим получившийся массив №2 в консоль
