using System;

public class HelloWorld
{
    //The program allows the user to input booking information
    public static void Main(string[] args)
    {
    Console.WriteLine("HOTEL RESERVATION SYSTEM");
    Console.WriteLine("BOOKING PREFERENCE");
    Console.WriteLine("1. Solo Traveler");
    Console.WriteLine("2. Couple / Pair");

    //Choice Selection
    Console.Write("\nENTER SELECTION: ");
    string dachoice = Console.ReadLine();

    //Conditional Statement
    string dabook;
    switch (dachoice){
        case "1": 
            dabook = "Solo Traveler";
            break;
        case "2": 
            dabook = "Couple / Pair";
            break;
        default:
            Console.WriteLine("\nYou are blind");
            Console.ReadKey();
            return;
    }

    //Input
    Console.WriteLine("\nGUEST INFORMATION\n");

    Console.Write("Full Name: ");
    string daname = Console.ReadLine();
    Console.Write("Email Address: ");
    string daemail = Console.ReadLine();
    Console.Write("Phone Number: ");
    string daphone = Console.ReadLine();

    Console.WriteLine("\nBED PREFERENCE");
    Console.WriteLine("King Size");
    Console.WriteLine("Queen Size");
    Console.WriteLine("Single Beds");
    
    Console.WriteLine("--------------------------------");
    Console.Write("Enter selection: ");
    string dasize = Console.ReadLine();
    Console.Write("How many nights: ");
    string danights = Console.ReadLine();

    //Output
    Console.WriteLine("\nOUTPUT");
    Console.WriteLine("-----------------------------------------------------------");
    Console.WriteLine("HOTEL RESERVATION SYSTEM");
    Console.WriteLine("-----------------------------------------------------------");
    Console.WriteLine("GUEST INFORMATION\n");

    Console.WriteLine("Booking Preference: " + dabook);
    Console.WriteLine("Stays per night: " + danights);
    Console.WriteLine("Bed Preference: " + dasize);
    Console.WriteLine("Full Name: " + daname);
    Console.WriteLine("Email Address: " + daemail);
    Console.WriteLine("Phone Number: " + daphone);
    
    Console.ReadKey();
    }
}
