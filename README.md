# Object-Oriented Programming Using C++

## 📌 About This Repository

This repository contains my learning and implementation of **Object-Oriented Programming (OOP) using C++**.

The repository focuses on understanding how object-oriented principles are used to design structured, reusable, secure, and maintainable programs.

Each topic is documented with its **definition, purpose, working principle, important features, and real-world applications** to build both theoretical and practical understanding of C++ OOP.

---

## 🎓 Student Details

| **Field** | **Details** |
|:---|:---|
| **Name** | Nandana S Korigoudar |
| **Branch** | Electronics and Communication Engineering |
| **Semester** | VII |
| **University** | KLE Technological University |

---

## 🎯 Objectives

The main objectives of this repository are:

- To understand the fundamentals of Object-Oriented Programming.
- To learn how C++ supports object-oriented software development.
- To understand how classes and objects represent real-world entities.
- To learn how constructors and destructors manage objects.
- To understand encapsulation and data hiding.
- To understand different types of inheritance and code reusability.
- To learn the purpose of friend functions and static members.
- To connect theoretical OOP concepts with real-world software applications.

---

## 📚 Features of OOPs

The main features of Object-Oriented Programming (OOP) are:

| **Feature** | **Description** |
|:---|:---|
| **Class** | A blueprint/template used to create objects. |
| **Object** | An instance of a class that represents a real-world entity. |
| **Encapsulation** | Wrapping data and functions together into a single unit (class). |
| **Abstraction** | Hiding unnecessary implementation details and showing only essential information. |
| **Inheritance** | Acquiring properties and functions of an existing class into a new class. |
| **Polymorphism** | One name having many forms, such as function overloading and overriding. |
| **Data Hiding** | Restricting direct access to data using access specifiers like private. |

---

# 📖 OOP Concepts in C++

## 1. Classes and Objects

### 🔹 What is a Class?

A **class** is a user-defined data type that acts as a blueprint for creating objects.

A class combines:

- Data members
- Member functions

The data members represent the properties of an entity, while member functions represent the operations that can be performed on that entity.

### 🔹 Why is a Class Used?

Classes are used to organize related data and functions into a single unit.

They help in:

- Organizing large programs.
- Representing real-world entities.
- Improving code reusability.
- Supporting data hiding.
- Building modular software.

### 🔹 What is an Object?

An **object** is an instance of a class.

When an object is created, memory is allocated for its data members.

For example, a `Student` class can represent the general structure of a student, while individual students can be represented as objects.

### 🌍 Real-World Applications

Classes and objects are widely used in:

- Banking systems.
- Student management systems.
- Hospital management systems.
- E-commerce applications.
- Vehicle management systems.
- Employee management systems.
- Games and simulations.

---

## 2. Constructors

### 🔹 What is a Constructor?

A constructor is a special member function of a class that is automatically called when an object is created.

Its primary purpose is to **initialize an object**.

### 🔹 Characteristics

- Constructor has the same name as the class.
- It does not have a return type.
- It is automatically called when an object is created.
- A class can have multiple constructors.
- Constructors can be overloaded.

### 🔹 Types of Constructors

Common types include:

1. **Default Constructor**
2. **Parameterized Constructor**
3. **Copy Constructor**

### 🔹 Why are Constructors Used?

Constructors ensure that an object starts with a valid or meaningful initial state.

For example, when creating a bank account object, the constructor can initialize:

- Account holder name.
- Account number.
- Initial balance.

### 🌍 Real-World Applications

Constructors are commonly used when:

- Creating user accounts.
- Initializing database objects.
- Creating employee records.
- Initializing configuration objects.
- Creating objects representing hardware or system components.

---

## 3. Destructors

### 🔹 What is a Destructor?

A destructor is a special member function that is automatically called when an object is destroyed.

Its purpose is to perform **cleanup operations** before an object is removed from memory.

### 🔹 Characteristics

- Destructor has the same name as the class preceded by `~`.
- It does not return a value.
- It does not take parameters.
- A class can have only one destructor.
- It is automatically invoked when the object goes out of scope.

### 🔹 Why is a Destructor Used?

Destructors are useful for releasing resources acquired by an object.

These resources can include:

- Dynamically allocated memory.
- Files.
- Database connections.
- Network resources.
- Other system resources.

### 🌍 Real-World Applications

Destructors are useful in applications where objects manage external resources, such as:

- File management systems.
- Database applications.
- Network applications.
- Memory-intensive applications.
- Embedded and system-level software.

---

## 4. Encapsulation

### 🔹 What is Encapsulation?

**Encapsulation** is the process of combining data and the functions that operate on that data into a single unit.

In C++, a class provides the mechanism for implementing encapsulation.

### 🔹 Why is Encapsulation Important?

Encapsulation helps protect an object's internal data from direct and unwanted access.

Instead of allowing external code to directly modify data, controlled functions can be provided to access or modify it.

### 🔹 Advantages

- Data protection.
- Better program organization.
- Controlled access.
- Easier maintenance.
- Reduced complexity.
- Improved reliability.

### 🌍 Real-World Example

Consider a bank account.

The account balance should not normally be modified directly by any part of the program.

Instead, operations such as:

- Deposit.
- Withdraw.
- Check Balance.

can control how the balance is accessed and modified.

### 🔹 Applications

Encapsulation is widely used in:

- Banking software.
- User authentication systems.
- Healthcare systems.
- E-commerce systems.
- Enterprise applications.
- Security-sensitive software.

---

## 5. Data Hiding

### 🔹 What is Data Hiding?

Data hiding is the practice of restricting direct access to the internal data of an object.

It is commonly implemented using access specifiers such as `private`.

### 🔹 Purpose

Data hiding prevents other parts of the program from directly changing sensitive internal information.

For example, an employee's salary or a bank account balance can be kept private.

### 🔹 Benefits

- Protects sensitive information.
- Prevents accidental modification.
- Provides controlled access.
- Improves software security.
- Reduces dependencies between components.

### 🔹 Difference Between Encapsulation and Data Hiding

**Encapsulation** focuses on combining data and methods into one unit.

**Data hiding** focuses on restricting direct access to internal data.

Data hiding is therefore an important part of implementing encapsulation effectively.

---

## 6. Access Specifiers

C++ provides three major access specifiers:

### 🔹 1. Public

Members declared as `public` can be accessed from outside the class.

They are generally used for operations that should be available to users of the class.

### 🔹 2. Private

Members declared as `private` can only be accessed directly from within the class.

They are commonly used to protect internal data.

### 🔹 3. Protected

Members declared as `protected` can be accessed within the class and by derived classes.

They are particularly useful when implementing inheritance.

### 🔹 Importance

Access specifiers provide control over how different parts of a program interact with an object.

They help implement:

- Encapsulation.
- Data hiding.
- Controlled access.
- Secure class design.

---

## 7. Friend Functions

### 🔹 What is a Friend Function?

A **friend function** is a function that is not a member of a class but is given permission to access the class's private and protected members.

It is declared inside the class using the `friend` keyword.

### 🔹 Why is it Used?

Normally, private members can only be accessed by member functions of the class.

A friend function provides controlled access when an external function needs to work closely with the internal data of a class.

### 🔹 Important Characteristics

- It is not a member of the class.
- It can access private and protected members.
- It is declared using the `friend` keyword.
- It is called like a normal function.
- Friendship is explicitly granted by the class.

### 🔹 Applications

Friend functions can be useful when:

- Two classes need to cooperate closely.
- An external function needs access to private data.
- Operator overloading requires access to private members.
- Data needs to be shared between related classes.

### ⚠️ Important Consideration

Friend functions should be used carefully because excessive use can reduce data hiding and increase dependency between components.

---

## 8. Static Members

### 🔹 What is a Static Member?

A static member belongs to the **class rather than to individual objects**.

Normally, every object has its own copy of non-static data members.

A static data member, however, is shared among all objects of that class.

### 🔹 Why is it Used?

Static members are useful when some information needs to be common to every object.

For example, if we want to keep track of how many objects of a class have been created, a static variable can maintain that count.

### 🔹 Static Data Member

A static data member has only one shared copy for the entire class.

### 🔹 Static Member Function

A static member function belongs to the class and can be called without creating an object.

It can directly access static members.

### 🔹 Applications

Static members are commonly used for:

- Counting objects.
- Maintaining shared information.
- Configuration values.
- Utility functions.
- Common counters.
- Resource management.

### 🌍 Real-World Example

In a university management system, a static member could maintain the total number of student objects created.

Instead of each student having a separate count, one shared count can represent the total.

---

## 9. Inheritance

### 🔹 What is Inheritance?

**Inheritance** is an OOP mechanism that allows a new class to acquire properties and behavior from an existing class.

The existing class is called the **base class**, while the new class is called the **derived class**.

### 🔹 Why is Inheritance Used?

The main purpose of inheritance is **code reusability**.

Instead of writing the same functionality repeatedly, common functionality can be placed in a base class and reused by derived classes.

### 🔹 Advantages

- Code reusability.
- Reduced code duplication.
- Easier maintenance.
- Better organization.
- Supports hierarchical relationships.
- Provides a foundation for polymorphism.

### 🌍 Real-World Example

Consider a transportation system.

A general `Vehicle` class may contain common properties such as:

- Speed.
- Number of wheels.
- Start operation.

Classes such as:

- Car.
- Bike.
- Bus.

can inherit common characteristics from the `Vehicle` class while adding their own specific functionality.

---

## 10. Types of Inheritance

C++ supports different forms of inheritance.

### 🔹 1. Single Inheritance

One derived class inherits from one base class.

**Structure:**

```text
Base Class
     ↓
Derived Class
```

**Application:**

Useful when a new class is a specialized version of an existing class.

**Example:**

```text
Vehicle → Car
```

---

### 🔹 2. Multilevel Inheritance

A class is derived from another derived class, creating multiple levels.

**Structure:**

```text
Base Class
     ↓
Derived Class
     ↓
Further Derived Class
```

**Application:**

Useful when functionality needs to be extended gradually through multiple levels.

**Example:**

```text
Person → Employee → Manager
```

---

### 🔹 3. Multiple Inheritance

A derived class inherits from more than one base class.

**Structure:**

```text
Base Class 1 ──┐
               ↓
          Derived Class
               ↑
Base Class 2 ──┘
```

**Application:**

Useful when a class needs functionality from multiple independent classes.

For example, a system component may require characteristics from two different functional categories.

---

### 🔹 4. Hierarchical Inheritance

Multiple derived classes inherit from the same base class.

**Structure:**

```text
          Base Class
          /        \
         ↓          ↓
   Derived 1    Derived 2
```

**Application:**

Useful when several classes share common functionality.

**Example:**

```text
        Employee
        /       \
   Manager     Engineer
```

---

### 🔹 5. Hybrid Inheritance

Hybrid inheritance is a combination of two or more types of inheritance.

It can be used to represent complex relationships between classes.

**Application:**

Hybrid inheritance can be useful in large systems where different types of relationships exist between classes.

However, complex inheritance structures should be designed carefully because they can make software harder to understand and maintain.

---

## 11. Polymorphism

### 🔹 What is Polymorphism?

**Polymorphism** is an Object-Oriented Programming concept that allows a single interface or function name to represent different behaviors.

The term polymorphism means **"many forms."**

In C++, polymorphism allows the same function or operation to behave differently depending on the context in which it is used.

### 🔹 Why is Polymorphism Used?

Polymorphism is used to provide flexibility and extensibility in software development.

It helps in:

- Using a common interface for different operations.
- Reducing code duplication.
- Improving code reusability.
- Supporting flexible program design.
- Making software easier to extend and maintain.

### 🔹 Types of Polymorphism

C++ supports two major types of polymorphism:

#### 1. Compile-Time Polymorphism

Compile-time polymorphism is resolved by the compiler during compilation.

It is commonly implemented using:

- **Function Overloading:** Multiple functions have the same name but different parameter lists.
- **Operator Overloading:** Operators are given specialized behavior for user-defined data types.

#### 2. Runtime Polymorphism

Runtime polymorphism is resolved during program execution.

It is commonly implemented using:

- **Function Overriding:** A derived class provides its own implementation of a function inherited from the base class.
- **Virtual Functions:** Virtual functions enable runtime method dispatch through base-class pointers or references.

### 🔹 Important Characteristics

- Supports multiple forms of behavior through a common interface.
- Function overloading is an example of compile-time polymorphism.
- Function overriding is an example of runtime polymorphism.
- Virtual functions enable dynamic binding.
- Improves flexibility and extensibility.

### 🔹 Advantages

- Code reusability.
- Improved flexibility.
- Reduced code duplication.
- Easier maintenance.
- Supports extensible software design.
- Simplifies interaction with different object types.

### 🌍 Real-World Example

Consider a payment processing system.

Different payment methods, such as:

- Credit Card.
- UPI.
- Net Banking.

can provide their own implementation of a common payment operation.

The same payment interface can be used to process different payment types without changing the calling code.

### 🔹 Applications

Polymorphism is widely used in:

- Payment processing systems.
- Graphics and animation software.
- GUI applications.
- Embedded software.
- Device driver development.
- Simulation systems.
- Extensible software frameworks.

---

## 12. Exception Handling

### 🔹 What is Exception Handling?

**Exception handling** is a mechanism in C++ used to detect and manage runtime errors or exceptional conditions without abruptly terminating the program.

It allows a program to respond to unexpected situations and continue execution when possible.

### 🔹 Why is Exception Handling Used?

Exception handling helps improve the reliability and robustness of software.

It is used to:

- Handle runtime errors.
- Prevent unexpected program termination.
- Separate error-handling logic from normal program logic.
- Provide meaningful error messages.
- Maintain program stability.

### 🔹 Exception Handling Keywords

C++ provides three main keywords for exception handling:

#### 1. try

The `try` block contains code that may generate an exception.

#### 2. throw

The `throw` keyword is used to signal an exception when an exceptional condition occurs.

#### 3. catch

The `catch` block handles an exception thrown from the corresponding `try` block.

### 🔹 Working Principle

Exception handling follows this sequence:

1. The program executes statements inside the `try` block.
2. If an exceptional condition occurs, an exception is thrown using `throw`.
3. The program searches for a matching `catch` block.
4. The matching `catch` block handles the exception.
5. Execution continues after the exception-handling structure.

If no matching handler is found, the program may terminate.

### 🔹 Types of Exceptions

#### 1. Standard Exceptions

C++ provides standard exception classes through its standard library.

Examples include:

- `std::runtime_error`
- `std::logic_error`
- `std::out_of_range`
- `std::invalid_argument`

#### 2. User-Defined Exceptions

Programmers can define and throw their own exceptions to handle application-specific error conditions.

For example, a banking application may define an exception for insufficient account balance.

### 🔹 Advantages

- Improves program reliability.
- Provides structured error handling.
- Separates error handling from normal logic.
- Helps prevent unexpected termination.
- Makes debugging and maintenance easier.
- Supports graceful recovery from errors.

### 🌍 Real-World Example

Consider a banking system.

When a user attempts to withdraw more money than the available balance, the program can throw an exception.

The exception handler can display an appropriate error message and prevent the invalid transaction from proceeding.

### 🔹 Applications

Exception handling is commonly used in:

- Banking and financial applications.
- File handling systems.
- Database applications.
- Network communication.
- Embedded software.
- Input validation.
- Resource management.

---

# ⭐ Conclusion

Object-Oriented Programming provides a structured approach to developing software by representing real-world entities as objects and defining relationships between them.

The concepts covered in this repository—including classes, objects, encapsulation, inheritance, polymorphism, and exception handling—form the foundation for writing modular, reusable, maintainable, and reliable C++ programs.

---

## 👩‍💻 Author

**Shivani Ishwar Metri**

Electronics and Communication Engineering (ECE)

KLE Technological University
