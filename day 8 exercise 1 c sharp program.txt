using System;

namespace CSharpExercises.Exercises.Conditional_statements
{
    class Program
    {
        static bool IfGreaterThanThirdOne(int[] arr)
        {
            return arr[0] + arr[1] > arr[2] || arr[0] * arr[1] > arr[2];
        }

        static void Main(string[] args)
        {
            Console.WriteLine(IfGreaterThanThirdOne(new int[] { 2, 8, 22 }));     
            Console.WriteLine(IfGreaterThanThirdOne(new int[] { 10, 5, 25 }));     
            Console.WriteLine(IfGreaterThanThirdOne(new int[] { -15, -25, 221 })); 
            Console.WriteLine(IfGreaterThanThirdOne(new int[] { 11, 15, 16 }));   
        }
    }
}