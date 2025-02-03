
            int charge = 0;
            Console.Write("Enter your car registration: ");
            string carReg = Console.ReadLine();
            
            while (carReg.Length > 8)
            {
                string displayMessage = carReg + " is not valid"; 
                Console.WriteLine(displayMessage);
                Console.Write("Enter a valid car registration: ");
                carReg = Console.ReadLine();
            }
            
            Console.Write("Enter your stay in hours: ");
            int hours = Convert.ToInt32(Console.ReadLine());
            
            if (hours < 2)
            {
                charge = 0;
            }
            else
            {
                charge = (hours * 2) + 2;
            }
            
            Console.WriteLine("Parking charge: £" + charge);
  


![image](https://github.com/user-attachments/assets/f93c474b-42e7-4358-bd31-59cd0ce482fc)
<img width="285" alt="Screenshot 2025-02-02 at 22 11 20" src="https://github.com/user-attachments/assets/72c1e764-ddff-47b5-91a0-8e2c7d3818a7" />

