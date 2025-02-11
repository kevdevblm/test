# test
using System;

class program
{
    static void Main()
    {
        Console.Write("Enter a string :");
        
        string input = Console.ReadLine();

        string LowercaseString = input.ToLower();
        
        Console.WriteLine("Lowercase output:" + LowercaseString);

    }