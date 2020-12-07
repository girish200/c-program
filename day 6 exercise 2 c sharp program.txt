using System;

namespace check_palindrome
{
    class Program
    {
        static bool IsPalindrome(string str)
        {
            for (int i = 0; i < str.Length / 2; i++)
            {
                if (str[i] != str[str.Length - 1 - i])
                {
                    return false;
                }
            }

            return true;
        }

        static void Main(string[] args)
        {
            Console.WriteLine(IsPalindrome("x"));                         
            Console.WriteLine(IsPalindrome("test"));                   
            Console.WriteLine(IsPalindrome("alter"));                             
            Console.WriteLine(IsPalindrome("Ryzen"));       
            Console.WriteLine(IsPalindrome("lenovo"));   
            Console.WriteLine(IsPalindrome("x"));                                    
        }
    }
}