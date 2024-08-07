# Homeworks for C++ course

[Complex number](https://github.com/0pqbd0/Cpp_Term_1/tree/main/ComplexNumber)
<details>
<summary>Условие</summary>
Создать класс "комплексное число" (пара чисел типа double). Класс должен поддерживать:
Конструктор по умолчанию (комплексный ноль)
Конструктор по вещественному числу (нулевая мнимая часть)
Конструктор по паре чисел - вещественной и мнимой части
Арифметические операции: сложение, вычитание, умножение и деление пар комплексных чисел и пары комплексное-вещественное/вещественное-комплексное
Операции арифметического присваивания
Унарный плюс и минус
Операцию сравнения на равенство (bool operator ==) и неравенство (bool operator !=) пар комплексных чисел, пар комплексное и вещественное число
Методы нахождения абсолютной величины (модуля) и комплексно-сопряженного значения.
Геттеры вещественной и мнимой части.
Потоковый ввод и вывод
Проследить за константной корректностью
</details>

[Template vector](https://github.com/0pqbd0/Cpp_Term_1/tree/main/TemplateVector)
<details>
<summary>Условие</summary>
Класс "вектор над полем T^N", где T - некоторый шаблонный тип (в первом приближении - double или int), N - шаблонная целочисленная константа. 
Класс должен поддерживать:
Конструктор по умолчанию, построение из Cи-массива
Операциии сложение, скалярное произведение, умножение на число, сравнение, арифметическое присваивание, унарный плюс и минус, ввод и вывод и др.
Методы евклидова норма и др.
STL не использовать.
</details>

[Stack and queue template impIementation with iterator](https://github.com/0pqbd0/Cpp_Term_1/tree/main/StackAndQueueTemplateImpIementationWithIterator)
<details>
<summary>Условие</summary>
Создать абстрактный базовый класс "односвязный список"  шаблонный, имеющий абстрактные методы
1) Push
2) Pop
3) GetFront
4) IsEmpty
5) Size
6) Print (защищенный)
7) Операцию присваивания из ссылки на "список"
и внутренний тип node (защищенный)
8) Реализовать перегрузку операции вывода (<< - через Print) и ввода (>> - через Push).
9) Реализовать конкретные классы Стек и Очередь, имеющие необходимые конструкторы пустого списка, копирования, перемещения, операции присваивания и присваивания по перемещению из ссылки на себя *и ссылки на другой список (копирование должно работать за O(n) и один проход списка, IsEmpty - за O(1)), реализацию необходимых абстрактных методов.
10) Реализовать итераторы обычный и константный для классов стек и очередь, а также виртуальные методы begin(), end(), cbegin(), cend(), работающие соответственно принципам STL.
Заменить вызов print() в operator << на использование итератора.
</details>
