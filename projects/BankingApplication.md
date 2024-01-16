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

For this project, I was the lead programmer who was responsible for programming the various requirements of the banking application. The provided Java code represents a simple banking application implemented using the Eclipse IDE. The project consists of two classes: `BankingApplication` and `BankAccount`. The `BankAccount` class encapsulates the banking functionalities, including deposit, withdrawal, checking the balance, and displaying previous transactions. The main method in the `BankingApplication` class initializes a new `BankAccount` object with customer details and then invokes the `showMenu` method to provide a menu-driven interface for the user. The user can perform operations such as checking the balance, depositing money, withdrawing funds, and viewing previous transactions. The program runs until the user chooses to exit (option 'E'). The code demonstrates the use of basic Java concepts such as classes, methods, conditional statements, loops, and user input handling. It offers a practical example of a text-based banking application that can be run and interacted with in a console environment.


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

