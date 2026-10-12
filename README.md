1. Class
A class is a blueprint/template for creating objects.
class Student {
    String name;
    int age;
}

2. Object
An object is an instance of a class.
Student s = new Student();
s.name = "Saurabh";

3. Encapsulation
Wrapping data and methods into one class and controlling access using access modifiers.
class Account {
    private double balance;

    public double getBalance() {
        return balance;
    }
}

Benefit: Data hiding and security.
4. Inheritance
One class acquires properties and methods of another class.
class Animal {
    void eat() {
        System.out.println("Eating");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Barking");
    }
}

Keyword: extends
5. Polymorphism
One name, multiple forms.
Two types:
- Compile-time: Method overloading
- Runtime: Method overriding
// Overloading
void add(int a, int b) {}
void add(int a, int b, int c) {}

// Overriding
class Animal {
    void sound() {}
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Bark");
    }
}

6. Abstraction
Hiding implementation details and showing only essential functionality.
Using:
- abstract class
- interface
interface Payment {
    void pay();
}

7. Four Main Pillars
Pillar	Meaning
Encapsulation	Data hiding
Inheritance	Code reusability
Polymorphism	Many forms
Abstraction	Hide implementation


8. Constructor
A special method used to initialize an object.
class Student {
    Student() {
        System.out.println("Object created");
    }
}

9. Access Modifiers
- private → same class only
- default → same package
- protected → same package + subclasses
- public → everywhere
10. this vs super
- this → refers to the current object
- super → refers to the parent class
this.name = name;
super.display();

Interview One-Line Answer
OOPs is a programming paradigm that organizes software around objects and classes. Its four main principles are encapsulation, inheritance, polymorphism, and abstraction.
