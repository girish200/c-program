using System;
namespace internship_c_sharp
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine(test(101));
            Console.WriteLine(test(80));
            Console.WriteLine(test(79));
            Console.ReadLine();
        }

        public static int test(int x, int y, int z)
        {
            if(Math.Abs(x - 100) <=10 || Math.Abs(x - 200) <= 10)
            return true;
            return false;

        }
    }
}
    

