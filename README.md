
class AI
{
    public static void Main(string[] args)
    {
        Console.ForegroundColor = ConsoleColor.DarkBlue;
        Console.WriteLine("       *****Welcome to Elevator***** ");
        Console.WriteLine();
        Console.Write("Choose the floor you want to go (1,2,3,4):"); ;
        int r = Convert.ToInt32(Console.ReadLine());
        if(r >4)
        {
            Console.WriteLine("Wrong Input");
        }
        switch (r)
        {
            case 1:
                Console.WriteLine("Welcome to 1st Floor");
            break;
            case 2:
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkRed;
                Console.WriteLine(" 1st Floor Arrived");
                Thread.Sleep(3000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("1st Floor Departed");
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkRed;
                Console.WriteLine("2nd Floor Arrived ");
                Console.WriteLine();
                Console.Write("Choose the floor you want to go (1,2,3,4):");
                int l = Convert.ToInt32(Console.ReadLine());
                if (l == 1)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("2nd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine(" 1st Floor Arrived");
                }
                if (l == 3)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("2nd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("3rd Floor Arrived");
                }
                if (l == 4)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("2nd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("3rd Floor Arrived");
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("3rd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("4th Floor Arrived");
                }
                break;
            case 3:
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("1st Floor Arrived");
                Thread.Sleep(3000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkRed;
                Console.WriteLine("1st Floor Departed");
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("2nd Floor Arrived");
                Thread.Sleep(3000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("2nd Floor Departed");
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkRed;
                Console.WriteLine("3rd Floor Arrived");
                Console.WriteLine();
                Console.Write("Choose the floor you want to go (1,2,3,4):");
                int u = Convert.ToInt32(Console.ReadLine());
                if (u == 1)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("3rd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("2nd Floor Arrived");
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("2nd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("1st Floor Arrived");
                }
                if (u == 2)
                {

                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("3rd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("2nd Floor Arrived");
                    Thread.Sleep(3000);

                }
                if (u == 4)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("3rd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("4th Floor Arrived");

                }
            break;
            case 4:
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("1st Floor Arrived");
                Thread.Sleep(3000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkRed;
                Console.WriteLine("1st Floor Departed");
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("2nd Floor Arrived");
                Thread.Sleep(3000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkRed;
                Console.WriteLine("2nd Floor Departed");
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("3rd Floor Arrived");
                Thread.Sleep(3000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkRed;
                Console.WriteLine("3rd Floor Departed");
                Thread.Sleep(5000);
                Console.Clear();
                Console.ForegroundColor = ConsoleColor.DarkBlue;
                Console.WriteLine("4th Floor Arrived");
                Console.WriteLine();
                Console.Write("Choose the floor you want to go (1,2,3,4):");
                int p = Convert.ToInt32(Console.ReadLine());
                if (p == 1)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("4th Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("3rd Floor Arrived");
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("3rd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("2nd Floor Arrived");
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("2nd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("1st Floor Arrived");
                }
                if (p == 3)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("4th Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("3rd Floor Arrived");
                }
                if (p == 2)
                {
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("4th Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("3rd Floor Arrived");
                    Thread.Sleep(3000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkRed;
                    Console.WriteLine("3rd Floor Departed");
                    Thread.Sleep(5000);
                    Console.Clear();
                    Console.ForegroundColor = ConsoleColor.DarkBlue;
                    Console.WriteLine("2nd Floor Arrived");
                }
            break;
     


             



        }
    }   


                



        
    
}

