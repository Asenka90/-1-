# Домашнее задание
//Задача 2: Напишите программу, которая на вход принимает два числа и выдаёт, какое число большее, а какое меньшее.
//a = 5; b = 7 -> max = 7
//a = 2 b = 10 -> max = 10
//a = -9 b = -3 -> max = -3


Console.WriteLine("***Задача 2:***");
Console.WriteLine("Введи 2 числа и программа выведет большее");
int a, b;
Console.Write("Введи первое число:");
a = int.Parse(Console.ReadLine());
Console.Write("Введи второе число:");
b = int.Parse(Console.ReadLine());
if (a > b)
{
    Console.WriteLine($"Число {a} больше чем {b}");
}
else if (a == b)
{
    Console.WriteLine($"Числа {a} и {b} равны");
}
else
{
    Console.WriteLine($"Число {b} больше чем {a}");
}


//Задача 4: Напишите программу, которая принимает на вход три числа и выдаёт максимальное из этих чисел.
// 2, 3, 7 -> 7
// 4 5 78 -> 78
// 22 3 9 -> 22


Console.WriteLine("***Задача 4:***");
Console.WriteLine("Введи 3 числа и программа выведет большее");
int x, y, z;
Console.Write("Введи первое число:");
x = int.Parse(Console.ReadLine());
Console.Write("Введи второе число:");
y = int.Parse(Console.ReadLine());
Console.Write("Введи третье число:");
z = int.Parse(Console.ReadLine());
int max = 0;
if (x > y)
{
    max = x;
}
if (y > x)
{
    max = y;
}
if (z > max)
{
    max = z;
}
Console.WriteLine($"Наибольшее число {max}");


// Задача 6: Напишите программу, которая на вход принимает число и выдаёт, является ли число чётным (делится ли оно на два без остатка).
// 4 -> да
// -3 -> нет
// 7 -> нет


Console.WriteLine("***Задача 6:***");
Console.WriteLine("Введи число и программа проверит четное ли оно:");
int number;
number = int.Parse(Console.ReadLine());
if (number % 2 == 0)
{
    Console.WriteLine($"Число {number} четное");
}
else
{
    Console.WriteLine($"Число {number} не четное");
}


//Задача 8: Напишите программу, которая на вход принимает число (N), а на выходе показывает все чётные числа от 1 до N.
// 5 -> 2, 4
// 8 -> 2, 4, 6, 8


Console.WriteLine("***Задача 8:***");
Console.WriteLine("Введи N и программа покажет все четные числа от 1 до N:");
int n;
n = int.Parse(Console.ReadLine());
for (int i = a; i < n; i++)
{
    Console.WriteLine(i);
}
