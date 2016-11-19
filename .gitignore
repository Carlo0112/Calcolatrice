using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication12
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Title = "Calcolatrice";
            while (true)
            {
                Console.Write("Inserisci un operatore: ");
                string op = Console.ReadLine();
                Console.Write("Inserisci un primo numero: ");
                string num1 = Console.ReadLine();
                Console.Write("Inserisci un secondo numero: ");
                string num2 = Console.ReadLine();
                
                
                if (op == "*")
                {

                    double num3 = Convert.ToDouble(num2);
                    double num4 = Convert.ToDouble(num1);
                    double risultato = num4 * num3;
                    Console.WriteLine("Risultato: " + risultato);
                }
                else if (op == "+")
                {
                    double num3 = Convert.ToDouble(num2);
                    double num4 = Convert.ToDouble(num1);
                    double risultato = num4 + num3;
                    Console.WriteLine("Risultato: " + risultato);

                }
                else if (op == "-")
                {
                    double num3 = Convert.ToDouble(num2);
                    double num4 = Convert.ToDouble(num1);
                    double risultato = num4 - num3;
                    Console.WriteLine("Risultato: " + risultato);
                }
                else if (op == "/")
                {
                    double num3 = Convert.ToDouble(num2);
                    double num4 = Convert.ToDouble(num1);
                    double risultato = num4 / num3;
                    Console.WriteLine("Risultato: " + risultato);
                }
                else if (op == "^")
                { 
                        int num3 = Convert.ToInt32(num2);
                        int num4 = Convert.ToInt32(num1);
                        double risultato = Math.Pow(num3,num4);
                        Console.WriteLine("Risultato: " + risultato);
                 }
                else if (op.Equals("Rad", StringComparison.CurrentCultureIgnoreCase))
                {
                    int num3 = Convert.ToInt32(num1);
                    double risultato = Math.Sqrt(num3);
                    Console.WriteLine("Risultato: " + risultato);
                }
                else if (op.Equals("Rad3", StringComparison.CurrentCultureIgnoreCase))
                {
                    int num5 = Convert.ToInt32(num1);
                    double risultato = Math.Pow(num5, 1.0/3.0);
                    Console.WriteLine("Risultato: " + risultato);
                }

                Console.ReadLine();
            }
        }
    }
}
