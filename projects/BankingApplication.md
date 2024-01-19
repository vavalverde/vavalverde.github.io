---
layout: project
type: project
image: img/BAMenu1.png
title: "Banking Application"
date: 2022
published: true
labels:
  - Java
  - Eclipse
summary: "I developed a banking application for an intro to java programming course."
---

<div class="text-center p-4">
  <img width="300px" src="../img/BAResult.png" class="img-thumbnail" >
</div>

## Project Overview
The primary goal was to design a program that allows users to interact with their bank accounts through a text-based menu. The `BankAccount` class encapsulated key functionalities like deposit, withdrawal, balance inquiry, and displaying previous transactions. The main method in the `BankingApplication` class instantiated a `BankAccount` object, initialized it with customer details, and then invoked the `showMenu` method to provide an interactive menu for users. The program demonstrated fundamental Java concepts such as classes, methods, conditional statements, and user input handling, providing a practical example of a basic banking system.

## Development Process
In this project, my role encompassed the entire development process. I initiated the project by conceptualizing the structure of the banking application and defining the key functionalities it should include. Subsequently, I implemented the Java code using the Eclipse IDE, creating the `BankAccount` class and integrating it into the `BankingApplication` class. I was responsible for designing the user interface, managing user input, and ensuring the correct execution of banking operations. The development process involved debugging and refining the code to achieve a functional and user-friendly application. Additionally, I documented the code and ensured that it adhered to best practices in Java programming.

## A Learning Experience
Through this experience, I gained valuable insights into Java development and software design. I enhanced my proficiency in object-oriented programming, especially in creating and utilizing classes. The project provided hands-on experience in user interface design and interaction, as well as error handling and debugging. 


```cpp
	void showMenu() {
		
		char option = '\0';
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("Welcome " +customerName);
		System.out.println("Your ID is "+ customerId);
		System.out.println("\n");
		System.out.println("A Check Balance");
		System.out.println("B Deposit");
		System.out.println("C Withdraw");
		System.out.println("D Previous Transaction");
		System.out.println("E Exit");
		
		do {
			System.out.println("======================================");
			System.out.println("Enter an option");
			System.out.println("======================================");
			option = scanner.next().charAt(0);
			System.out.println("\n");
			
			switch(option) {
			
			case 'A':
				System.out.println("======================================");
				System.out.println("Balance = "+ balance);
				System.out.println("======================================");
				System.out.println("\n");
				break;
		

```

