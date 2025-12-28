# JVM_Basics.md
Answering the questions

What is JDK, JRE, JVM

JDK- The JDK( Java Development kit)is a complete package designed for developers to write, compile, and run java application.
JRE- The JRE( Java Runtime Environment) is the actual implementation of the JVM and provide everything necessary to run a java application.
JVM- The JVM( Java Virtual Machine) is an abstrat machine that provides the runtime environment in which java bytecode can be executed.

What is bytecode.

Bytecode is an intermediate version of your Java code that acts as a bridge between the high-level language you write and the binary "machine code" the computer actually runs. 

What does "write once run anywhere" means.

It means a programmer can develop Java code on one system and can expect it to run on any other Java-enabled system without any adjustment. 
It means if you write an code  in (window OS) it will run in any of the OS like (Mac or linux) without any changes in the program.
In Java, the program is not converted to code directly understood by Hardware, rather it is converted to bytecode(.class file), which is interpreted by JVM, so once compiled it generates bytecode file, which can be run anywhere (any machine) which has JVM( Java Virtual Machine).
