using System;

namespace Number_of_words
{
    class Program
    {
        static int NumberOfWords(string str)
        {
            int numberOfWords = 0;
            for (int i = 1; i < str.Length; i++)
            {
                numberOfWords = (char.IsWhiteSpace(str[i]) ? numberOfWords + 1 : numberOfWords);
                
            }
           
            return numberOfWords + 1;
        }

        static void Main(string[] args)
        {
            Console.WriteLine(NumberOfWords("I am a monkey")); 
            Console.WriteLine(NumberOfWords("He owns a AMD Ryzen 9 5950X processor "));                                                
            Console.WriteLine(NumberOfWords("Windows is one of the worst operating system"));                                                      
        }
    }
}
