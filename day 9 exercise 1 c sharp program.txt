using System;

class Program
{
    static String FirstAndLast(String str)
    {

       
        String[] arrOfStr = str.Split(' ');

         
        String res = "";

       
        foreach (String a in arrOfStr)
        {
            res += a.Substring(1, a.Length - 1) + " ";
        }

        return res;
    }

 
    public static void Main(String[] args)
    {
        String str = "Monkey is an animal";
        Console.WriteLine(str);
        Console.WriteLine(FirstAndLast(str));
    }
}

