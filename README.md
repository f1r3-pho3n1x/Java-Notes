# Java Notes <!-- omit from toc -->
- [1 Basic Syntax of Java Program](#1-basic-syntax-of-java-program)
- [2 How Compilation works](#2-how-compilation-works)
- [3 How Runtime works](#3-how-runtime-works)
- [3 Java Variables and its Types, Datatypes of variables,  and Operators](#3-java-variables-and-its-types-datatypes-of-variables--and-operators)
  - [3.1 - Local Variable](#31---local-variable)
  - [3.2 - Instance Variable](#32---instance-variable)
  - [3.3 - Static Variable](#33---static-variable)



# 1 Basic Syntax of Java Program
```java
public class helloworld {
    
    public static void main(String[] args) {
        System.out.println("Hello World!!!");
    }
}
```

# 2 How Compilation works
- At the compile time, the Java file is compiled by java compiler and converts the java code into bytecode.
- At compilation time there is not interaction with OS, its just btw the compiler and your code.
```
"Java Code -> compiler -> Bytecode"
```

# 3 How Runtime works
```
"Class file -> Class Loader -> Bytecode Verified -> Interpreter -> Runtime -> Hardware."
```
- `ClassLoader:` It is a subsystem of JVM that is used to load class file.
- `Bytecode Verifier:` Check the code fragments for illegal code that can violate access rights to objects.
- `Interpreter:` Read the bytecode stream then execute the instructions.

# 3 Java Variables and its Types, Datatypes of variables,  and Operators
## 3.1 - Local Variable
## 3.2 - Instance Variable
## 3.3 - Static Variable