---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "BankingApplication"
date: 2022-09-01
published: true
labels:
  - Java
  - Eclipse
summary: "I developed a banking application for an intro to java programming course."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The project aimed to create a simple banking application using Java and Eclipse. The primary goal was to design a program that allows users to interact with their bank accounts through a text-based menu. The `BankAccount` class encapsulated key functionalities like deposit, withdrawal, balance inquiry, and displaying previous transactions. The main method in the `BankingApplication` class instantiated a `BankAccount` object, initialized it with customer details, and then invoked the `showMenu` method to provide an interactive menu for users. The program demonstrated fundamental Java concepts such as classes, methods, conditional statements, and user input handling, providing a practical example of a basic banking system.

In this project, my role encompassed the entire development process. I initiated the project by conceptualizing the structure of the banking application and defining the key functionalities it should include. Subsequently, I implemented the Java code using the Eclipse IDE, creating the `BankAccount` class and integrating it into the `BankingApplication` class. I was responsible for designing the user interface, managing user input, and ensuring the correct execution of banking operations. The development process involved debugging and refining the code to achieve a functional and user-friendly application. Additionally, I documented the code and ensured that it adhered to best practices in Java programming.

Through this experience, I gained valuable insights into Java development and software design. I enhanced my proficiency in object-oriented programming, especially in creating and utilizing classes. The project provided hands-on experience in user interface design and interaction, as well as error handling and debugging. Working on this banking application honed my skills in problem-solving and decision-making within the context of software development. Overall, the project served as a practical learning opportunity, allowing me to apply theoretical knowledge to create a tangible and functional Java application.


```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

