# Section Four: Non-Primitive Types

## Classes

* Classes combine related variables (fields) and functions (methods) together

* An object is an instance of the person class

## Declaring Classes

public class Person
{
  public string Name;

  public void Introduce()
  {
    Console.WriteLine("Hi, my name is " + Name);
  }
}

## Creating Objects (or instances of classes)

int number;

Person person = new Person();

var person = new Person();
person.Name = "Mosh";
person.Introduce();

## Static Modifier

public class Calculator
{
  public static int Add(int a, int b)
  {
    return a + b;
  }
}

int result = Calculator.Add( 1, 2 );
