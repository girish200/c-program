using System;

class Program
{

   
    public static void Main(String[] args)
    {

        Console.WriteLine("Enter the first Name");
        String a = Console.ReadLine();
        Console.WriteLine("Enter the last Name");
        String b = Console.ReadLine();
       
      
        a = a + b;
        b = a.Substring(0, a.Length - b.Length);
        a = a.Substring(b.Length);

       
        Console.WriteLine("Strings after swap are:" +
                          " " + a + " and  " + b);
    }
}