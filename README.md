

koodagolishi TRAINING REPORT ON JAVA LANGUAGE

Submitted in partial fulfillment of the requirements for the award of  degree of
    
        MASTER OF COMPUTER SCIENCE
    Guru Jambheshwar University, HISAR
  

submitted by
MANISHA
Class rollno_2232687027
University rollno_233112720023
     

                   DECLARATION
 
I Manisha student of Master of Computer Science 2nd semester in the department of computer science Guru Jambheshwar University,HISAR under class rollno_2232687027, university rollno_233112720023 for session 2023-2025 here by declare that the training report entitled "core java" has been completed by me at internship. 


The matter embodied in this training work has not been submitted earlier for award of any degree Or diploma to the best of my knowledge and any degree Or diploma to the best of my knowledge and belief . 

   
                                 MANISHA
    


             JAVA INTRODUCTION
  

Java is one of the programming language of technology used for developing web application.  Java language developed at SUN micro system in the year of 1995 under the guidance of James gosling and there team. 

JAVA decided into three categories they are

° J2SE (JAVA 2 standard edition) 
° J2EE (JAVA 2 enterprise edition) 
° J2ME (JAVA 2 micro or mobile edition) 
  

  °J2SE is used for developing for client side
    application. 
   
  °J2EE is used for developing for server side  
   applications. 
   


                  BASICS OF JAVA 

Overview Of JAVA
 
Java is a platform independent, more powerful, secure, high performance multithreade

programming language. Here we discuss some points related to Java. 

 
°Define JRE

The Java runtime environment is part of the Java development kit. It contains set of libraries and tools for developing Java application. 

°Define JVM

JVM is set of program developed by sun Micro System and supplied as a part of jdk for reading line by line of byte code and it converts into native understanding form of operating system. 

° Garbage Collector
 
Garbage collector is the system Java program which runs in the background along with regular Java program to collect Un-referenced memory space for improving the performance of our application. 

° Define an API

An API (application programming interface) is a collection of packages. A package is the collection of classes. 


Difference Between JDK, JRE AND JVM. 
 
JVM, JRE, and jdk these all  the backbone of Java language. eack components have separated works. jdk and jre physically exists but JVM are abstract machine it means it not physically exists. 
JVM:JVM (Java virtual machine) is a software. it is a specification that provides runtime environment in which Java bytecode can be executed. it not physically exists. JVMs are not same for all hardware and software, for example for window os JVM is different and for linux VJM is different. 

JRE: The Java runtime environment is part of the Java development kit(JDK). it contains set of libraries and tools for developing Java application. The Java Runtime environment provides the minimum requirements for executing a Java application. 

JDK: The Java development kit(JDK) is primary components. it physically exists. it is collection of programming tools and JRE, JVM. 


• Object and Class

Object is the physically as well as logical entity where as class is the only logical entity. 

Class: class is a blue print which is containing only list of variables and method and no memory is allocated for them. A class is a group of objects that has common properties. 
 
 A class is Java contains:
 
 . Data Member
 . Method
 . Constructor
 . Block
 . Class and Interface
 
Object: object is a instance of class, object has state and behavior. An object in Java has three characteristics. 
• State
• behavior
• Identify


• State: represent data of an object. 

• Behavior: represent the behavior of an object  such as deposit , withdraw etc. 

• Identify: object identify is typically implemented via a unique ID. The value of the id is not visible to the external user. 



            * PROGRAMMING CONCEPT *


Structure of Java Program

Structure of a Java program is the standard format released by language developer to the industry programmer . Sun Micro System has prescibed the following structure of java programmer for developing for java application.



Package details ----------------> import Java. io
class ClassName ----------------> class sum
{ 
Data members;-----------------> int a, b, c;

User_defined method;----------> void display() ;

public static void main(string args[]) 
{
block of statement;---------->System.out.println("hellow Java!") ;
}
}

• A Package is a collection of class, interface and sub-package . 

