using System;

class Program
{
	static string month_ProblemString(int x)
	{
		int month_name = x;
		string sentence = "The month name is " + month_name + ".";
		return sentence;
	}

	static void Main()
	{
		int month;
		Console.Write("Enter the month number:  ");
		int a = int.Parse(Console.ReadLine());
		switch (a)
		{
			case 1:
				Console.Write("The month name is January\n");
				break;
			case 2:
				Console.Write("The month name is February\n");
				break;
			case 3:
				Console.Write("The month name is March\n");
				break;
			case 4:
				Console.Write("The month name is April\n");
				break;
			case 5:
				Console.Write("The month name is May\n");
				break;
			case 6:
				Console.Write("The month name is June\n");
				break;
			case 7:
				Console.Write("The month name is July\n");
				break;
			case 8:
				Console.Write("The month name is August\n");
				break;
			case 9:
				Console.Write("The month name is September\n");
				break;
			case 10:
				Console.Write("The month name is October\n");
				break;
			case 11:
				Console.Write("The month name is November\n");
				break;
			case 12:
				Console.Write("The month name is December\n");
				break;
			default:
				Console.Write("invalid Month number. \nPlease try again ....\n");
				break;
		}
	}
}