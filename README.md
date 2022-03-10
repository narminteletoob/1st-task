//# 1st-task

using System;

namespace switchtask
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Read month name and display season name:\n");

            string str = Console.ReadLine();

            

            switch (str)
            {
                case "december":
                case "january":
                case "february":
                    Console.Write("Winter");
                    break;
                case "march":
                case "april":
                case "may":
                    Console.Write("Spring");
                    break;
                case "june":
                case "july":
                case "august":
                    Console.Write("Summer");
        break;
                case "september":
                case "october":
                case "november":
                    Console.Write("Autumn");
                    break;
                default:
                    Console.WriteLine("Nothing");
                    break;
            }

        }
    }
    }
