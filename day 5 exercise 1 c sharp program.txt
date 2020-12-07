using System;

namespace arithmetic_operations
{
    class Program
    {
        public static bool IsResultTheSame(double a, double b)
        {
            return a == b;
        }

        public static void Main()
        {
            Console.WriteLine(IsResultTheSame(2 * 2, 8 / 2));           
            Console.WriteLine(IsResultTheSame(6 + 7, 12 - 8));           
            Console.WriteLine(IsResultTheSame(3 * 2 * 6, 256 / 2 / 3));  
        }
    }
}