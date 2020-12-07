using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
 
public class Exercise12
    {
        static void Main(string[] args)
        {
    double roll_no, sub1,sub2,sub3,total;
    double per;
    string name,div;

 


    Console.Write("Input the Roll Number of the student :");
    rl = Convert.ToInt32(Console.ReadLine());

    Console.Write("Input the Name of the Student :");
    nm = Console.ReadLine();

    Console.Write("Input  the marks of Subject 1 : ");
    phy= Convert.ToInt32(Console.ReadLine());
    Console.Write("Input  the marks of  Subject 2 : ");
    che = Convert.ToInt32(Console.ReadLine());
    Console.Write("Input  the marks of Subject 3 : ");
    ca = Convert.ToInt32(Console.ReadLine());

    total = sub1+sub2+sub3;
    per = total/3.0;
    if (per>=60)
	 div="First";
    else
	if (per<60&&per>=48)
	    div="Second";
	else
	    if (per<48&&per>=36)
		div="Pass";
	     else
		div="Fail";

       Console.Write("\nRoll No : {0}\nName of Student : {1}\n",roll_nol,name);
       Console.Write("Marks in Subject 1 : {0}\nMarks in Subject 2 : {1}\nMarks in sub3: {2}\n",sub1,sub2,sub3);
       Console.Write("Total Marks = {0}\nPercentage = {1}\nDivision = {2}\n",total,per,div);
}
}
