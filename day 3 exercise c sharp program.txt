using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

public class Program
{
    static void Main(string[] args)
    {
        double rollno, sub1, sub2, sub3, total;
        double per;
        string name, div;

        Console.Write("Input the Roll Number of the student :");
        rollno = Convert.ToInt32(Console.ReadLine());

        Console.Write("Input the Name of the Student :");
        name = Console.ReadLine();

        Console.Write("Input  the marks of Subject 1 : ");
        sub1 = Convert.ToInt32(Console.ReadLine());
        Console.Write("Input  the marks of  Subject 2 : ");
        sub2 = Convert.ToInt32(Console.ReadLine());
        Console.Write("Input  the marks of Subject 3 : ");
        sub3 = Convert.ToInt32(Console.ReadLine());

        total = sub1 + sub2 + sub3;
        per = total / 3.0;
        if (per >= 60)
            div = "First";
        else
        if (per < 60 && per >= 48)
            div = "Second";
        else
            if (per < 48 && per >= 36)
            div = "Pass";
        else
            div = "Fail";

        Console.Write("\nRoll No : {0}\nName of Student : {1}\n", rollno, name);
        Console.Write("Marks in Subject 1 : {0}\nMarks in Subject 2 : {1}\nMarks in Subject 3 : {2}\n", sub1, sub2, sub3);
        Console.Write("Total Marks = {0}\nPercentage = {1}\nDivision = {2}\n", total, per, div);
    }
}
