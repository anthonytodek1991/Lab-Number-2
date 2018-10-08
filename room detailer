using System;

namespace Lab_1_Room_detailer
{
    class Program
    {
        static void Main(string[] args)
        {
            do
            {
                Console.WriteLine("Please enter Room length");
                String InputLength = Console.ReadLine();
                Console.WriteLine("Please enter Room Width");
                String InputWidth = Console.ReadLine();


                double Length = double.Parse(InputLength);
                double Width = double.Parse(InputWidth);

                double Area = Length * Width;
                Console.WriteLine("Area: {0}", Area);

                double Perimeter = (2 * Length) + (2 * Width);
                Console.WriteLine("Perimeter: {0}", Perimeter);

                Console.WriteLine("Continue? (y/n):");
            } while (Console.ReadLine()== "y");
            Console.WriteLine("Goodbye");
        }
    }
}
