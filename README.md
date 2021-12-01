Программа 1 
using System;

namespace практика_1
{
    class Program
    {
        static void Main(string[] args)
        {
            double a, b, c, d, abstand;
            Console.WriteLine("Введите a");
            a = double.Parse(Console.ReadLine());
            Console.WriteLine("Введите b");
            b = double.Parse(Console.ReadLine());
            Console.WriteLine("Введите c");
            c = double.Parse(Console.ReadLine());
            Console.WriteLine("Введите d");
            d = double.Parse(Console.ReadLine());
            abstand=Math.Sqrt(Math.Pow((c - a), 2) + Math.Pow((d - b), 2));
            Console.Write(" Расстояние между точками с координатами a = {0}, b = {1}, c = {2}, d = {3} равно: ", a, b, c, d);
            Console.Write("{0:0.00}", abstand);
        }
    }
}
Программа 2: 
using System;

namespace практика_1
{
    class Program
    {
        static void Main(string[] args)
        {
            int a;
            Console.Write("введите целое число: ");
             a = int.Parse(Console.ReadLine());
            if (a % 2 == 1)
            {
                Console.WriteLine("число нечетное");
            }
            else
            {
                Console.WriteLine("Число четное");
            }
            Console.ReadKey();
        }
    }
}
