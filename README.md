using System;

namespace ConsoleApp31
{
    class Program
    {
        static void Main(string[] args)
        {
            int amt = 10000, a, current = 50000, pin = 7535, pin1, pin2, acc;
            Console.WriteLine("Select your type of account:");
            Console.WriteLine("1.saving.");
            Console.WriteLine("2.current.");
            Console.WriteLine("3.Salary.");
            Console.WriteLine("Enter your choice:");
            acc = int.Parse(Console.ReadLine());
            switch (acc)
            {
                case 1:
                    Console.WriteLine("");
                    break;
                case 2:
                    Console.WriteLine("");
                    break;
                case 3:
                    Console.WriteLine("");
                    break;

            }
            Console.WriteLine("Enter your pin:");
            pin1 = int.Parse(Console.ReadLine());
            if (pin1 == pin)
            {
                Console.WriteLine("1.To Cheak balance:");
                Console.WriteLine("2.To Withdraw money:");
                Console.WriteLine("3.To Deposite money:");
                Console.WriteLine("4.To change your pin:");
                Console.WriteLine("Enter your Choice:");
                int ch = int.Parse(Console.ReadLine());
                switch (ch)
                {
                    case 1:
                        Console.WriteLine("your balance is =:" + current);
                        break;
                    case 2:
                        Console.WriteLine("Enter the ammount to Withdraw your money:");
                        a = int.Parse(Console.ReadLine());
                        if (amt >= a)
                        {
                            if (a % 100 == 0)
                            {
                                Console.WriteLine("Please Collact your cash:");
                                current = current - a;
                                Console.WriteLine("Your current balance is:" + current);
                            }
                            else
                            {
                                Console.WriteLine("Please Enter the ammount to withdraw in multiple of 100");
                            }
                        }
                        else
                        {
                            Console.WriteLine("Your account does not have sufficient balance:");
                        }
                        break;
                    case 3:
                        Console.WriteLine("Enter your ammount to Deposite your money:");
                        int b = int.Parse(Console.ReadLine());
                        current = current + b;
                        Console.WriteLine("The current balance is:" + current);
                        break;
                    case 4:
                        Console.WriteLine("Enter the previous pin:");
                        int prepin = int.Parse(Console.ReadLine());
                        if (prepin == pin)
                        {
                            Console.WriteLine("Enter your new pin:");
                            pin2 = int.Parse(Console.ReadLine());
                            pin1 = pin2;
                            Console.WriteLine("Your pin is changed.");
                        }
                        else
                        {
                            Console.WriteLine("Enter your correct pin");

                        }
                        break;
                }
            }
            else
            {
                Console.WriteLine("Pin is Wrong please input your correct pin.");
                int pin3 = int.Parse(Console.ReadLine());
                if (pin3 == pin)
                {

                    Console.WriteLine("1.To Cheak balance:");
                    Console.WriteLine("2.To Withdraw money:");
                    Console.WriteLine("3.To Deposite money:");
                    Console.WriteLine("4.To change your pin:");
                    Console.WriteLine("Enter your Choice:");
                    int ch = int.Parse(Console.ReadLine());
                    switch (ch)
                    {
                        case 1:
                            Console.WriteLine("your balance is =:" + current);
                            break;
                        case 2:
                            Console.WriteLine("Enter the ammount to Withdraw your money:");
                            a = int.Parse(Console.ReadLine());
                            if (amt >= a)
                            {
                                if (a % 100 == 0)
                                {
                                    Console.WriteLine("Please Collact your cash:");
                                    current = current - a;
                                    Console.WriteLine("Your current balance is:" + current);
                                }
                                else
                                {
                                    Console.WriteLine("Please Enter the ammount to withdraw in multiple of 100");
                                }
                            }
                            else
                            {
                                Console.WriteLine("Your account does not have sufficient balance:");
                            }
                            break;
                        case 3:
                            Console.WriteLine("Enter your ammount to Deposite your money:");
                            int b = int.Parse(Console.ReadLine());
                            current = current + b;
                            Console.WriteLine("The current balance is:" + current);
                            break;
                        case 4:
                            Console.WriteLine("Enter the previous pin:");
                            int prepin = int.Parse(Console.ReadLine());
                            if (prepin == pin)
                            {
                                Console.WriteLine("Enter your new pin:");
                                pin2 = int.Parse(Console.ReadLine());
                                pin1 = pin2;
                                Console.WriteLine("Your pin is changed.");
                            }
                            else
                            {
                                Console.WriteLine("Enter your correct pin");

                            }
                            break;
                    }
                }
                else
                {
                    Console.WriteLine("Pin is Wrong please input your correct pin.");
                    int pin4 = int.Parse(Console.ReadLine());
                    if (pin4 == pin)
                    {

                        Console.WriteLine("1.To Cheak balance:");
                        Console.WriteLine("2.To Withdraw money:");
                        Console.WriteLine("3.To Deposite money:");
                        Console.WriteLine("4.To change your pin:");
                        Console.WriteLine("Enter your Choice:");
                        int ch = int.Parse(Console.ReadLine());
                        switch (ch)
                        {
                            case 1:
                                Console.WriteLine("your balance is =:" + current);
                                break;
                            case 2:
                                Console.WriteLine("Enter the ammount to Withdraw your money:");
                                a = int.Parse(Console.ReadLine());
                                if (amt >= a)
                                {
                                    if (a % 100 == 0)
                                    {
                                        Console.WriteLine("Please Collact your cash:");
                                        current = current - a;
                                        Console.WriteLine("Your current balance is:" + current);
                                    }
                                    else
                                    {
                                        Console.WriteLine("Please Enter the ammount to withdraw in multiple of 100");
                                    }
                                }
                                else
                                {
                                    Console.WriteLine("Your account does not have sufficient balance:");
                                }
                                break;
                            case 3:
                                Console.WriteLine("Enter your ammount to Deposite your money:");
                                int b = int.Parse(Console.ReadLine());
                                current = current + b;
                                Console.WriteLine("The current balance is:" + current);
                                break;
                            case 4:
                                Console.WriteLine("Enter the previous pin:");
                                int prepin = int.Parse(Console.ReadLine());
                                if (prepin == pin)
                                {
                                    Console.WriteLine("Enter your new pin:");
                                    pin2 = int.Parse(Console.ReadLine());
                                    pin1 = pin2;
                                    Console.WriteLine("Your pin is changed.");
                                }
                                else
                                {
                                    Console.WriteLine("Enter your correct pin");

                                }
                                break;
                        }
                    }
                    else
                    {
                        Console.WriteLine("Pin is Wrong please input your correct pin.");
                        int pin5 = int.Parse(Console.ReadLine());
                        if (pin5 == pin)
                        {

                            Console.WriteLine("1.To Cheak balance:");
                            Console.WriteLine("2.To Withdraw money:");
                            Console.WriteLine("3.To Deposite money:");
                            Console.WriteLine("4.To change your pin:");
                            Console.WriteLine("Enter your Choice:");
                            int ch = int.Parse(Console.ReadLine());
                            switch (ch)
                            {
                                case 1:
                                    Console.WriteLine("your balance is =:" + current);
                                    break;
                                case 2:
                                    Console.WriteLine("Enter the ammount to Withdraw your money:");
                                    a = int.Parse(Console.ReadLine());
                                    if (amt >= a)
                                    {
                                        if (a % 100 == 0)
                                        {
                                            Console.WriteLine("Please Collact your cash:");
                                            current = current - a;
                                            Console.WriteLine("Your current balance is:" + current);
                                        }
                                        else
                                        {
                                            Console.WriteLine("Please Enter the ammount to withdraw in multiple of 100");
                                        }
                                    }
                                    else
                                    {
                                        Console.WriteLine("Your account does not have sufficient balance:");
                                    }
                                    break;
                                case 3:
                                    Console.WriteLine("Enter your ammount to Deposite your money:");
                                    int b = int.Parse(Console.ReadLine());
                                    current = current + b;
                                    Console.WriteLine("The current balance is:" + current);
                                    break;
                                case 4:
                                    Console.WriteLine("Enter the previous pin:");
                                    int prepin = int.Parse(Console.ReadLine());
                                    if (prepin == pin)
                                    {
                                        Console.WriteLine("Enter your new pin:");
                                        pin2 = int.Parse(Console.ReadLine());
                                        pin1 = pin2;
                                        Console.WriteLine("Your pin is changed.");
                                    }
                                    else
                                    {
                                        Console.WriteLine("Enter your correct pin");

                                    }
                                    break;
                            }
                        }
                    }
                }
            }
        }
    }
}
