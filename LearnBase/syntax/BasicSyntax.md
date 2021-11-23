## BasicSyntax



Basic Syntax
When writing Java programs, you should pay attention to the following points:

Case sensitive: Java is case sensitive, which means that the identifiers hello and hello are different.
Class name: for all classes, the first letter of the class name should be capitalized. If the class name consists of several words, the first letter of each word should be capitalized, such as myfirstjavaclass.

Method name: all method names should start with lowercase letters. If the method name contains several words, each subsequent word is capitalized.

Source file name: the source file name must be the same as the class name. When saving a file, you should use the class name as the file name (remember that Java is case sensitive), and the suffix of the file name is. Java. (if the file name and class name are different, it will lead to compilation errors).

Main method entry: all Java programs are executed by the `public static void main (String [] args) `method.



Java identifier
All components of Java need names. Class names, variable names, and method names are all called identifiers.

There are several points to note about Java identifiers:
All identifiers should start with letters (A-Z or A-Z), dollar sign ($), or underscore ()
The first character can be followed by any combination of letters (A-Z or A-Z), dollar sign ($), underscore () or numbers
Keywords cannot be used as identifiers
Identifiers are case sensitive
Examples of legal identifiers: age, $salary_ value、__ 1_ value
Examples of illegal identifiers: 123abc, - salary

Java modifier
Like other languages, Java can use modifiers to modify methods and properties in classes. There are two main types of modifiers:

Access control modifiers: default, public, protected, private
Non access control modifiers: final, abstract, static, synchronized

Java variables
There are mainly the following types of variables in Java
local variable
Class variable (static variable)
Member variable (non static variable)