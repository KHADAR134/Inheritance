# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance.
## Algorithm:
### step 1: 
Create a base class.

### step 2:
Create two child class.

### step 3:
Create a constructor in the base class and print a message.

### step 4:
create a function in child class to print a message.


## Program:
```c#
using System;
namespace kb
{
    public class vehicle
    {
        public vehicle()
        {
            Console.Write("tyre is attached");
        }

    }
    public class car : vehicle
    {
        public void display()
        {
            Console.Write(" to car");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.Write(" to scooter");
        }
    }
    public class program
    {
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            Console.WriteLine();
            scooter scooter = new scooter();
            scooter.display();
            Console.ReadKey();
        }
    }
}
```
## Output:
![c8](https://user-images.githubusercontent.com/75235006/173345998-e185e168-af05-498c-94dd-9d990de444fd.png)



## Result
C# program to print some messages using hierarchical inheritance is implemented successfully.
