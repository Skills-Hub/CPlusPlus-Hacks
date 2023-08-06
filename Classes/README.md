# Introduction :wave:

Welcome, coders! Today, we're going to talk about one of the essential building blocks of object-oriented programming in C++ - the Classes. Classes are the heart of C++, allowing us to implement object-oriented programming concepts like abstraction, encapsulation, inheritance, and polymorphism. So buckle up and get ready to learn about Classes in C++. 

# Body :open_book:

## What is a Class? :thinking:

In C++, a class is a user-defined data type, which holds its own data members and member functions, which can be accessed and used by creating an instance of that class. A class is like a blueprint for an object. 

```cpp
class MyClass {       // The class
  public:             // Access specifier
    int myNum;        // Attribute (int variable)
    string myString;  // Attribute (string variable)
};
```

In this example, we defined a class called `MyClass`. Now, we can use this to create objects.

## Creating Objects :factory:

Once a class has been defined, we can use it to create objects. An object is an instance of a class, and it can be defined as follows:

```cpp
MyClass myObj;  // Create an object of MyClass
```

Now, `myObj` is an object of `MyClass`, and we can access the attributes of `MyClass` using the dot operator `.`.

```cpp
myObj.myNum = 15;    // Set the value of the attribute myNum in myObj
myObj.myString = "Hello"; // Set the value of the attribute myString in myObj
```

## Member Functions & Encapsulation :lock_with_ink_pen:

Member functions are functions that belong to the class and can manipulate the class's attributes. Encapsulation, another OOP principle, means that the class's sensitive data is hidden from users. 

```cpp
class MyClass {
  public:
    void myMethod() {   // Method/function defined inside the class
      cout << "Hello World!";
    }
};

int main() {
  MyClass myObj;     // Create an object of MyClass
  myObj.myMethod();  // Call the method
  return 0;
}
```

In the code above, we encapsulated a method `myMethod()` inside `MyClass`, and it can be accessed using the object of `MyClass`.

# Conclusion :checkered_flag:

Classes in C++ are a powerful tool that allows us to implement the principles of Object-Oriented Programming. They provide us with the structure and methods to create and manipulate our own data types, opening up countless possibilities. It's a wide topic, and there's still so much to learn about classes, such as inheritance, polymorphism, etc. So, keep learning and happy coding! :nerd_face:

# 📣 Share your feedback

If you have any questions, comments, or feedback on this blog post, I'd love to hear from you! You can reach me on LinkedIn [Rayan Ch.](https://www.linkedin.com/in/rayan-ch-b787ab224/) or by email at [mo@gglink.uk](mailto:mo@gglink.uk).

### Thanks for reading! 😊
