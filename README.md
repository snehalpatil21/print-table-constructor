# print-table-constructor
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace constructor89
{
    class Program
    {
        //c# program to illustrate calling
        //a default constructor
        int fno;
       // int sno,result;
        //this would be invoked while the object of class created.
        Program(int a)
        {
            fno = a;
            //sno = b;
            Console.WriteLine("table of given number is:");
            for (int i = 1; i <= 10; i++)
            {
                Console.WriteLine(i*a);
            }
        }
        //main method
        static void Main(string[] args)
        {
            int a;
             Console.WriteLine("enter number:");
            a = Convert.ToInt32(Console.ReadLine());
          //  Console.WriteLine("enter second number:");
          //  b = Convert.ToInt32(Console.ReadLine());
            
            //this would invoke default  //constructor.
            Program p = new Program(a);
            
 //default constructor provides //the default values to the //int and object.
             
            Console.ReadLine();
        }
    }
}
