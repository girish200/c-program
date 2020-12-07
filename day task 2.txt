using System;  
public class Exercise24
{  
    public static void Main() 
      {          
                    string line = "Write a C# Sharp Program to display the following pattern using the alphabet.";
                    string[] words = line.Split(new[] { " " }, StringSplitOptions.None);
                        string word = "";
                        int ctr = 0;
                        foreach (String s in words)
                        {
                            if (s.Length > ctr)
                            {
                                word = s;
                                ctr = s.Length;
                            }
                        }
                   
                        Console.WriteLine(word);
                    
    }
}
