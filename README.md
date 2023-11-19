# Package 


**Objectives**

In this project we will learn how to organize **classes into package**. And develop distinct classes for entities and system functionalities.

**Concepts**

| Concept   |      Resources      |
|----------|:-------------:|
|Concept of a package |  [Concept of a package ](https://github.com/nourabyte/high-level-language/blob/main/resources/what-is-a-package.md) |
|Tutorial about Package      |    [What is a package](https://www.youtube.com/watch?v=Bua6LQO2vQ8)  |


**Problem**

Create your own structure to organize the project using `package` concept.


**Implementation**

1. Create a package to organize your classes.
2. Create `Student` class within the package, with attributes name, id number, age, and grade.
3. Create "StudentManagementSystem" class, which serves as the main entry point for the system.
4. Implement methods to add and remove a student.
6. Implement a method to calculate the average grade of all the students in the system.


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
         }
}
```

