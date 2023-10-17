1. **True or False: Polymorphism allows objects of different classes to be treated as objects of a common superclass.**

   - [x] True
   - [ ] False\
     - **Explanation:** Polymorphism allows objects of different classes to be treated as objects of a common superclass, promoting flexibility in code design.

2. **True or False: Method overloading in Java allows multiple methods with the same name in the same class, as long as they have the same number and type of parameters.**

   - [x] True
   - [ ] False \* **Explanation:** True. Method overloading enables the definition of multiple methods in the same class with the same name but different parameter lists.

3. **Which of the following best defines polymorphism in Java?**

   - [ ] The ability to access an object's attributes.\

     - **Explanation:** Polymorphism in Java allows an object to take on many forms by behaving differently based on its actual class or type.

   - [x] The ability of an object to take on many forms.
   - [ ] The ability to create objects from abstract classes.\

     - **Explanation:** Polymorphism in Java allows an object to take on many forms by behaving differently based on its actual class or type.

   - [ ] The ability to inherit from multiple classes.\
     - **Explanation:** Polymorphism in Java allows an object to take on many forms by behaving differently based on its actual class or type.

4. **What is the primary difference between method overloading and method overriding in Java?**

   - [ ] Method overloading allows methods with the same name and parameters, while method overriding does not.\
          -**Explanation**:Method overloading involves multiple methods with the same name but different parameters, while method overriding involves a subclass providing a specific implementation for a method defined in its superclass.
   - [x] Method overloading involves multiple methods with the same name but different parameters, while method overriding involves a subclass providing a specific implementation for a method defined in its superclass.\
   - [ ] Method overriding is the same as method overloading.
         --**Explanation**:Method overloading involves multiple methods with the same name but different parameters, while method overriding involves a subclass providing a specific implementation for a method defined in its superclass.
   - [ ] Method overloading is only possible in abstract classes.\
          --**Explanation**:Method overloading involves multiple methods with the same name but different parameters, while method overriding involves a subclass providing a specific implementation for a method defined in its superclass.

5. **In Java, which keyword is used to indicate that a method can be overridden by a subclass?**

   - [ ] `final`\
     - **Explanation:** The `abstract` keyword is used to declare a method as abstract and indicates that it can be overridden by a subclass.
   - [ ] `static`\
     - **Explanation:** The `abstract` keyword is used to declare a method as abstract and indicates that it can be overridden by a subclass.
   - [x] `abstract`
   - [ ] `super`\
     - **Explanation:** The `abstract` keyword is used to declare a method as abstract and indicates that it can be overridden by a subclass.

6. Given the following code, which method is invoked at runtime when you call `myObject.printInfo()`?

```java
class Base {
    void printInfo() {
        System.out.println("Info from the Base class.");
    }
}

class Derived extends Base {
    void printInfo() {
        System.out.println("Info from the Derived class.");
    }
}

Base myObject = new Derived();
```

- [ ] `Base` class's `printInfo` method.\ - **Explanation:** In this example of runtime polymorphism, the `Derived` class's `printInfo` method is invoked since `myObject` is of type `Base` but refers to an instance of `Derived`.
- [x] `Derived` class's `printInfo` method.
- [ ] An error will occur.\ - **Explanation:** In this example of runtime polymorphism, the `Derived` class's `printInfo` method is invoked since `myObject` is of type `Base` but refers to an instance of `Derived`.
- [ ] `Base` class's `printInfo` method, but it will print "Info from the Derived class."\ - **Explanation:** In this example of runtime polymorphism, the `Derived` class's `printInfo` method is invoked since `myObject` is of type `Base` but refers to an instance of `Derived`.

7. Which of the following is an example of method overloading?

```java
class Example {
    void printMessage(String message) {
        System.out.println(message);
    }

    void printMessage(String message, int times) {
        for (int i = 0; i < times; i++) {
            System.out.println(message);
        }
    }
}
```

- [ ] This is not an example of method overloading.\
       --**Explanation**:It is right example of method overloading as signature is varying
- [x] This is an example of method overloading.
- [ ] This code will result in a compilation error.\
       --**Explanation**:It is right example of method overloading as signature is varying
- [ ] This code demonstrates method overriding.\
       --**Explanation**:It is right example of method overloading as signature is varying

8. In the context of method overriding, what is the purpose of the `@Override` annotation in Java?

   - [x] It is used to indicate that a method in a subclass is intended to override a method in its superclass. It helps catch compile-time errors if the intended method is not an override.

   - [ ] It is used to mark methods as private to prevent any further overriding.\
          --**Explanation**:It helps catch compile-time errors if the intended method is not an override
   - [ ] It is used to specify the access modifier of the overridden method.\
          --**Explanation**:It helps catch compile-time errors if the intended method is not an override
   - [ ] It is not required in method overriding.\
          --**Explanation**:It helps catch compile-time errors if the intended method is not an override

9. Consider the following code snippet:

```java
public class Animal {
    void makeSound() {
        System.out.println("Animal makes a sound.");
    }
}

public class Dog extends Animal {
    void makeSound() {
        System.out.println("Dog barks.");
    }
}

Animal myDog = new Dog();
myDog.makeSound();
```

What is the output when you call `myDog.makeSound()`?

- [ ] "Animal makes a sound."\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.
- [x] "Dog barks."
- [ ] An error will occur.\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.
- [ ] "Animal makes a sound," followed by "Dog barks."\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.

10. In the context of polymorphism, which keyword is used to explicitly call a method from the superclass that has been overridden in a subclass?

- [ ] `new`\
  - **Explanation:** The `super` keyword is used to call a method from the superclass that has been overridden in a subclass, providing a way to access the superclass's behavior when needed.
- [ ] `override`\
  - **Explanation:** The `super` keyword is used to call a method from the superclass that has been overridden in a subclass, providing a way to access the superclass's behavior when needed.
- [x] `super`
- [ ] `this`\
  - **Explanation:** The `super` keyword is used to call a method from the superclass that has been overridden in a subclass, providing a way to access the superclass's behavior when needed.

11. **True or False: Polymorphism can be achieved through method overloading.**

- [ ] True\
  - **Explanation:** Polymorphism is primarily achieved through method overriding and interface implementations. Method overloading is a different concept that allows multiple methods with the same name in a class but with different parameters.
- [x] False

12. **True or False: In Java, a subclass can call private methods of its superclass.**

- [ ] True\
  - **Explanation:** False. Private methods in a superclass are not visible to the subclass, and thus, they cannot be directly called or overridden by the subclass.
- [x] False

13. **What is the key benefit of using polymorphism in object-oriented programming?**

- [ ] Reducing code duplication.\

  - **Explanation:** The primary benefit of polymorphism is enhancing code flexibility and reusability by allowing objects of different classes to be treated as objects of a common superclass.

- [ ] Enhancing program execution speed.\

  - **Explanation:** The primary benefit of polymorphism is enhancing code flexibility and reusability by allowing objects of different classes to be treated as objects of a common superclass.

- [x] Enhancing code flexibility and reusability.
- [ ] Improving data encapsulation.\
  - **Explanation:** The primary benefit of polymorphism is enhancing code flexibility and reusability by allowing objects of different classes to be treated as objects of a common superclass.

14. **Which of the following statements is true regarding method overriding in Java?**

- [x] The overridden method in the subclass must have the same method signature as the method in the superclass.
- [ ] The overridden method in the subclass can have a different return type than the method in the superclass.\
  - **Explanation:** Method overriding requires the subclass method to have the same method signature (name, parameter types) as the superclass method.
- [ ] The access modifier of the overridden method in the subclass cannot be more restrictive than that of the superclass method.\
  - **Explanation:** Method overriding requires the subclass method to have the same method signature (name, parameter types) as the superclass method.
- [ ] A subclass can override any method from its superclass, regardless of the method's access modifier.\
  - **Explanation:** Method overriding requires the subclass method to have the same method signature (name, parameter types) as the superclass method.

15. **Which type of polymorphism is exhibited in the code below?**

```java
Shape shape = new Circle();
```

- [ ] Compile-time (static) polymorphism\
  - **Explanation:** The type of `shape` is determined at runtime, and it demonstrates runtime (dynamic) polymorphism.
- [ ] Operator polymorphism
  - **Explanation:** The type of `shape` is determined at runtime, and it demonstrates runtime (dynamic) polymorphism.\
- [x] Runtime (dynamic) polymorphism
- [ ] Method polymorphism\
  - **Explanation:** The type of `shape` is determined at runtime, and it demonstrates runtime (dynamic) polymorphism.

16. Consider the following code:

```java
class Animal {
    void makeSound() {
        System.out.println("Animal makes a sound.");
    }
}

class Dog extends Animal {
    void makeSound() {
        System.out.println("Dog barks.");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal myDog = new Dog();
        myDog.makeSound();
    }
}
```

What is the output when you run the `main` method?

- [ ] "Animal makes a sound."\
  - **Explanation:** The output is "Dog barks." This is an example of runtime polymorphism where the `makeSound` method of the `Dog` class is invoked.
- [x] "Dog barks."
- [ ] An error will occur.\
  - **Explanation:** The output is "Dog barks." This is an example of runtime polymorphism where the `makeSound` method of the `Dog` class is invoked.
- [ ] "Animal makes a sound," followed by "Dog barks."\
  - **Explanation:** The output is "Dog barks." This is an example of runtime polymorphism where the `makeSound` method of the `Dog` class is invoked.

17. Which of the following code snippets demonstrates method overloading?

```java
a) void printMessage(String message) {
       System.out.println(message);
}

b) void printMessage(int count, String message) {
       for (int i = 0; i < count; i++) {
           System.out.println(message);
       }
}
```

- [x] Both (a) and (b)
- [ ] Only (a)\
  - **Explanation:** Both (a) and (b) demonstrate method overloading because they have the same method name but different parameter lists.
- [ ] Only (b)\
  - **Explanation:** Both (a) and (b) demonstrate method overloading because they have the same method name but different parameter lists.
- [ ] Neither (a) nor (b)\
  - **Explanation:** Both (a) and (b) demonstrate method overloading because they have the same method name but different parameter lists.

18. In the context of method overriding, which annotation can be used to inform the compiler that a method in a subclass is intended to override a method in its superclass?

- [x] `@Override`
- [ ] `@OverrideMethod` \- **Explanation:** The `@Override` annotation is used to indicate that a method in a subclass is intended to override a method in its superclass. It helps catch compile-time errors if the intended method is not an override.
- [ ] `@OverrideSuper`\ - **Explanation:** The `@Override` annotation is used to indicate that a method in a subclass is intended to override a method in its superclass. It helps catch compile-time errors if the intended method is not an override.
- [ ] `@OverrideClass` \- **Explanation:** The `@Override` annotation is used to indicate that a method in a subclass is intended to override a method in its superclass. It helps catch compile-time errors if the intended method is not an override.

19. Given the following code:

```java
class Parent {
    void display() {
        System.out.println("Parent's display");
    }
}

class Child extends Parent {
    void display() {
        System.out.println("Child's display");
    }
}

public class Main {
    public static void main(String[] args) {
        Parent p = new Child();
        p.display();
    }
}
```

What is the output when you run the `main` method?

- [ ] "Parent's display"\
  - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.
- [x] "Child's display"
- [ ] An error will occur.\
  - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.
- [ ] The code will not compile.\
  - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.

20. In Java, what is the main purpose of method overloading?

- [ ] Allowing a method to have multiple return types.\
  - **Explanation:** Method overloading allows you to provide multiple ways to call the same method with different parameters, enhancing code flexibility and reusability.
- [ ] Enforcing encapsulation.\
  - **Explanation:** Method overloading allows you to provide multiple ways to call the same method with different parameters, enhancing code flexibility and reusability.
- [x] Providing multiple ways to call the same method with different parameters.
- [ ] Ensuring that a method is only called once.\
  - **Explanation:** Method overloading allows you to provide multiple ways to call the same method with different parameters, enhancing code flexibility and reusability.

21. **True or False: Polymorphism is a feature that is exclusive to object-oriented programming languages like Java.**

- [ ] True \- **Explanation:** False. Polymorphism is a concept present in various programming paradigms, not just object-oriented languages like Java.

- [x] False

22. **True or False: Method overloading is based on the return type of a method.**

- [x] True
- [ ] False\
  - **Explanation:** True. Method overloading is determined by the number and types of parameters as well as the return type of a method.

23. **What is the primary difference between method overloading and method overriding in Java?**

- [ ] Method overloading allows methods with the same name and parameters, while method overriding does not.\
       --**Explanation**:Method overloading involves multiple methods with the same name but different parameters
- [x] Method overloading involves multiple methods with the same name but different parameters, while method overriding involves a subclass providing a specific implementation for a method defined in its superclass.
- [ ] Method overriding is the same as method overloading.\
       --**Explanation**:Method overloading involves multiple methods with the same name but different parameters
- [ ] Method overloading is only possible in abstract classes.\
       --**Explanation**:Method overloading involves multiple methods with the same name but different parameters

24. **In Java, what is the superclass of all classes?**

- [ ] `Object` \- **Explanation:** The `java.lang.Object` class is the implicit superclass of all classes in Java.
- [ ] `Main`\ - **Explanation:** The `java.lang.Object` class is the implicit superclass of all classes in Java.
- [x] `java.lang.Object`
- [ ] `SuperClass` \- **Explanation:** The `java.lang.Object` class is the implicit superclass of all classes in Java.

25. **What is a potential use case for method overloading in Java?**

- [ ] Ensuring a method is hidden from subclasses.\
  - **Explanation:** Method overloading in Java provides multiple versions of a method with different parameter lists, which can be used for convenience and flexibility in calling methods.
- [ ] Restricting the access to methods.\
  - **Explanation:** Method overloading in Java provides multiple versions of a method with different parameter lists, which can be used for convenience and flexibility in calling methods.
- [x] Providing multiple versions of a method with different parameter lists for convenience and flexibility.
- [ ] Defining abstract methods.\
  - **Explanation:** Method overloading in Java provides multiple versions of a method with different parameter lists, which can be used for convenience and flexibility in calling methods.

26. Consider the following code snippet:

```java
class A {
    void display() {
        System.out.println("A's display");
    }
}

class B extends A {
    void display() {
        System.out.println("B's display");
    }
}

public class Main {
    public static void main(String[] args) {
        A obj = new B();
        obj.display();
    }
}
```

What is the output when you run the `main` method?

- [ ] "A's display" \- **Explanation:** The output is "B's display" due to runtime polymorphism. The method of the actual object (B) is called.
- [x] "B's display"
- [ ] An error will occur.\ - **Explanation:** The output is "B's display" due to runtime polymorphism. The method of the actual object (B) is called.
- [ ] The code will not compile.\ - **Explanation:** The output is "B's display" due to runtime polymorphism. The method of the actual object (B) is called.

27. Which of the following code snippets demonstrates method overriding in Java?

```java
a) void printMessage(String message) {
       System.out.println(message);
}

b) @Override
   void printMessage(String message) {
       System.out.println(message);
}
```

- [ ] Both (a) and (b) - \*\*Explanation:\*\* Method overriding is demonstrated by the `@Override` annotation, as shown in snippet (b).
- [x] Only (b)
- [ ] Only (a) - \*\*Explanation:\*\* Method overriding is demonstrated by the `@Override` annotation, as shown in snippet (b).
- [ ] Neither (a) nor (b) - \*\*Explanation:\*\* Method overriding is demonstrated by the `@Override` annotation, as shown in snippet (b).

28. In Java, which keyword is used to call a method from within the same class, without creating an instance of the class?

- [ ] `new`\
  - **Explanation:** The `static` keyword is used to define methods that can be called without creating an instance of the class.
- [ ] `invoke`\
  - **Explanation:** The `static` keyword is used to define methods that can be called without creating an instance of the class.
- [ ] `this`\
  - **Explanation:** The `static` keyword is used to define methods that can be called without creating an instance of the class.
- [x] `static`

29. Given the following code snippet:

```java
class Figure {
    void draw() {
        System.out.println("Drawing a figure.");
    }
}

class Circle extends Figure {
    void draw() {
        System.out.println("Drawing a circle.");
    }
}

class Square extends Figure {
    void draw() {
        System.out.println("Drawing a square.");
    }
}

public class Main {
    public static void main(String[] args) {
        Figure f1 = new Circle();
        Figure f2 = new Square();
        f1.draw();
        f2.draw();
    }
}
```

What is the output when you run the `main` method?

- [ ] "Drawing a figure." twice -\ **Explanation:** The output is "Drawing a circle." followed by "Drawing a square." due to runtime polymorphism.

- [x] "Drawing a circle." followed by "Drawing a square."
- [ ] "Drawing a square." twice \- **Explanation:** The output is "Drawing a circle." followed by "Drawing a square." due to runtime polymorphism.

- [ ] "Drawing a circle." twice \- **Explanation:** The output is "Drawing a circle." followed by "Drawing a square." due to runtime polymorphism.

30. In Java, can you overload a method by just changing its return type?

- [ ] Yes, as long as the method name and parameter list are the same.\ - **Explanation:** Method overloading in Java depends on the number and types of parameters, not just the return type.
- [x] No, method overloading is not based on the return type alone; it depends on the parameter list.
- [ ] Yes, as long as the method name is unique within the class. \- **Explanation:** Method overloading in Java depends on the number and types of parameters, not just the return type.
- [ ] Yes, as long as the method name is unique in the entire program.\ - **Explanation:** Method overloading in Java depends on the number and types of parameters, not just the return type.

31. **True or False: Polymorphism allows you to create objects of abstract classes.**

- [ ] True\ - **Explanation:** False. You cannot create objects of abstract classes; they are meant to be subclassed, and their constructors cannot be invoked directly.
- [x] False

32. **True or False: In method overloading, it is possible to have the same method name and the same parameter list but with different return types.**

- [x] True
- [ ] False\ - **Explanation:** True. Method overloading is based on the number and types of parameters, and the return type does not play a role in determining method overloads.

33. **What is method overriding in Java?**

- [ ] The ability to create multiple methods with the same name but different parameters in a class.\
       --**Explanation**:The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.
- [ ] The process of hiding an inherited method from the superclass.\
       --**Explanation**:The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.
- [x] The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.
- [ ] The ability to define methods with the same name and parameters in different classes.\
       --**Explanation**:The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.

34. **What is the main advantage of polymorphism in Java?**

- [ ] It reduces code complexity.\
       --**Explanation**:It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.
- [ ] It improves code performance.\
       --**Explanation**:It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.
- [x] It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.
- [ ] It enforces strong data encapsulation.\
       --**Explanation**:It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.

35. **Which keyword is used to prevent a method from being overridden in a Java subclass?**

- [ ] `extend` \- **Explanation:** The `final` keyword is used to prevent a method from being overridden in a subclass.
- [ ] `private` \- **Explanation:** The `final` keyword is used to prevent a method from being overridden in a subclass.
- [ ] `final` \- **Explanation:** The `final` keyword is used to prevent a method from being overridden in a subclass.
- [x] `static`

36. Consider the following code:

```java
class Parent {
    void display() {
        System.out.println("Parent's display");
    }
}

class Child extends Parent {
    void display() {
        System.out.println("Child's display");
    }
}

public class Main {
    public static void main(String[] args) {
        Parent p = new Child();
        p.display();
    }
}
```

What is the output when you run the `main` method?

- [ ] "Parent's display"\ - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.
- [x] "Child's display"
- [ ] An error will occur. \- **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.
- [ ] The code will not compile.\ - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.

37. Which of the following code snippets demonstrates method overloading in Java?

```java
a) void printMessage(String message) {
       System.out.println(message);
}

b) void printMessage(String msg) {
       System.out.println(msg);
}
```

- [ ] Both (a) and (b)\
  - **Explanation:** Only snippet (b) demonstrates method overloading. The method name is the same, but the parameter name is different, which is allowed.
- [ ] Only (a)\
  - **Explanation:** Only snippet (b) demonstrates method overloading. The method name is the same, but the parameter name is different, which is allowed.
- [x] Only (b)
- [ ] Neither (a) nor (b)\
  - **Explanation:** Only snippet (b) demonstrates method overloading. The method name is the same, but the parameter name is different, which is allowed.

38. In Java, which keyword is used to explicitly call a superclass constructor from a subclass constructor?

- [x] `super`
- [ ] `this`\
  - **Explanation:** The `super` keyword is used to call a superclass constructor from a subclass constructor.
- [ ] `base`\
  - **Explanation:** The `super` keyword is used to call a superclass constructor from a subclass constructor.
- [ ] `parent`\
  - **Explanation:** The `super` keyword is used to call a superclass constructor from a subclass constructor.

39. Given the following code:

```java
class Animal {
    void makeSound() {
        System.out.println("Animal makes a sound.");
    }
}

class Dog extends Animal {
    void makeSound() {
        System.out.println("Dog barks.");
    }
}

Animal myDog = new Dog();
myDog.makeSound();
```

What is the output when you call `myDog.makeSound()`?

- [ ] "Animal makes a sound."\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.
- [x] "Dog barks."
- [ ] An error will occur.\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.
- [ ] "Animal makes a sound," followed by "Dog barks."\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.

40. Which of the following is a valid reason for using method overloading in Java?

- [ ] To make a method inaccessible to subclasses.\
  - **Explanation:** Method overloading in Java is used to provide multiple ways to call the same method with different parameter lists, enhancing code flexibility and reusability.\
- [x] To provide multiple ways to call the same method with different parameter lists.
- [ ] To enforce encapsulation by restricting access to methods.\
  - **Explanation:** Method overloading in Java is used to provide multiple ways to call the same method with different parameter lists, enhancing code flexibility and reusability.\
- [ ] To define abstract methods that must be implemented by subclasses.\

  - **Explanation:** Method overloading in Java is used to provide multiple ways to call the same method with different parameter lists, enhancing code flexibility and reusability.\

    41.**True or False: Polymorphism allows you to create objects of abstract classes.**

  * [ ] True\
    - **Explanation:** False. You cannot create objects of abstract classes; they are meant to be subclassed, and their constructors cannot be invoked directly.
  * [x] False

42. **True or False: In method overloading, it is possible to have the same method name and the same parameter list but with different return types.**

- [x] True
- [ ] False\
  - **Explanation:** True. Method overloading is based on the number and types of parameters, and the return type does not play a role in determining method overloads.

43. **What is method overriding in Java?**

- [ ] The ability to create multiple methods with the same name but different parameters in a class.\
       --**Explanation**: The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.
- [ ] The process of hiding an inherited method from the superclass.\
       --**Explanation**: The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.
- [x] The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.
- [ ] The ability to define methods with the same name and parameters in different classes.\
       --**Explanation**: The ability of a subclass to provide a specific implementation for a method that is already defined in its superclass.

44. **What is the main advantage of polymorphism in Java?**

- [ ] It reduces code complexity.\
       --**Explanation**: It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.
- [ ] It improves code performance.\
       --**Explanation**: It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.
- [x] It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.
- [ ] It enforces strong data encapsulation.\
       --**Explanation**: It enhances code flexibility and extensibility by allowing objects of different classes to be treated as objects of a common superclass.

45. **Which keyword is used to prevent a method from being overridden in a Java subclass?**

- [ ] `extend`\
- **Explanation:** The `final` keyword is used to prevent a method from being overridden in a subclass.
- [ ] `private`\
  - **Explanation:** The `final` keyword is used to prevent a method from being overridden in a subclass.
- [ ] `final`\
- **Explanation:** The `final` keyword is used to prevent a method from being overridden in a subclass.
- [x] `static`

46. Consider the following code:

```java
class Parent {
    void display() {
        System.out.println("Parent's display");
    }
}

class Child extends Parent {
    void display() {
        System.out.println("Child's display");
    }
}

public class Main {
    public static void main(String[] args) {
        Parent p = new Child();
        p.display();
    }
}
```

What is the output when you run the `main` method?

- [ ] "Parent's display"\
  - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.
- [x] "Child's display"
- [ ] An error will occur.\
  - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.
- [ ] The code will not compile.\
  - **Explanation:** The output is "Child's display" due to runtime polymorphism. The method of the actual object (Child) is called.

47. Which of the following code snippets demonstrates method overloading in Java?

```java
a) void printMessage(String message) {
       System.out.println(message);
}

b) void printMessage(String msg) {
       System.out.println(msg);
}
```

- [ ] Both (a) and (b)\
  - **Explanation:** Only snippet (b) demonstrates method overloading. The method name is the same, but the parameter name is different, which is allowed.
- [ ] Only (a)\
  - **Explanation:** Only snippet (b) demonstrates method overloading. The method name is the same, but the parameter name is different, which is allowed.
- [x] Only (b)
- [ ] Neither (a) nor (b)\
  - **Explanation:** Only snippet (b) demonstrates method overloading. The method name is the same, but the parameter name is different, which is allowed.

48. In Java, which keyword is used to explicitly call a superclass constructor from a subclass constructor?

- [x] `super`
- [ ] `this`\
- **Explanation:** The `super` keyword is used to call a superclass constructor from a subclass constructor.
- [ ] `base`\
- **Explanation:** The `super` keyword is used to call a superclass constructor from a subclass constructor.
- [ ] `parent`\
- **Explanation:** The `super` keyword is used to call a superclass constructor from a subclass constructor.

49. Given the following code:

```java
class Animal {
    void makeSound() {
        System.out.println("Animal makes a sound.");
    }
}

class Dog extends Animal {
    void makeSound() {
        System.out.println("Dog barks.");
    }
}

Animal myDog = new Dog();
myDog.makeSound();
```

What is the output when you call `myDog.makeSound()`?

- [ ] "Animal makes a sound."\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.
- [x] "Dog barks."
- [ ] An error will occur.\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.
- [ ] "Animal makes a sound," followed by "Dog barks."\
  - **Explanation:** In this example of runtime polymorphism, the `makeSound` method of the `Dog` class is invoked because `myDog` is an instance of `Dog` even though it's declared as an `Animal`.

50. Which of the following is a valid reason for using method overloading in Java?

- [ ] To make a method inaccessible to subclasses.\

  - **Explanation:** Method overloading in Java is used to provide multiple ways to call the same method with different parameter lists, enhancing code flexibility and reusability.

- [x] To provide multiple ways to call the same method with different parameter lists.
- [ ] To enforce encapsulation by restricting access to methods.\

  - **Explanation:** Method overloading in Java is used to provide multiple ways to call the same method with different parameter lists, enhancing code flexibility and reusability.

- [ ] To define abstract methods that must be implemented by subclasses.\
  - **Explanation:** Method overloading in Java is used to provide multiple ways to call the same method with different parameter lists, enhancing code flexibility and reusability.
