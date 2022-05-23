## Java Basic Assignment 1
1. What is a programming language? What is Java and what is Java used for?
- Java is a general purpose programming language based on class and object. The language is designed in a way that it can run on any computer architecture. 
Jave is used on enormous amount of applications and websites. These apps and websites are not going to work unless java installed. From laptops to data centers, game consoles to super computers - Java is the go to language. Jave is used to write application and run it virtually on any platform.

2. Which version of Java you are working with? How can you find out the version of Java you are using?
- I am working on Java 8. Using it in a windows terminal and this command is used to find the version - java --version.

3. What is IDE? Which IDE you are working with? 
- IDE stands for Integrated Development Environment. This enables programmers to consolidate different aspects of writing a computer program. I am using InttelliJ IDEA community edition as an IDE.

4. What is source code? What is file extension for Java source code?
- Source code is text listing of commands to be compiled or assembled into a executable computer program. The file extension for Java source code is .java

5. What is the second stage of Java life cycle?
- Compile the .java file

6. Which compiler is used for compiling Java file? 
- Javac is the comppiler for java files.

7. What files are the input and output of the compilation stage?
- .java is at the input and .class is the output of the compilation stage.

8. Which command is used to call Java compiler in terminal or CMD?
- javac

9. What is the third stage of Java Life Cycle? 
- Interpretation is the third stage of Java lifecycle.

10. At which stage class loader is used and what function does it perform?
- Class loader used at running stage of java application. This load and read .class file and save bytecode in JVM.

11. Which unit is responsible for translating bytecodes into machine code?
- JVM is responsible for translating bytecode in machine code.

12. What is last stage of Java Life Cycle?
- Execution is the last stage of Java lifecycle.

13. Which command is used to run Java program in terminal or CMD?
- java MyApplication (Application naming case senstive) 

14. At what stage bytecode verifier is used? 
- Before execution to ensure everything is perfect.

15. What is JDK? Briefly explain the components of JDK.
- JDK stands for Java Development Kit. JDK Consist of JRE (Java runtime environment that is responsible for executing programs), Intepreter/loader for class loading,
Compiler for compiling codes and Jar for acrchiving as well as a documentation generator called Javadoc.

16. Name main components present in JVM and write function of each component.
- Main components of JVM is class loader (subsystem used to load files and perform major functions), method area for storing class structures such as meta data etc, Heap for sorting arrays and objects, Java langyage stacks to store local variable, PC registers to store the address of the java vitual machine instruction that is currently executing. Native method stacks to hold instruction of native code depends on native library. Execution engine to test hardware, software and complete systems, native method interfacce for programming framework and native method libraries for a collection of native labiraries (C, C++)

17. What is JRE? In which stage of Java life cycle JRE is used?
- JRE is Java Runtime Environment. Its used in exceution stage.

18. What is the syntax? Make a list of rules(you learned in a class) you should always follow while creating your Java application.
- Syntax is the basic of all language and rulles and commands that require to write program that is understandable by compiler and computer.
The rules for different identifiers include 
-- Packages > All lowercase letter
-- Classes > should be noun and in mixed cases first letter should be capitalized.
-- Interfaces > Name should be capitalized.
-- Methods > Should be verbs and in mixed cases first letter should be lowercase and for inernal word, it should be capitalized
-- Variables > Mixed case with lowecase letter and internal words start with capitalized. Variable names should be also meaningful.
-- Constants > Should be all upper case.

19. How should we name our Java application? 
- Applicaation should be always named same as public class name and extension for saving the file before compilation should be .java

21. Write a structure of a simple Java application. 
-  public class HelloWorld
-  -{
-  - public static void main(String[] args)
-  --{
-  ---System.out.println("Hello, World!");
-  --}
-  -}

23. What is the importance of comments in the program? Mention different ways in which we can write comments in a program. 
- Proper use of comments can make code maintenance easier and help to find bug faster. It also help other people to translate functions in a collaborative environment.
- The way to write comment includ following methods
- - Single line // This is a comment. This can be use above or end of the command line/code
- - Multiline comments start with /* and end with */

25. Write a simple Java program to print the “Hello World” message. Keeping in mind stages of Java Life Cycle draw a flow chart to show journey of your first program
- nano HelloWorld.java
- - public class HelloWorld
- -{
- - public static void main (Strings[] args)
- --{
- ---System.out.println("Hello, World!");
- --}
- }
- CTRL+S and CTRL+X
- javac HelloWorld.java
- java HelloWorld

27. What is file extension for Java executable code? At which stage of Java Life Cycle we get executable code?  
- The extension is either .class or .jar. It happens in compilation stage.

29. When does compile time starts? 
- Once the coding or modification of coding complete and need to push next stage for execution.

31. Compile time ends with generation of which file? 
-.class file

33. Can you run the program without compilation? Try running your first program without compilation and share result.
- No, a program cant start with compilation because the code is not yet ready for computer to understand
 
35. When does runtime start? 
- Runtime starts with execution of the program with the command java to run the program.

37. During which phase .class file is loaded into memory runtime or compile time? Who loads .class file into memory?
- The load happens during execution stage. The class loader loads the .class file into memory.

