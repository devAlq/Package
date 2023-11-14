#  What is a Package

`Package` is a **Set of classes and interfaces grouped together.**


## Concept

`Package` is a way to **organize and group** related classes, interfaces, and other components together. Packages provide a mechanism for managing the namespace and access control of Java classes and help **avoid naming conflicts** between classes with the same name.

`Packages` are divided into **two categories**:

 - `Built-in Packages` (packages from the Java API).
   * The **Java API** is a library of prewritten classes, that are free to use, included in the Java Development Environment.
   * To use a **class or a package from the library**, you need to use the `import`
 - `User-defined Packages` (create your own packages).
   * To create your own package, you need to understand that Java uses a file system directory to store them. **Just like folders on your computer**.

## Example
* Built-in Packages

```java

import java.util.Scanner;

class MyClass {
  public static void main(String[] args) {
    Scanner myObj = new Scanner(System.in);
    System.out.println("Enter username");
  }
}
```

* User-defined Packages

```java
package myproject;

class MyPackageClass {
  public static void main(String[] args) {
    System.out.println("This is my package!");
  }
}
```

## Resource 
For more information you can find resource Package
-  [What is a package](https://www.youtube.com/watch?v=Bua6LQO2vQ8)
