# Enum
 - Special Data Types that enables for a variable to be a set of predefined constants.


At the early stages of the programming languages, it is common to use a set of constants to represent a set of predefined values. 

For example, 
 - The days of the week, 
 - The months of the year, 
 - The colors of the rainbow, etc. 

### History of Enum:

------------

Java Programming languages is based on the programming languages in late 90s (1967 onwards), such as Pascal, C, Smalltalk, C++, Ada, Objective-C, Perl, etc...

The `enum` keyword was not available in the early versions of Java (Java 1.0 to Java 1.4).

In those days, the only way to represent a set of predefined values was to use a set of constants.

```java
public class Color {
    public static final string Red = "Red";
    public static final string Green = "Green";
    public static final string Blue = "Blue";
}
```

By the time, the `enum` keyword was introduced in Java 5.0 (also known as Java 1.5 in 2004).
And it was a significant improvement over the traditional way of representing a set of predefined values using a set of constants.

The `enum` keyword is used to define an `enumeration` which is a user-defined data type that consists of integral constants.
To define an enumeration, the enum keyword is followed by the enumeration name (which is optional) and a set of curly braces that contain the enumeration constants. 

For example,

The following code defines an enumeration called `Color` that contains the constants `Red`, `Green`, and `Blue`:

```java
enum Color {
    Red, Green, Blue
}
```

[//]: # (To be continued...)