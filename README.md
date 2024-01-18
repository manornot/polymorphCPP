
# C++ Advanced Concepts: Operator Overloading and Polymorphism

Welcome to our C++ advanced concepts training module! This project is designed to enhance your understanding of two key Object-Oriented Programming (OOP) concepts: operator overloading and polymorphism. Through a series of tasks, you'll apply these concepts in real-world scenarios, solidifying your knowledge and skills in C++ programming.

## Objectives

- Understand and implement operator overloading.
- Grasp the concept of polymorphism and its application in C++.
- Develop practical C++ programs implementing these concepts.

## Prerequisites

Before starting, ensure you have:
- Basic knowledge of C++ syntax and OOP principles.
- A C++ development environment set up on your machine.
- Familiarity with using GitHub for cloning repositories and pushing updates.

## Tasks

### Task 1: Operator Overloading

**Objective**: Create a `ComplexNumber` class and overload arithmetic operators.

1. **Setup**: Create a `ComplexNumber` class with real and imaginary parts.
2. **Overload Operators**: Implement overloading for `+`, `-`, `*`, `/`.
3. **Testing**: Write a main function to demonstrate the operations between complex numbers.

### Task 2: Understanding Polymorphism

**Objective**: Develop a simple class hierarchy demonstrating polymorphism.

1. **Base Class**: Create an abstract base class `Shape` with a virtual function `draw()`.
2. **Derived Classes**: Implement derived classes like `Circle`, `Rectangle`, `Triangle`, each overriding `draw()`.
3. **Demonstration**: In your main function, create a vector of `Shape*` and populate it with instances of derived classes, calling `draw()` on each.

### Task 3: Combining Concepts

**Objective**: Use both operator overloading and polymorphism in a unified task.

1. **Enhance `Shape`**: Add coordinates to the `Shape` class and overload the `+` operator to move the shape's position.
2. **Interaction**: Implement a function to `resize` shapes, differently in each derived class.
3. **Showcase**: In the main function, demonstrate moving and resizing different shapes.

## Submission Guidelines

- Fork this repository to your GitHub account.
- Complete each task in a separate branch and merge them into your master branch upon completion.
- Ensure your code is well-commented and follows best practices.
- Push your final code to your forked repository.
- Submit a pull request with a brief description of your implementations.

## Resources

- [C++ Documentation](https://en.cppreference.com/w/)
- [Understanding Operator Overloading](https://www.learncpp.com/cpp-tutorial/operator-overloading/)
- [Polymorphism in C++](https://www.tutorialspoint.com/cplusplus/cpp_polymorphism.htm)

## Support

For any questions or issues, please open an issue on this repository, and we'll respond as soon as possible.

Happy Coding!

---

This README provides clear instructions and structured tasks that guide learners through practical implementations of operator overloading and polymorphism, offering a hands-on approach to understanding these advanced C++ concepts.