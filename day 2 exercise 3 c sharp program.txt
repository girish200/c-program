using System;
namespace internship_c_sharp
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine(test(3, 2, 3));
            Console.WriteLine(test(2, 3, 2));
            Console.WriteLine(test(6, 1, 1));
            Console.WriteLine(test(7, 2, 2));
            Console.ReadLine();
        }

        public static int test(int x, int y, int z)
        {
            var max = Math.Max(x, Math.Max(y, z));
            Console.WriteLine("The maximum value is");
            return max;

        }
    }
}
    

