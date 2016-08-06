using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication5
{
    class letras
    {            
            static void Main(string[] args)
            {
                char letra1, letra2, letra3;
                Console.WriteLine("Ingrese la letra m: ");
                letra1 = char.Parse(Console.ReadLine());
                Console.WriteLine("Ingrese la letra a: ");
                letra2 = char.Parse(Console.ReadLine());
                Console.WriteLine("Ingrese la letra r: ");
                letra3 = char.Parse(Console.ReadLine());

                Console.WriteLine("El resultados es: " + letra3 + letra2 + letra1);
                Console.ReadLine();
            }
        }
    }



