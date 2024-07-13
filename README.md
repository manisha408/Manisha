
shi TRAINING REPORT ON JAVA LANGUAGE

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

• A Package is a collection of class, interface and sub-package contains collection of classes , interface and sub-package etc. 

. Class is keyword used for developing user defined data type and every java program must start with a connept of class. 



Main() Method

Main() method is starting execution block of java program or any program start their execution form main method. if any class contain main() method knows as main class. 



•Decision Making Statement

decision making statement is also called selection statement. That is depending on the conditional block need to be executed or not which is decided by condition. if the condition is 'true' statement block will be executed, if condition is ' false' then statement block not be executed. 

In Java three are three types of decision making statement. 


. if

. if-else

. switch



•Looping statements
for loop, while loop or do while loop. 



         * Constructor and It's types *


A constructor is a special members method which will be called implicitly by the JVM whenever as object is created for placing user and programmer defined values in place or default value . 

Types of Constructor

based on creating object in java constructor and classified in two types . they are

. Default or no argument Constructor
. Parameterized constructors 

static block is a set of statement which will be executed by the JVM before execution of main method. at the time of class loading if we want to perform any activity we have to defined that activity inside static block execute at the time of class loading.


             **JAVA OBJECT ORIENTED**

Inheritance 

The process of obtaining the data members and method from one class to another class is known as inheritance. it is one of the fundamental feature of object oriented programming. 

//Types of inheritance

. Single inheritance
. multiple inheritance
. hierarchical inheritance
. multilevel inheritance
. hybrid inheritance




              𝙋𝙍𝙊𝙅𝙀𝘾𝙏 𝙐𝙉𝘿𝙀𝙍𝙏𝘼𝙆𝙀𝙉


Connect for whether App:  

• 𝘾𝙊𝙈𝙈𝙊𝙉

1. Created package common, and a class in the 
   package alsa called common. 

2. This will help to hold data sharing. 

3. Taken API key from an open source website ,   
   called open weathermap which is london based  
   company which shares data regarding the                 
   weather to developer. 

4. API_LINK is link API of open weatherMap. 
   And we will create a function to create a 
   functional link to the API path. 

5. create a function to convert unix  time 
   stamp to date type with format "HH:mm".

6. A three function will be used to get a link 
   image from open WeatherMap . 

7. Finally a forth function will be create to 
   get date with format "DD/MM/YY"HH:mm.

   𝙈𝙊𝘿𝙀𝙇 

. look at the json string from open weatherMap,  
  API and create a model package for it. 

. consider all the parameters and then create 
  seperate class for each under the same 
  package, also create constructor in each 
  class with getter and setter respectively. 

𝙍𝙚𝙨𝙪𝙡𝙩𝙨 𝙖𝙨 𝙫𝙖𝙧𝙞𝙤𝙪𝙨 𝙨𝙩𝙖𝙜𝙚𝙨

• 𝙎𝙩𝙚𝙥 𝙩𝙖𝙠𝙚𝙣 𝙗𝙮 𝙩𝙝𝙚 𝙤𝙥𝙚𝙣 𝙨𝙤𝙪𝙧𝙘𝙚 𝙬𝙚𝙗𝙨𝙞𝙩𝙚

• climate API: Climate forecast for 30 days. 

  climate forecast for 30 days allow you to request weather data for next 30 days. this is a statistical approach and weather data are updated with hourly frequency. 

• hourly forecast: 

hourly forecast for 4 days with 96 timestamp and very high geographic Accourecy. 

. Integrated Timezones 
 
dues to this, the 'Timezones' filed provides a shift in second from UTC. 

• feels like:

this parameters is added and it account for human reception of weather it let's you know how the temperature feels . 



𝙊𝙐𝙏𝙋𝙐𝙏 𝘼𝙏 𝙑𝘼𝙍𝙄𝙊𝙐𝙎 𝙎𝙏𝘼𝙂𝙀𝙎

𝙎𝙩𝙚𝙥:1 enter the name of the city in the first box that is typed as shimla here. then write the number of days  for which you need to find the forecast. 

The app will fetch the data from the open source website open weatherMap and we will be able to fetch the data from there, onto over mobile screen. 


𝙎𝙩𝙚𝙥:2 The application requirs proper internet connection to display the correct results. Here as we can see the weather report for five days has been display on the mobile screen. 

you can click on any one slot to access the minimum and maximum temperatur on one particular day. 


𝗦𝘁𝗲𝗽:3 we are performing the first step again , but this time we are entering the result for delhi for just one day. 
 

𝙎𝙩𝙚𝙥:4 however if you wish to access the maximum and minimum temperature, you need to tap on the icon. 


𝙎𝙩𝙚𝙥:5 when we tap on the icons the following result is displaying on the application. here we get the date e.g 14th,2024 then the average temperatur , then the icon displaying that it is a cloud day . and finally we get the min and max temperature of that day. 


