# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance.


## Algorithm:

step 1: Create a base class.

Step 2: Create two child class.

step 3: Create a constructor in the base class and print a message.

step 4: create a function in child class to print a message.


## Program:

Name: G.TEJASWINI

Reg no:212222230157

```python
using System;
namespace inheri
{
    public class tyre
    {
        public virtual void display()
        {
            Console.Write("Tyre has been inserted:");
        }
    }
    class Scooter : tyre
    {
        public override void display()
        {
            base.display(); 
            Console.WriteLine("scooter ");
        }
    }
    class Car : tyre
    {
        public override void display()
        {
            base.display();
            Console.WriteLine("car ");
        }
    }
    class program
    {
        static void Main()
        {
            Scooter s = new Scooter();
            s.display();
            Car c = new Car();
            c.display();
        }
    }
}

```

## Output:
![image](https://github.com/TejaswiniGugananthan/Inheritance/assets/121222763/06c040c3-d369-4f47-b58d-b959903da0de)


## Result:
Thus C# program to print some messages using hierarchical inheritance is written and executed sucessfully.
