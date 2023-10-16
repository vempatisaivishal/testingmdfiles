1. T/F: In Java, a class can be instantiated directly without defining a constructor.

   - [ ] True
   - [x] False

   **Explanation:** False. In Java, a constructor is used to initialize objects. If a class doesn't define a constructor, a default constructor is provided, but you still need a constructor to create objects explicitly.

2. T/F: Class variables in Java are specific to an instance of the class.

   - [ ] True
         **Explanation:** False. Class variables, also known as static variables, are shared across all instances of a class. They are not specific to any single instance
   - [x] False

.

3. Which of the following is the correct way to define a class in Java?

   - [ ] `class MyClass() {}`
         **Explanation:** The correct syntax for defining a class in Java is simply `class ClassName {}`.
   - [x] `class MyClass {}`
   - [ ] `void class MyClass {}`
         **Explanation:** The correct syntax for defining a class in Java is simply `class ClassName {}`.
   - [ ] `new class MyClass {}`
         **Explanation:** The correct syntax for defining a class in Java is simply `class ClassName {}`.

4. What is the purpose of a constructor in Java?

   - [ ] To create class variables.

   **Explanation:** Constructors in Java are used to initialize the state of an object when it is created.

   - [x] To initialize object state.
   - [ ] To define static methods.

   **Explanation:** Constructors in Java are used to initialize the state of an object when it is created.

   - [ ] To declare instance variables.

   **Explanation:** Constructors in Java are used to initialize the state of an object when it is created.

5. When should you use a static (class) variable in Java?

   - [x] When you want a value shared among all instances of the class.
   - [ ] When you want a variable that changes its value for each object.

     **Explanation:** Static variables are used when you want a value shared among all instances of the class.

   - [ ] When you want to prevent object creation.
         **Explanation:** Static variables are used when you want a value shared among all instances of the class.
   - [ ] When you want to make a variable constant.
         **Explanation:** Static variables are used when you want a value shared among all instances of the class.

6. What is the output of the following Java code?

   ```java
   class MyClass {
       static int count = 0;

       MyClass() {
           count++;
       }
   }

   public class Main {
       public static void main(String[] args) {
           MyClass obj1 = new MyClass();
           MyClass obj2 = new MyClass();
           System.out.println(MyClass.count);
       }
   }
   ```

   - [ ] 0

   **Explanation:** Two objects of the `MyClass` are created, and the constructor increments the `count` each time an object is created. Thus, the output is 2.

   - [ ] 1

   **Explanation:** Two objects of the `MyClass` are created, and the constructor increments the `count` each time an object is created. Thus, the output is 2.

   - [ ] 2

   **Explanation:** Two objects of the `MyClass` are created, and the constructor increments the `count` each time an object is created. Thus, the output is 2.

   - [x] 2

7. What is missing in the following Java class definition to make it valid?

   ```java
   public class Student {
       String name;
       int age;

       // What is missing here?
   }
   ```

   - [ ] Constructors

   **Explanation:** Access modifiers (e.g., public, private) are missing. You should specify the visibility of the class members (fields, methods) using access modifiers.

   - [x] Access modifiers
   - [ ] Class variables

   **Explanation:** Access modifiers (e.g., public, private) are missing. You should specify the visibility of the class members (fields, methods) using access modifiers.

   - [ ] Main method

   **Explanation:** Access modifiers (e.g., public, private) are missing. You should specify the visibility of the class members (fields, methods) using access modifiers.

8. Which keyword is used to create an instance (object) of a class in Java?

   - [ ] create
         **Explanation:** The `new` keyword is used to create an instance of a class in Java.
   - [x] new
   - [ ] instance
         **Explanation:** The `new` keyword is used to create an instance of a class in Java.
   - [ ] class
         **Explanation:** The `new` keyword is used to create an instance of a class in Java.

9. What is the purpose of a constructor with parameters in Java?

   - [ ] To create a static variable.
         **Explanation:** A constructor with parameters allows you to initialize object properties with specific values during object creation.
   - [x] To initialize object properties with specific values during object creation.
   - [ ] To define class variables.
         **Explanation:** A constructor with parameters allows you to initialize object properties with specific values during object creation.
   - [ ] To access instance variables.
         **Explanation:** A constructor with parameters allows you to initialize object properties with specific values during object creation.

10. Consider the following Java code:

```java
class Example {
    static int count = 0;

    Example() {
        count++;
    }
}

public class Main {
    public static void main(String[] args) {
        Example obj1 = new Example();
        Example obj2 = new Example();
        Example obj3 = new Example();
        System.out.println(Example.count);
    }
}
```

What is the output of this code?

- [ ] 1
      **Explanation:** Three objects of the `Example` class are created, and the constructor increments the `count` each time an object is created. The output is 3.
- [ ] 3
      **Explanation:** Three objects of the `Example` class are created, and the constructor increments the `count` each time an object is created. The output is 3.
- [ ] 0
      **Explanation:** Three objects of the `Example` class are created, and the constructor increments the `count` each time an object is created. The output is 3.
- [x] 3

11. T/F: In Java, a constructor can have a return type.

- [ ] True

**Explanation:** False. Constructors do not have a return type, not even `void`. They are implicitly called when an object is created.

- [x] False

12. T/F: In Java, every class must have a constructor.

- [ ] True
      **Explanation:** False. If a class doesn't define any constructor, a default no-argument constructor is provided by the compiler.
- [x] False

13. What is the primary purpose of encapsulation in Java?

- [ ] To create objects.
      **Explanation:** Encapsulation in Java is used to hide the internal details of a class and provide controlled access to its members, which helps in data security and maintainability.
- [ ] To define constructors.
      **Explanation:** Encapsulation in Java is used to hide the internal details of a class and provide controlled access to its members, which helps in data security and maintainability.
- [ ] To declare class variables.
      **Explanation:** Encapsulation in Java is used to hide the internal details of a class and provide controlled access to its members, which helps in data security and maintainability.
- [x] To hide the internal details of a class and provide controlled access to its members.

14. When is the `this` keyword used in Java?

- [ ] To create objects.
      **Explanation:** The `this` keyword is used to refer to the current instance of a class within instance methods.
- [ ] To define constructors.
      **Explanation:** The `this` keyword is used to refer to the current instance of a class within instance methods.
- [ ] To declare class variables.
      **Explanation:** The `this` keyword is used to refer to the current instance of a class within instance methods.
- [x] To refer to the current instance of a class within instance methods.

15. What is a default constructor in Java?

- [ ] A constructor with a single parameter.

  **Explanation:** A default constructor in Java is a constructor with no arguments that is provided by the compiler if no constructors are explicitly defined in the class.

- [ ] A constructor that is automatically generated for a class.
      **Explanation:** A default constructor in Java is a constructor with no arguments that is provided by the compiler if no constructors are explicitly defined in the class.
- [x] A constructor with no arguments that is provided by the compiler if no constructors are defined.
- [ ] A constructor for creating default objects.
      **Explanation:** A default constructor in Java is a constructor with no arguments that is provided by the compiler if no constructors are explicitly defined in the class.

16. What is the output of the following Java code?

```java
class Car {
    String model;

    Car(String model) {
        this.model = model;
    }
}

public class Main {
    public static void main(String[] args) {
        Car car1 = new Car("Sedan");
        Car car2 = new Car("SUV");
        System.out.println(car1.model + " and " + car2.model);
    }
}
```

- [ ] "Sedan and Sedan"

**Explanation:** The `model` attribute of each car object is set by the constructor, so car1 is "Sedan" and car2 is "SUV."

- [ ] "SUV and Sedan"

**Explanation:** The `model` attribute of each car object is set by the constructor, so car1 is "Sedan" and car2 is "SUV."

- [ ] "Sedan and SUV"

**Explanation:** The `model` attribute of each car object is set by the constructor, so car1 is "Sedan" and car2 is "SUV."

- [x] "Sedan and SUV"

17. Which keyword is used to access class variables in Java?

- [ ] this
      **Explanation:** Class variables are accessed using the class name, not with `this`.
- [x] ClassName
- [ ] super
      **Explanation:** Class variables are accessed using the class name, not with `this`.
- [ ] new
      **Explanation:** Class variables are accessed using the class name, not with `this`.

18. In Java, which of the following statements about instance variables is correct?

- [ ] They are shared among all instances of a class.
      **Explanation:** Instance variables are specific to each instance (object) of a class.

- [x] They are specific to each instance of a class.
- [ ] They are declared as `static`.
      **Explanation:** Instance variables are specific to each instance (object) of a class.

- [ ] They are created with the `new` keyword.
      **Explanation:** Instance variables are specific to each instance (object) of a class.

19. What is the purpose of the `static` keyword in Java?

- [ ] To make a variable specific to an instance.

**Explanation:** The `static` keyword is used to create class-level variables and methods, which are shared among all instances of a class.

- [ ] To create a constructor.

**Explanation:** The `static` keyword is used to create class-level variables and methods, which are shared among all instances of a class.

- [x] To create class-level variables and methods.
- [ ] To make a method specific to an instance.

**Explanation:** The `static` keyword is used to create class-level variables and methods, which are shared among all instances of a class.

20. Consider the following Java code:

```java
class Employee {
    String name;
    static int employeeCount = 0;

    Employee(String name) {
        this.name = name;
        employeeCount++;
    }
}

public class Main {
    public static void main(String[] args) {
        Employee emp1 = new Employee("Alice");
        Employee emp2 = new Employee("Bob");
        System.out.println(Employee.employeeCount);
    }
}
```

What is the output of this code?

- [ ] 1
      **Explanation:** Two `Employee` objects are created, and the `employeeCount` is incremented each time an object is created. The output is 2.

- [ ] 2
      **Explanation:** Two `Employee` objects are created, and the `employeeCount` is incremented each time an object is created. The output is 2.

- [ ] 0
      **Explanation:** Two `Employee` objects are created, and the `employeeCount` is incremented each time an object is created. The output is 2.

- [x] 2

21. T/F: In Java, a class can extend more than one class (multiple inheritance).

- [ ] True
      **Explanation:** False. Java does not support multiple inheritance for classes; a class can extend only one other class.
- [x] False

22. T/F: A subclass inherits all the members (fields and methods) of its superclass.

- [x] True
- [ ] False
      **Explanation:** True. A subclass inherits all the members of its superclass, both fields and methods, unless they are marked as private or overridden.

13. What is the purpose of the `super` keyword in Java?

- [ ] To create an instance of a superclass.
      **Explanation:** The `super` keyword is used to refer to the superclass or call its constructors and methods from a subclass.
- [ ] To access class variables.
      **Explanation:** The `super` keyword is used to refer to the superclass or call its constructors and methods from a subclass.
- [ ] To define constructors.
      **Explanation:** The `super` keyword is used to refer to the superclass or call its constructors and methods from a subclass.
- [x] To refer to the superclass or call its constructors and methods from a subclass.

24. What is method overriding in Java?

- [ ] Creating a new method in a subclass with a different name.
      **Explanation:** Method overriding in Java means providing a specific implementation for a method in a subclass that is already defined in its superclass.
- [x] Providing a specific implementation for a method in a subclass that is already defined in its superclass.
- [ ] Defining a new constructor in a subclass.
      **Explanation:** Method overriding in Java means providing a specific implementation for a method in a subclass that is already defined in its superclass.
- [ ] Declaring a method as private in a subclass.
      **Explanation:** Method overriding in Java means providing a specific implementation for a method in a subclass that is already defined in its superclass.

25. What is the difference between an instance variable and a class variable in Java?

- [ ] Instance variables are shared among all instances of a class, while class variables are specific to each instance.

**Explanation:** Instance variables are specific to each instance (object) of a class, while class variables (static variables) are shared among all instances.

- [x] Instance variables are specific to each instance of a class, while class variables are shared among all instances.
- [ ] Instance variables are declared with the `static` keyword, while class variables are not.

**Explanation:** Instance variables are specific to each instance (object) of a class, while class variables (static variables) are shared among all instances.

- [ ] There is no difference; they are interchangeable.

**Explanation:** Instance variables are specific to each instance (object) of a class, while class variables (static variables) are shared among all instances.

26. Given the following code snippet, what is the expected output?

```java
class Animal {
    void makeSound() {
        System.out.println("Animal makes a sound");
    }
}

class Cat extends Animal {
    void makeSound() {
        System.out.println("Cat meows");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal myPet = new Cat();
        myPet.makeSound();
    }
}
```

- [ ] "Animal makes a sound"
      **Explanation:** The output will be "Cat meows" because the method in the subclass `Cat` overrides the method in the superclass `Animal`.

- [ ] "Cat meows"
      **Explanation:** The output will be "Cat meows" because the method in the subclass `Cat` overrides the method in the superclass `Animal`.

- [ ] Compilation error
      **Explanation:** The output will be "Cat meows" because the method in the subclass `Cat` overrides the method in the superclass `Animal`.

- [x] "Cat meows"

27. Which keyword is used to explicitly call the constructor of a superclass from a subclass constructor?

- [ ] superclass
      **Explanation:** The `super` keyword is used to explicitly call the constructor of a superclass from a subclass constructor.
- [ ] parent
      **Explanation:** The `super` keyword is used to explicitly call the constructor of a superclass from a subclass constructor.
- [ ] base
      **Explanation:** The `super` keyword is used to explicitly call the constructor of a superclass from a subclass constructor.
- [x] super

28. What is the access modifier for a class member that is only accessible within its own class?

- [x] private
- [ ] public

**Explanation:** The `private` access modifier restricts access to the member to within its own class.

- [ ] protected

**Explanation:** The `private` access modifier restricts access to the member to within its own class.

- [ ] default (package-private)

**Explanation:** The `private` access modifier restricts access to the member to within its own class.

29. In Java, which of the following is a correct way to declare a constant (variable with a fixed value) in a class?

- [ ] `constant int VALUE = 10;`

**Explanation:** To declare a constant in Java, you should use the `final` and `static` modifiers, typically written as `final static`.

- [ ] `const VALUE = 10;`

**Explanation:** To declare a constant in Java, you should use the `final` and `static` modifiers, typically written as `final static`.

- [ ] `static final int VALUE = 10;`

**Explanation:** To declare a constant in Java, you should use the `final` and `static` modifiers, typically written as `final static`.

- [x] `final static int VALUE = 10;`

30. Consider the following Java code:

```java
class Vehicle {
    static int count = 0;

    Vehicle() {
        count++;
    }
}

class Car extends Vehicle {
    Car() {
        count--;
    }
}

public class Main {
    public static void main(String[] args) {
        Vehicle vehicle = new Car();
        System.out.println(Vehicle.count);
    }
}
```

What is the output of this code?

- [ ] 1
      **Explanation:** One `Car` object is created and assigned to a `Vehicle` reference. The `Car` constructor decrements `count`, which cancels out the increment in the `Vehicle` constructor. The output is 0.
- [x] 0
- [ ] -1
      **Explanation:** One `Car` object is created and assigned to a `Vehicle` reference. The `Car` constructor decrements `count`, which cancels out the increment in the `Vehicle` constructor. The output is 0.
- [ ] 2
      **Explanation:** One `Car` object is created and assigned to a `Vehicle` reference. The `Car` constructor decrements `count`, which cancels out the increment in the `Vehicle` constructor. The output is 0.

31. T/F: Java supports multiple constructors with the same parameter list in a class.

- [ ] True
      **Explanation:** False. Java does not allow multiple constructors with the same parameter list in a class.
- [x] False

32. T/F: You can create an object of an abstract class in Java.

- [ ] True
      **Explanation:** False. You cannot create an object of an abstract class in Java. Abstract classes are meant to be extended by concrete subclasses.
- [x] False

33. What is method overloading in Java?

- [ ] Providing a specific implementation for a method in a subclass.
      **Explanation:** Method overloading in Java is about defining multiple methods in the same class with the same name but different parameter lists.
- [x] Defining multiple methods in the same class with the same name but different parameter lists.
- [ ] Creating a new method in a subclass with a different name.
      **Explanation:** Method overloading in Java is about defining multiple methods in the same class with the same name but different parameter lists.
- [ ] Declaring a method as private in a subclass.
      **Explanation:** Method overloading in Java is about defining multiple methods in the same class with the same name but different parameter lists.

34. What is the purpose of the `final` keyword in Java?

- [ ] To make a variable specific to an instance.
      **Explanation:** The `final` keyword in Java is used to prevent a class from being extended, prevent method overriding, or declare constants.
- [ ] To create an abstract class.
      **Explanation:** The `final` keyword in Java is used to prevent a class from being extended, prevent method overriding, or declare constants.
- [x] To prevent a class from being extended, prevent method overriding, or declare constants.
- [ ] To create a constructor.
      **Explanation:** The `final` keyword in Java is used to prevent a class from being extended, prevent method overriding, or declare constants.

35. In Java, what is the `this` keyword used for in a constructor?

- [ ] To refer to the superclass.

**Explanation:** In a constructor, `this` is used to distinguish between instance variables and parameters with the same name.

- [ ] To create a new instance of the class.

**Explanation:** In a constructor, `this` is used to distinguish between instance variables and parameters with the same name.

- [ ] To call another constructor from the same class.

**Explanation:** In a constructor, `this` is used to distinguish between instance variables and parameters with the same name.

- [x] To distinguish between instance variables and parameters with the same name.

36. Given the following Java code, what is the output?

```java
class Parent {
    void display() {
        System.out.println("Parent class");
    }
}

class Child extends Parent {
    void display() {
        System.out.println("Child class");
    }
}

public class Main {
    public static void main(String[] args) {
        Parent obj = new Child();
        obj.display();
    }
}
```

- [ ] "Parent class"
      **Explanation:** The output will be "Child class" because the method in the subclass `Child` overrides the method in the superclass `Parent`, and the object is of type `Child`.
- [ ] "Child class"
      **Explanation:** The output will be "Child class" because the method in the subclass `Child` overrides the method in the superclass `Parent`, and the object is of type `Child`.
- [ ] Compilation error
      **Explanation:** The output will be "Child class" because the method in the subclass `Child` overrides the method in the superclass `Parent`, and the object is of type `Child`.
- [x] "Child class"

37. Which keyword is used to create an object of an inner class in Java?

- [ ] inner
      **Explanation:** The `new` keyword is used to create an object of a class, including inner classes.
- [ ] this
      **Explanation:** The `new` keyword is used to create an object of a class, including inner classes.
- [ ] super
      **Explanation:** The `new` keyword is used to create an object of a class, including inner classes.
- [x] new

38. What is an abstract class in Java?

- [ ] A class that cannot have any methods.
      **Explanation:** An abstract class in Java cannot be instantiated and is meant to be subclassed by concrete (non-abstract) classes.

- [x] A class that cannot be instantiated and is meant to be subclassed.
- [ ] A class with all methods marked as `static`.
      **Explanation:** An abstract class in Java cannot be instantiated and is meant to be subclassed by concrete (non-abstract) classes.

- [ ] A class with no fields or methods.
      **Explanation:** An abstract class in Java cannot be instantiated and is meant to be subclassed by concrete (non-abstract) classes.

39. In Java, how can you prevent a class from being subclassed (extended)?

- [ ] Use the `final` keyword on all methods.
      **Explanation:** To prevent a class from being subclassed, you can use the `final` keyword on the class itself.
- [ ] Mark all methods as `private`.
      **Explanation:** To prevent a class from being subclassed, you can use the `final` keyword on the class itself.
- [x] Use the `final` keyword on the class itself.
- [ ] Declare all methods as `static`.
      **Explanation:** To prevent a class from being subclassed, you can use the `final` keyword on the class itself.

40. Consider the following Java code:

```java
class Base {
    static void display() {
        System.out.println("Base class");
    }
}

class Derived extends Base {
    static void display() {
        System.out.println("Derived class");
    }
}

public class Main {
    public static void main(String[] args) {
        Base obj = new Derived();
        obj.display();
    }
}
```

What is the output of this code?

- [ ] "Base class"

**Explanation:** The output will be "Base class" because static methods do not participate in method overriding, and the reference type determines which class's method is called.

- [ ] "Derived class"

**Explanation:** The output will be "Base class" because static methods do not participate in method overriding, and the reference type determines which class's method is called.

- [ ] Compilation error

**Explanation:** The output will be "Base class" because static methods do not participate in method overriding, and the reference type determines which class's method is called.

- [x] "Base class"

41. T/F: An abstract class can have both abstract and non-abstract (concrete) methods.

- [x] True
- [ ] False

**Explanation:** True. An abstract class can have both abstract and concrete methods. Concrete methods have implementations, while abstract methods do not.

42. T/F: Java allows you to instantiate an interface.

- [ ] True
      **Explanation:** False. You cannot create an instance of an interface in Java. Interfaces define a contract that implementing classes must adhere to.
- [x] False

43. What is the purpose of the `extends` keyword in Java class definitions?

- [x] To indicate that one class is a subclass of another class, establishing an inheritance relationship.
- [ ] To import another class.
      **Explanation:** The `extends` keyword is used to establish an inheritance relationship between classes in Java.
- [ ] To implement an interface.
      **Explanation:** The `extends` keyword is used to establish an inheritance relationship between classes in Java.
- [ ] To define a constructor.
      **Explanation:** The `extends` keyword is used to establish an inheritance relationship between classes in Java.

44. What is the primary use of the `new` keyword in Java?

- [ ] To create class variables.
      **Explanation:** The `new` keyword is used to create objects (instances) of classes in Java.
- [ ] To define constructors.
      **Explanation:** The `new` keyword is used to create objects (instances) of classes in Java.
- [x] To create objects (instances) of classes.
- [ ] To access instance variables.
      **Explanation:** The `new` keyword is used to create objects (instances) of classes in Java.

45. What is the purpose of an interface in Java?

- [ ] To provide a blueprint for creating objects.

**Explanation:** An interface in Java specifies a contract for classes that implement it, defining the methods that those classes must provide.

- [ ] To define constructors.

**Explanation:** An interface in Java specifies a contract for classes that implement it, defining the methods that those classes must provide.

- [x] To specify a contract for classes that implement the interface.
- [ ] To declare class variables.

**Explanation:** An interface in Java specifies a contract for classes that implement it, defining the methods that those classes must provide.

46. Given the following Java code, what is the output?

```java
interface Shape {
    void draw();
}

class Circle implements Shape {
    public void draw() {
        System.out.println("Drawing a circle.");
    }
}

public class Main {
    public static void main(String[] args) {
        Shape shape = new Circle();
        shape.draw();
    }
}
```

- [ ] "Drawing a circle."

**Explanation:** The output will be "Drawing a circle." The `draw` method of the `Circle` class, which implements the `Shape` interface, is called.

- [ ] "Drawing a shape."

**Explanation:** The output will be "Drawing a circle." The `draw` method of the `Circle` class, which implements the `Shape` interface, is called.

- [ ] Compilation error

**Explanation:** The output will be "Drawing a circle." The `draw` method of the `Circle` class, which implements the `Shape` interface, is called.

- [x] "Drawing a circle."

47. In Java, what is the access modifier for a class member that is accessible within the same package but not from other packages?

- [ ] `public`
      **Explanation:** The default (package-private) access modifier allows access within the same package but not from other packages.
- [ ] `private`
      **Explanation:** The default (package-private) access modifier allows access within the same package but not from other packages.
- [ ] `protected`
      **Explanation:** The default (package-private) access modifier allows access within the same package but not from other packages.
- [x] Default (no modifier)

48. What is the purpose of an abstract method in an interface in Java?

- [ ] To provide a method with an implementation.
      **Explanation:** An abstract method in an interface defines a method signature that implementing classes must provide an implementation for.
- [x] To declare a method signature that implementing classes must define.
- [ ] To create a static method.
      **Explanation:** An abstract method in an interface defines a method signature that implementing classes must provide an implementation for.
- [ ] To prevent method overriding.
      **Explanation:** An abstract method in an interface defines a method signature that implementing classes must provide an implementation for.

49. In Java, what is the primary difference between an abstract class and an interface?

- [x] An abstract class can have both abstract and concrete methods, while an interface can only have abstract methods.
- [ ] An abstract class can have variables, while an interface cannot.

**Explanation:** The primary difference is that an abstract class can have both abstract and concrete methods, while an interface can only have abstract methods.

- [ ] An interface can have constructors, while an abstract class cannot.

**Explanation:** The primary difference is that an abstract class can have both abstract and concrete methods, while an interface can only have abstract methods.

- [ ] An abstract class can be instantiated, while an interface cannot.

**Explanation:** The primary difference is that an abstract class can have both abstract and concrete methods, while an interface can only have abstract methods.

50. Consider the following Java code:

```java
interface Printable {
    void print();
}

class Document implements Printable {
    public void print() {
        System.out.println("Printing a document.");
    }
}

public class Main {
    public static void main(String[] args) {
        Printable printable = new Document();
        printable.print();
    }
}
```

What is the output of this code?

- [ ] "Printing a document."
      **Explanation:** The output will be "Printing a document." The `print` method of the `Document` class, which implements the `Printable` interface, is called.
- [ ] "Printing a printable."
      **Explanation:** The output will be "Printing a document." The `print` method of the `Document` class, which implements the `Printable` interface, is called.
- [ ] Compilation error
      **Explanation:** The output will be "Printing a document." The `print` method of the `Document` class, which implements the `Printable` interface, is called.
- [x] "Printing a document."
