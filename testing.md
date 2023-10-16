1. True / \[x\] False

   - Statement: In Java, every class automatically inherits from the `Object` class.
   - Explanation: True. In Java, every class implicitly extends the `Object` class, which means it inherits the methods and behaviors of the `Object` class.

2. True / \[ \] False

   - Statement: The `super` keyword is used to call a superclass constructor.
   - Explanation: True. The `super` keyword is used to call a constructor in the superclass of a subclass. It is often used to initialize the inherited properties.

3. Which keyword is used to indicate that a class is inheriting from another class in Java?

   - [ ] extends
     - Explanation: The `extends` keyword is used to indicate that a class is inheriting from another class.
   - [ ] implement
     - Explanation: The `extends` keyword is used to indicate that a class is inheriting from another class.
   - [ ] interface
     - Explanation: The `extends` keyword is used to indicate that a class is inheriting from another class.
   - [x] extends

4. What is method overriding in Java?

   - [ ] Creating new methods with the same name in a class.
     - Explanation: Method overriding in Java is the process of providing a new implementation for a method in a subclass that is already defined in its superclass.
   - [x] Providing a new implementation for a method in a subclass that is already defined in its superclass.
   - [ ] Overloading a method with a different number of parameters.
     - Explanation: Method overriding in Java is the process of providing a new implementation for a method in a subclass that is already defined in its superclass.
   - [ ] Accessing superclass methods using the `super` keyword.
     - Explanation: Method overriding in Java is the process of providing a new implementation for a method in a subclass that is already defined in its superclass.

5. In Java, which class is at the top of the class hierarchy and is implicitly extended by all classes?

   - [ ] Abstract
     - Explanation: The `Object` class is at the top of the class hierarchy in Java and is implicitly extended by all classes.
   - [ ] Exception
     - Explanation: The `Object` class is at the top of the class hierarchy in Java and is implicitly extended by all classes.
   - [ ] Main
     - Explanation: The `Object` class is at the top of the class hierarchy in Java and is implicitly extended by all classes.
   - [x] Object

6. Consider the following code snippet:

```java
class Parent {
    int x = 10;
}

class Child extends Parent {
    int x = 20;
    void display() {
        System.out.println(super.x);
    }
}
```

What will be the output of `new Child().display()`?

- [ ] 10
- Explanation: The `super` keyword is used to access the superclass's member. In this case, it will print the `x` from the `Parent` class, which is 10
- [ ] 20
- Explanation: The `super` keyword is used to access the superclass's member. In this case, it will print the `x` from the `Parent` class, which is 10
- [x] 10
      .

7. In Java, if a subclass has a method with the same name and parameter list as a method in its superclass, what is it called?

   - [x] Method overriding
   - [ ] Method overloading

     - Explanation: When a subclass has a method with the same name and parameter list as a method in its superclass, it's called method overriding.

   - [ ] Method shadowing

     - Explanation: When a subclass has a method with the same name and parameter list as a method in its superclass, it's called method overriding.

   - [ ] Method inheritance
     - Explanation: When a subclass has a method with the same name and parameter list as a method in its superclass, it's called method overriding.

8. Given the following class hierarchy:

```java
class Animal {
    void makeSound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    void makeSound() {
        System.out.println("Dog barks");
    }
}
```

If we create an instance of `Dog` and call `makeSound()`, what will be the output?

- [ ] Animal makes a sound
- Explanation: In method overriding, the subclass method is invoked. So, calling `makeSound()` on a `Dog` object will print "Dog barks."
- [ ] Dog makes a sound
- Explanation: In method overriding, the subclass method is invoked. So, calling `makeSound()` on a `Dog` object will print "Dog barks."
- [x] Dog barks

9. In Java, can you use the `super` keyword to access a superclass's private field in a subclass?

   - [ ] Yes
     - Explanation: No, the `super` keyword cannot be used to access a superclass's private field in a subclass because private fields are not accessible in subclasses.
   - [x] No

10. What is the purpose of the `Object` class in Java's inheritance hierarchy?

- [ ] It is a placeholder class that does not serve any practical purpose.
- Explanation: The `Object` class in Java provides common methods (e.g., `equals`, `hashCode`, `toString`) that are inherited by all classes, making it a fundamental part of Java's inheritance hierarchy.

- [ ] It is used for implementing abstract methods in all classes.
- Explanation: The `Object` class in Java provides common methods (e.g., `equals`, `hashCode`, `toString`) that are inherited by all classes, making it a fundamental part of Java's inheritance hierarchy.

- [x] It provides common methods that are inherited by all classes in Java.
- [ ] It is used only for creating objects.
- Explanation: The `Object` class in Java provides common methods (e.g., `equals`, `hashCode`, `toString`) that are inherited by all classes, making it a fundamental part of Java's inheritance hierarchy.

11. True / \[x \] False

- Statement: Inheritance in Java allows a subclass to inherit the private members (fields and methods) of its superclass.
- Explanation: False. In Java, private members of a superclass are not accessible in a subclass, even through inheritance.

12. True / \[x\] False

- Statement: In method overriding, it is mandatory for the return type of the overriding method to be the same as the return type of the overridden method.
- Explanation: False. In method overriding, the return type of the overriding method can be a subtype of the return type of the overridden method (covariant return types).

13. What is the main benefit of using inheritance in object-oriented programming?

- [ ] It reduces code duplication.
  - Explanation: The main benefit of inheritance is to promote code reusability and the creation of a class hierarchy.
- [ ] It enhances encapsulation.
  - Explanation: The main benefit of inheritance is to promote code reusability and the creation of a class hierarchy.
- [ ] It simplifies the debugging process.
  - Explanation: The main benefit of inheritance is to promote code reusability and the creation of a class hierarchy.
- [x] It promotes code reusability and the creation of a class hierarchy.

14. Which keyword is used to prevent a class from being subclassed in Java?

- [ ] sealed
- Explanation: The `final` keyword is used to indicate that a class cannot be subclassed.
- [ ] abstract
- Explanation: The `final` keyword is used to indicate that a class cannot be subclassed.
- [ ] final
- Explanation: The `final` keyword is used to indicate that a class cannot be subclassed.
- [x] final

15. What is the primary purpose of the `extends` keyword in Java?

- [ ] To create a new instance of a class.
- Explanation: The `extends` keyword is used to indicate that a class is inheriting from another class.
- [ ] To call a method in the superclass.
- Explanation: The `extends` keyword is used to indicate that a class is inheriting from another class.
- [ ] To implement an interface.
- Explanation: The `extends` keyword is used to indicate that a class is inheriting from another class.
- [x] To indicate that a class is inheriting from another class.

16. Consider the following code snippet:

```java
class A {
    int x = 5;
}

class B extends A {
    int x = 10;
    void display() {
        System.out.println(x);
    }
}
```

What will be the output of `new B().display()`?

- [ ] 5
- Explanation: In this case, `x` in the `display()` method refers to the `x` in the `B` class (subclass).
- [ ] 10
- Explanation: In this case, `x` in the `display()` method refers to the `x` in the `B` class (subclass).
- [x] 10

17. In Java, if a subclass and its superclass both have a method with the same name, and you call that method on an instance of the subclass, which method gets executed?

- [ ] The subclass method.
  - Explanation: When a subclass and its superclass have methods with the same name, the subclass method takes precedence.
- [ ] The superclass method.
  - Explanation: When a subclass and its superclass have methods with the same name, the subclass method takes precedence.
- [ ] Both methods get executed simultaneously.
  - Explanation: When a subclass and its superclass have methods with the same name, the subclass method takes precedence.
- [x] The subclass method.

18. What is the purpose of the `super` keyword in a constructor in Java?

- [x] To call a constructor in the superclass.
- [ ] To create a new instance of the superclass.
  - Explanation: The `super` keyword in a constructor is used to call a constructor in the superclass.
- [ ] To access private fields of the superclass.
  - Explanation: The `super` keyword in a constructor is used to call a constructor in the superclass.
- [ ] To prevent method overriding in the superclass.
  - Explanation: The `super` keyword in a constructor is used to call a constructor in the superclass.

19. In Java, can you override a static method in a subclass?

- [ ] Yes
  - Explanation: Static methods cannot be overridden in Java. They are associated with the class itself and not with instances.
- [x] No

20. Which method from the `Object` class is often overridden in user-defined classes to provide a string representation of the object?

- [ ] `clone()`
- Explanation: The `toString()` method from the `Object` class is often overridden in user-defined classes to provide a string representation of the object.
- [x] `toString()`
- [ ] `equals()`
- Explanation: The `toString()` method from the `Object` class is often overridden in user-defined classes to provide a string representation of the object.
- [ ] `hashCode()`
- Explanation: The `toString()` method from the `Object` class is often overridden in user-defined classes to provide a string representation of the object.

21. True / \[ \] False

- Statement: In Java, a subclass constructor must always explicitly call a constructor of the superclass using the `super` keyword.
- Explanation: True. If the subclass constructor does not explicitly call a superclass constructor using `super(...)`, the compiler will automatically insert a call to the no-argument constructor of the superclass.

22. True / \[x\] False

- Statement: The `Object` class in Java contains only static methods that are not inherited by other classes.
- Explanation: False. The `Object` class contains instance methods (e.g., `toString()`, `equals()`) that are inherited by all classes in Java.

23. What is a constructor in Java, and how is it related to inheritance?

- [ ] A constructor is a method used for method overloading.
  - Explanation: Constructors are used to initialize objects, and when a subclass is created, it must call a constructor in its superclass using `super(...)`.
- [ ] A constructor is a method used to access private fields in a class.
  - Explanation: Constructors are used to initialize objects, and when a subclass is created, it must call a constructor in its superclass using `super(...)`.
- [ ] Constructors have no relation to inheritance in Java.
  - Explanation: Constructors are used to initialize objects, and when a subclass is created, it must call a constructor in its superclass using `super(...)`.
- [x] A constructor is a special method used to initialize objects, and when a subclass is created, it must call a constructor in its superclass.

24. What is the role of the `protected` access modifier in Java?

- [ ] It allows access to a class from any other class.

  - Explanation: The `protected` access modifier allows access within the same package and by subclasses in other packages.

- [ ] It restricts access to only the class itself.

  - Explanation: The `protected` access modifier allows access within the same package and by subclasses in other packages.

- [x] It allows access within the same package and by subclasses in other packages.
- [ ] It makes a member inaccessible from all other classes.
  - Explanation: The `protected` access modifier allows access within the same package and by subclasses in other packages.

25. What is method hiding in Java?

- [ ] Method hiding is the same as method overriding.
- Explanation: Method hiding occurs when a subclass defines a static method with the same name as a static method in its superclass.
- [ ] It is a technique to protect a method from being overridden.
- Explanation: Method hiding occurs when a subclass defines a static method with the same name as a static method in its superclass.
- [ ] Method hiding is not a concept in Java.
- Explanation: Method hiding occurs when a subclass defines a static method with the same name as a static method in its superclass.
- [x] It is a situation where a subclass defines a static method with the same name as a static method in its superclass.

26. Consider the following code snippet:

```java
class Parent {
    void display() {
        System.out.println("Parent's display");
    }
}

class Child extends Parent {
    void display() {
        System.out.println("Child's display");
        super.display();
    }
}
```

What will be the output of `new Child().display()`?

- [ ] Parent's display
- Explanation: The `super.display()` call within the `Child` class calls the `display()` method in the `Parent` class first.
- [ ] Child's display
- Explanation: The `super.display()` call within the `Child` class calls the `display()` method in the `Parent` class first.
- [ ] Parent's display followed by Child's display
- Explanation: The `super.display()` call within the `Child` class calls the `display()` method in the `Parent` class first.
- [x] Child's display followed by Parent's display

27. Can you override a private method in a subclass in Java?

- [ ] Yes
  - Explanation: No, private methods in a superclass are not accessible in a subclass and therefore cannot be overridden.
- [x] No

28. What does the `@Override` annotation do in Java?

- [ ] It specifies that a method is static.
  - Explanation: The `@Override` annotation is used to indicate that a method is intended to override a method in a superclass.
- [ ] It is used to create new methods.
  - Explanation: The `@Override` annotation is used to indicate that a method is intended to override a method in a superclass.
- [x] It indicates that a method is intended to override a method in a superclass.
- [ ] It is used to specify a custom access modifier.
  - Explanation: The `@Override` annotation is used to indicate that a method is intended to override a method in a superclass.

29. In Java, if a subclass does not provide constructors, what happens during object creation?

- [ ] The compiler generates default constructors for the subclass.
- Explanation: If the subclass does not provide constructors, it implicitly calls the no-argument constructor of the superclass.
- [ ] The superclass constructors are automatically inherited.
- Explanation: If the subclass does not provide constructors, it implicitly calls the no-argument constructor of the superclass.
- [ ] The object cannot be created.
- Explanation: If the subclass does not provide constructors, it implicitly calls the no-argument constructor of the superclass.
- [x] The subclass implicitly calls the no-argument constructor of the superclass.

30. What is the significance of the `super()` call in a constructor in Java?

- [x] It calls a constructor in the superclass to perform initialization tasks.
- [ ] It creates a new instance of the subclass.
- Explanation: The `super()` call in a constructor is used to call a constructor in the superclass to perform initialization tasks.

- [ ] It is used to access private fields of the superclass.
- Explanation: The `super()` call in a constructor is used to call a constructor in the superclass to perform initialization tasks.

- [ ] It is required for method overriding.
- Explanation: The `super()` call in a constructor is used to call a constructor in the superclass to perform initialization tasks.

31. True / \[ \] False

- Statement: In Java, a class can inherit from multiple classes (i.e., support multiple inheritance).
- Explanation: False. In Java, a class can inherit from only one class (single inheritance), but it can implement multiple interfaces (multiple inheritance through interfaces).

32. True / \[x\] False

- Statement: All methods in a subclass must be overridden from the superclass.
- Explanation: False. Subclasses can have additional methods that are not present in the superclass. Not all methods need to be overridden.

33. What is the difference between inheritance and composition in object-oriented programming?

- [ ] Inheritance involves creating objects of one class within another class, while composition involves reusing a class's interface.

  - Explanation: Inheritance is about the "is-a" relationship, while composition is about the "has-a" relationship.

- [ ] Inheritance is a way to achieve code reusability, while composition is a way to establish an "is-a" relationship between classes.

  - Explanation: Inheritance is about the "is-a" relationship, while composition is about the "has-a" relationship.

- [x] Inheritance is an "is-a" relationship, where a subclass inherits properties and behaviors from a superclass, while composition is a "has-a" relationship, where a class is composed of other classes as parts.
- [ ] Inheritance and composition are the same concept with different names.
  - Explanation: Inheritance is about the "is-a" relationship, while composition is about the "has-a" relationship.

34. What is method overloading in Java?

- [ ] Providing a new implementation for a method in a subclass.

  - Explanation: Method overloading involves creating multiple methods in a class with the same name but different parameters.

- [ ] Creating a method with the same name and parameters in a class.

  - Explanation: Method overloading involves creating multiple methods in a class with the same name but different parameters.

- [ ] Overriding a method in a subclass.

  - Explanation: Method overloading involves creating multiple methods in a class with the same name but different parameters.

- [x] Creating multiple methods in a class with the same name but different parameters.

35. When a subclass extends a superclass, which members (fields and methods) of the superclass are inherited by the subclass?

- [ ] Only public members.
  - Explanation: When a subclass extends a superclass, all members except private members are inherited by the subclass.
- [ ] Only private members.
  - Explanation: When a subclass extends a superclass, all members except private members are inherited by the subclass.
- [ ] Only static members.
  - Explanation: When a subclass extends a superclass, all members except private members are inherited by the subclass.
- [x] All members except private members.

36. Consider the following code snippet:

```java
class Shape {
    void draw() {
        System.out.println("Drawing a shape");
    }
}

class Circle extends Shape {
    void draw() {
        System.out.println("Drawing a circle");
    }
}

class Test {
    public static void main(String[] args) {
        Shape s = new Circle();
        s.draw();
    }
}
```

What will be the output of the `main` method in the `Test` class?

- [ ] Drawing a shape
- Explanation: In this case, polymorphism allows the `draw` method of the `Circle` class to be called.
- [ ] Drawing a circle
- Explanation: In this case, polymorphism allows the `draw` method of the `Circle` class to be called.
- [x] Drawing a circle

37. In Java, if a superclass has a method with the `final` modifier, can it be overridden in a subclass?

- [ ] Yes
- Explanation: A method with the `final` modifier cannot be overridden in a subclass.
- [x] No

38. What is the purpose of the `super` keyword in a non-constructor method in Java?

- [ ] To create a new instance of the superclass.
- Explanation: The `super` keyword in a non-constructor method is used to access or invoke a method or member from the superclass.
- [x] To access or invoke a method or member from the superclass.
- [ ] To make a method final.
- Explanation: The `super` keyword in a non-constructor method is used to access or invoke a method or member from the superclass.
- [ ] To create a new instance of the subclass.
- Explanation: The `super` keyword in a non-constructor method is used to access or invoke a method or member from the superclass.

39. In Java, what happens when a subclass inherits a constructor from its superclass?

- [ ] The subclass constructor is automatically generated.
- Explanation: When a subclass inherits a constructor, it implicitly calls a constructor in the superclass using `super(...)`.
- [ ] The subclass constructor must be marked as `final`.
- Explanation: When a subclass inherits a constructor, it implicitly calls a constructor in the superclass using `super(...)`.
- [ ] The subclass constructor must be marked as `private`.
- Explanation: When a subclass inherits a constructor, it implicitly calls a constructor in the superclass using `super(...)`.
- [x] The subclass constructor implicitly calls a constructor in the superclass using `super(...)`.

40. What is the primary use of the `protected` keyword in Java?

- [ ] To restrict access to a class's methods and fields.
- Explanation: The `protected` keyword in Java provides access within the same package and by subclasses in other packages.
- [x] To provide access to methods and fields within the same package and by subclasses in other packages.
- [ ] To make all class members public.
- Explanation: The `protected` keyword in Java provides access within the same package and by subclasses in other packages.
- [ ] To indicate that a class is not inheritable.
- Explanation: The `protected` keyword in Java provides access within the same package and by subclasses in other packages.

41. True / \[x\] False

- Statement: The `super` keyword is used to access and modify private fields of the superclass in a subclass.
- Explanation: False. The `super` keyword cannot be used to access or modify private fields of the superclass in a subclass.

42. True / \[ \] False

- Statement: In Java, you can create an instance of an abstract class.
- Explanation: True. You can create an instance of a concrete subclass of an abstract class, but you cannot create an instance of the abstract class itself.

43. What is the primary advantage of using the `super` keyword in a subclass?

- [ ] It allows the subclass to override methods in the superclass.
- Explanation: The primary advantage of using the `super` keyword is to reuse and customize behavior from the superclass in a subclass.
- [ ] It prevents other classes from inheriting from the superclass.
- Explanation: The primary advantage of using the `super` keyword is to reuse and customize behavior from the superclass in a subclass.
- [ ] It provides access to private members of the superclass.
- Explanation: The primary advantage of using the `super` keyword is to reuse and customize behavior from the superclass in a subclass.
- [x] It facilitates the reuse and customization of behavior from the superclass.

44. In Java, what is the role of the `protected` access modifier with respect to methods and fields in a class?

- [ ] It makes all methods and fields public.
  - Explanation: The `protected` access modifier allows access to methods and fields within the same package and by subclasses in other packages.
- [x] It allows access to methods and fields within the same package and by subclasses in other packages.
- [ ] It restricts access to only the class itself.
  - Explanation: The `protected` access modifier allows access to methods and fields within the same package and by subclasses in other packages.
- [ ] It prevents methods and fields from being inherited.
  - Explanation: The `protected` access modifier allows access to methods and fields within the same package and by subclasses in other packages.

45. What is method shadowing in Java?

- [ ] Method shadowing is the same as method hiding.
- Explanation: Method shadowing occurs when a subclass defines a method with the same name as a method in its superclass without overriding it.
- [ ] It is a technique to protect a method from being overridden.
- Explanation: Method shadowing occurs when a subclass defines a method with the same name as a method in its superclass without overriding it.
- [ ] Method shadowing is not a concept in Java.
- Explanation: Method shadowing occurs when a subclass defines a method with the same name as a method in its superclass without overriding it.
- [x] It is a situation where a subclass defines a method with the same name as a method in its superclass, without overriding it.

46. Consider the following code snippet:

```java
class Parent {
    int x = 5;
}

class Child extends Parent {
    int x = 10;
    void display() {
        System.out.println(super.x);
    }
}
```

What will be the output of `new Child().display()`?

- [ ] 5
- Explanation: The `super.x` within the `display()` method references the `x` variable in the `Parent` class, which is 5.

- [ ] 10
- Explanation: The `super.x` within the `display()` method references the `x` variable in the `Parent` class, which is 5.

- [x] 5

47. In Java, can a subclass access the private members (fields or methods) of its superclass?

- [ ] Yes, without any restrictions.
- Explanation: Private members of a class are not accessible to its subclasses.
- [ ] Yes, but only through the use of the `protected` keyword.
- Explanation: Private members of a class are not accessible to its subclasses.
- [ ] No, private members are inaccessible to subclasses.
- Explanation: Private members of a class are not accessible to its subclasses.
- [x] No, private members are not accessible to subclasses.

48. What is the purpose of the `@Override` annotation in Java?

- [ ] It specifies that a method is static.
  - Explanation: The `@Override` annotation indicates that a method is intended to override a method in a superclass.
- [ ] It creates a new method in the class.
  - Explanation: The `@Override` annotation indicates that a method is intended to override a method in a superclass.
- [x] It indicates that a method is intended to override a method in a superclass.
- [ ] It enforces a method's visibility.
  - Explanation: The `@Override` annotation indicates that a method is intended to override a method in a superclass.

49. In Java, can you override a static method in a subclass?

- [ ] Yes
- Explanation: Static methods cannot be overridden in Java. They are associated with the class itself, not instances.
- [x] No

50. What is the primary role of the `super()` call in a constructor in Java?

- [ ] It creates a new instance of the subclass.
- Explanation: The `super()` call in a constructor is used to call a constructor in the superclass to perform initialization tasks.
- [x] It calls a constructor in the superclass to perform initialization tasks.
- [ ] It prevents the superclass from being extended by other classes.
- Explanation: The `super()` call in a constructor is used to call a constructor in the superclass to perform initialization tasks.
- [ ] It is required for method overriding.
- Explanation: The `super()` call in a constructor is used to call a constructor in the superclass to perform initialization tasks.
