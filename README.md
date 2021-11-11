using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;


namespace Practice
{
	class Program
	{
		static void Main(string[] args)
		{ //Take user data
		  Console.WriteLine("Welcome to our app");	
          string name = Console.ReadLine();
          string status = Console.ReadLine();
          string address = Console.ReadLine();
          int age = Convert.ToInt32(Console.ReadLine());
          //This is these data output
          Console.WriteLine();
          Console.WriteLine("Name : " + name);
          Console.WriteLine("Your status is : " + status);
          Console.WriteLine("Address : " + address);
          Console.WriteLine("Age : " + age);
          if(age>=18)
          {
              Console.WriteLine("You are invited to party!");
          }
          else
          {
              Console.WriteLine("Ooopss");
          }
         
          
		}
	}
}

