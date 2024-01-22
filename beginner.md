## Beginner C# and .NET Assessment

### 1.  Understanding Basic Syntax

    

```cs
    int a = 10;
    int b = 20;
    int sum = a + b;
```

    What is the value of `sum`?

    -   [ ]  10
    -   [ ]  20
    -   [x]  30
    -   [ ]  40
### 2.  Variable Types

    
```cs
    string name = "John Doe";
```
    What data type is `name`?

    -   [ ]  int
    -   [x]  string
    -   [ ]  bool
    -   [ ]  float
### 3.  For Loop Structure

    
```cs
    for (int i = 0; i < 5; i++) {
        Console.WriteLine(i);
    }
```
    How many times will the loop execute?

    -   [ ]  4
    -   [x]  5
    -   [ ]  6
    -   [ ]  Infinite
### 4.  If-Else Condition

```cs
    int number = 10;
    if (number > 5) {
        return true;
    } else {
        return false;
    }
```
    What does this code return?

    -   [x]  true
    -   [ ]  false
    -   [ ]  5
    -   [ ]  10
### 5.  Arrays
```cs
    int[] numbers = {1, 2, 3, 4, 5};
```

    How do you access the third element in the array `numbers`?

    -   [ ]  `numbers[2]`
    -   [ ]  `numbers[3]`
    -   [x]  `numbers[1]`
    -   [ ]  `numbers[4]`
### 6.  Basic String Manipulation

    
```cs
    string greeting = "Hello, World!";
    string sub = greeting.Substring(0, 5);
```

    What is the value of `sub`?

    -   [x]  "Hello"
    -   [ ]  "World"
    -   [ ]  "Hello, "
    -   [ ]  "ello"
### 7.  Understanding Methods

    
```cs
    public int Add(int a, int b) {
        return a + b;
    }
```

    What does this method do?

    -   [ ]  Subtracts two numbers
    -   [x]  Adds two numbers
    -   [ ]  Multiplies two numbers
    -   [ ]  Divides two numbers
### 8.  Exception Handling

    
```cs
    try {
        int x = int.Parse("NotAnInt");
    } catch (FormatException) {
        Console.WriteLine("Format error!");
    }
```

    What will be the output?

    -   [ ]  No output
    -   [x]  "Format error!"
    -   [ ]  "NotAnInt"
    -   [ ]  An unhandled exception
### 9.  Enums

    

```cs
enum Days {Sun, Mon, Tue, Wed, Thu, Fri, Sat};
```


    What is `Days.Tue`?

    -   [ ]  0
    -   [ ]  1
    -   [x]  2
    -   [ ]  3
### 10. LINQ Basics

    

```cs
List<int> numbers = new List<int> {1, 2, 3, 4, 5};
    var evenNumbers = numbers.Where(n => n % 2 == 0);
```

    What does `evenNumbers` contain?

    -   [ ]  {1, 3, 5}
    -   [x]  {2, 4}
    -   [ ]  {1, 2, 3, 4, 5}
    -   [ ]  Nothing
### 11. Basic Class Definition

    

```cs
public class Car {
        public string Color { get; set; }
    }
```

    How do you set the `Color` of a `Car` object to "Red"?

    -   [ ]  `Car.Color = "Red";`
    -   [x]  `Car myCar = new Car(); myCar.Color = "Red";`
    -   [ ]  `new Car("Red");`
    -   [ ]  `Car.SetColor("Red");`
### 12. Constructors

    
```cs
    public class Person {
        public Person() {
            Console.WriteLine("A new person is created.");
        }
    }
```

    What happens when `new Person()` is called?

    -   [ ]  Nothing is printed.
    -   [x]  "A new person is created." is printed.
    -   [ ]  An error occurs.
    -   [ ]  It creates a person without any output.
### 13. Static vs Instance Method

    
```cs
    public class MathOperations {
        public static int Multiply(int a, int b) {
            return a * b;
        }

        public int Subtract(int a, int b) {
            return a - b;
        }
    }
```

    How do you call the `Multiply` method?

    -   [x]  `MathOperations.Multiply(5, 3);`
    -   [ ]  `MathOperations myMath = new MathOperations(); myMath.Multiply(5, 3);`
    -   [ ]  `Multiply(5, 3);`
    -   [ ]  `new MathOperations().Multiply(5, 3);`
### 14. Inheritance

    
```cs
    public class Animal {
        public void Eat() {
            Console.WriteLine("Eating");
        }
    }

    public class Dog : Animal {
        public void Bark() {
            Console.WriteLine("Barking");
        }
    }
```

    Can an instance of `Dog` call the `Eat` method?

    -   [x]  Yes
    -   [ ]  No
### 15. Interfaces

    
```cs
    interface IVehicle {
        void Drive();
    }

    public class Car : IVehicle {
        public void Drive() {
            Console.WriteLine("Driving a car");
        }
    }
```

    Is this implementation correct?

    -   [x]  Yes
    -   [ ]  No
### 16. Delegates

    
```cs
    delegate void DisplayMessage(string message);
```


    What is `DisplayMessage` in this context?

    -   [ ]  A class
    -   [ ]  An interface
    -   [x]  A delegate
    -   [ ]  A method
### 17. Nullable Types

    
```cs
    int? a = null;`
```

    What is the meaning of `int?`?

    -   [ ]  Syntax error
    -   [x]  Nullable integer
    -   [ ]  Integer with default value 0
    -   [ ]  Integer array
### 18. Using Directives

    
```cs
    using System.Text;
```


    What is the purpose of this statement?

    -   [ ]  To include the `System.Text` namespace
    -   [ ]  To inherit from the `System.Text` class
    -   [x]  To use the classes and methods in the `System.Text` namespace without namespace qualification
    -   [ ]  To install the `System.Text` library
### 19. Value vs Reference Types

    
```cs
    int a = 10;
    int b = a;
    b = 20;`
```
    What is the value of `a` after this code executes?

    -   [x]  10
    -   [ ]  20
    -   [ ]  30
    -   [ ]  0
### 20. Basic Error Handling

    
```cs
     int Divide(int x, int y) {
        return x / y;
    }
```


    Which exception type might this method throw?

    -   [ ]  `InvalidOperationException`
    -   [x]  `DivideByZeroException`
    -   [ ]  `FormatException`
    -   [ ]  `NullReferenceException`


