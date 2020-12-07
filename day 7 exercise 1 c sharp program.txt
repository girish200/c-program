using System;

namespace CSharpExercises.Exercises.Library_functions
{
    class Program
    {
        public static string ReplaceXWithY(string word)
        {
            string[] words = word.Split(' ');

            for (int i = 0; i < words.Length; i++)
            {
                if (words[i].Contains("y"))
                {
                    words[i] = words[i].Replace("y", "x");
                }
            }

            return String.Join(" ", words);
        }

        public static void Main()
        {
            Console.WriteLine(ReplaceXWithY("yak"));                                   
            Console.WriteLine(ReplaceXWithY("xtay"));                   
            Console.WriteLine(ReplaceXWithY("He is in the gym"));        
            Console.WriteLine(ReplaceXWithY("xellaphone"));                                     
        }
    }
}