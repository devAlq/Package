# Package / oop Project 01 


**Objectives**

This project aims to facilitate and organizing **classes into packages**, developing distinct classes for entities and system functionality, and incorporating methods to **execute operations** on student objects. Additionally, it offers a chance to enhance skills in **error handling** and **fundamental calculations**.

**Concepts**

`Package` is a way to **organize and group** related classes, interfaces, and other components together. Packages provide a mechanism for managing the namespace and access control of Java classes and help **avoid naming conflicts** between classes with the same name.


```java
package com.example.myapp;

import com.example.utilities.StringUtils;

public class Main {
    public static void main(String[] args) {
        String text = "Hello, World!";
        String reversedText = StringUtils.reverse(text);
        System.out.println(reversedText);
    }
}
```
package called com.example.myapp. Within this package, we have a class named Main. The Main class imports a utility class StringUtils from another package, com.example.utilities, to perform a string reversal operation.

**Problem**

1. Create a package called “practice.studentmanagement" to organize your classes.
2. Create a class called "Student" within the package, with attributes like name, id number, age, and grade. Include 
   appropriate getters and setters.
3. Create a class called "StudentManagementSystem" within the package, which serves as the main entry point for the system.
4. Implement methods in the "StudentManagementSystem" class to add a new student, remove a student, and search for a student by id number.
5. Include error handling to handle cases such as duplicate id numbers or non-existent students.
6. Implement a method to calculate the average grade of all the students in the system.
7. Create a separate "Main" class outside the package to demonstrate and test the functionality of the student management system.


**Implementation**


```Java

public class Main {
    public static void main(String[] args) {
        StudentManagementSystem sms = new StudentManagementSystem();
        /* Adding students */
        Student student1 = new Student("Khaled", 1, 20, 85.5);
        sms.addStudent(student1);

        Student student2 = new Student("Rema", 2, 21, 92.3);
        sms.addStudent(student2);

        Student student3 = new Student("Noura", 3, 19, 78.9);
        sms.addStudent(student3);

```

