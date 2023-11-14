#  What is a Package

## Concept

`Package` is a way to **organize and group** related classes, interfaces, and other components together. Packages provide a mechanism for managing the namespace and access control of Java classes and help **avoid naming conflicts** between classes with the same name.




## Example

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

