/*
 Complete the square sum function so that it squares each number passed into it and then sums the results together. For example, for [1, 2, 2] it should return 9 because 1^2 + 2^2 + 2^2 = 9.
 */

using System;

namespace ConsoleApp2
{
    class Program
    {
        private static double SquareAndSum(int amount)
        {
            double result = 0;
            for (int i = 0; i < amount; i++)
            {
                Console.Write($"Number {i + 1} >> ");
                result += Math.Pow(Convert.ToInt32(Console.ReadLine()), 2);
            }
            return result;
        }
        
        static void Main(string[] args)
        {
            int amount;
            Console.Write("Enter amount of numbers to square and sum >> ");
            amount = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Result: " + SquareAndSum(amount));
        }
    }
}
