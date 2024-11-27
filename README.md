# Password Generator

A Java Console Application that generates secure random passwords and checks password strength.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation and Usage](#installation-and-usage)
    - [Prerequisites](#prerequisites)
    - [Running the Application](#running-the-application)
- [Usage](#usage)
    - [Generating a Password](#generating-a-password)
    - [Checking Password Strength](#checking-password-strength)
- [Security Tips](#security-tips)

## Introduction

The Password Generator is a Java-based console application designed to help users create secure passwords and assess the strength of existing ones. This tool promotes better security practices by ensuring passwords are strong and comply with recommended guidelines.

## Features

- **Password Generation**: Create random passwords based on user-defined criteria, including:
    - Use of uppercase letters
    - Use of lowercase letters
    - Inclusion of numbers
    - Inclusion of symbols
    - Customizable password length
- **Password Strength Checker**: Evaluate the strength of any given password against key security criteria.

## Installation and Usage

### Prerequisites

- Java Development Kit (JDK) 8 or higher installed on your system
- Command-line interface access (Terminal, Command Prompt, etc.)

### Running the Application

#### Windows

1. Open Command Prompt.
2. Navigate to the project directory:
     ```cmd
     cd C:\path\to\password-generator
     ```
3. Compile the Java files:
     ```cmd
     javac PasswordGenerator.java
     ```
4. Run the application:
     ```cmd
     java PasswordGenerator
     ```

#### macOS and Linux

1. Open Terminal.
2. Navigate to the project directory:
     ```bash
     cd /path/to/password-generator
     ```
3. Compile the Java files:
     ```bash
     javac PasswordGenerator.java
     ```
4. Run the application:
     ```bash
     java PasswordGenerator
     ```

## Usage

### Generating a Password

- The application will prompt you to include various character types. Answer with "Yes" or "No":
    - Use uppercase letters?
    - Use lowercase letters?
    - Use numbers?
    - Use symbols?
- Enter the desired password length when prompted.
- The generated password will be displayed on the console.

### Checking Password Strength

- When prompted, enter the password you wish to evaluate.
- The application will assess the password based on:
    - Use of uppercase and lowercase letters
    - Inclusion of numbers and symbols
    - Password length
- A strength score and feedback will be provided.

## Security Tips

- Avoid reusing passwords across different accounts.
- Do not use easily guessable information like birthdays or common words.
- Regularly update your passwords to reduce the risk of compromise.
- Consider using a password manager to store and manage your passwords securely.
