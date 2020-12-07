using System;

class Program
{
    static string month_ProblemString(int x, int y)
    {
        int days = x * y;
        string sentence = "The age of the person in days  is" + days + ".";
        return sentence;
    }

    static void Main()
    {
       Console.Write("Enter the age of the person:  ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Enter the number of days in a year: ");
        int b = int.Parse(Console.ReadLine());
        Console.WriteLine(month_ProblemString(a, b));
    }
}