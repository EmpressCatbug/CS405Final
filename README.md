# CS 410 Secure Coding Final

Welcome to the repository for my CS 410 Final Project. This repository contains all the work completed for the course, including project documentation, presentations, and coding artifacts.

## Table of Contents

- [Project One: Security Policy](#project-one-security-policy)
- [Project Two: Presentation](#project-two-presentation)
- [Coding ZIP Files](#coding-zip-files)
  - [Static Code Thompson](#static-code-thompson)
  - [CS 405 M5 Encryption Thompson](#cs-405-m5-encryption-thompson)
  - [CS 405 Unit Test Thompson](#cs-405-unit-test-thompson)
  - [CS 405 Expectations Thompson](#cs-405-expectations-thompson)
  - [Buffer Overflow Thompson](#buffer-overflow-thompson)
  - [SQL Injection Thompson](#sql-injection-thompson)
  - [Numeric Overflow Thompson](#numeric-overflow-thompson)
- [Portfolio Journal Reflection](#portfolio-journal-reflection)

## Project One: Security Policy

This project involves the development of a comprehensive security policy for Green Pace, an environmentally-focused software company. The project requires documenting, categorizing, and providing examples for coding and architectural vulnerabilities, with a focus on implementing a DevSecOps approach. The policy includes coding standards, risk assessments, automated detection tools, and policies for encryption and the Triple-A security framework.

- **Document:** [CS 405 Project 1 Thompson.docx](./CS%20405%20Project%201%20Thompson.docx)

## Project Two: Presentation

This project builds on the security policy created in Project One by presenting it to the Green Pace development team. The presentation includes policies, standards, principles, and best practices designed to prevent security vulnerabilities in both code development and systems architecture. It covers a threat matrix, coding standards, encryption strategies, the Triple-A framework, and unit testing methods.

- **YouTube Video:**
  [![Project Two Presentation](https://img.youtube.com/vi/zSYLCtxr2fc/0.jpg)](https://www.youtube.com/watch?v=zSYLCtxr2fc)


## Coding ZIP Files

The following ZIP files contain the code and configurations related to different coding exercises completed throughout the course.

### Numeric Overflow Thompson

- **File:** [NumericOverflowThompson.zip](./NumericOverflowThompson.zip)
- **Description:** This assignment involved detecting and preventing numeric overflows and underflows in a large banking application. The code modifications ensure that operations like addition and subtraction do not result in incorrect calculations due to overflow or underflow.

### SQL Injection Thompson

- **File:** [SQLInjectionThompson.zip](./SQLInjectionThompson.zip)
- **Description:** This assignment focused on preventing SQL injection attacks in a banking web application. The code was modified to detect potential SQL injection attempts, particularly those using the "OR value=value;" attack, and to prevent them from executing.

### Buffer Overflow Thompson

- **File:** [BufferOverflowThompson.zip](./BufferOverflowThompson.zip)
- **Description:** In this assignment, the code was modified to prevent buffer overflow attacks that could potentially alter customer account numbers in a banking web application. The solution ensures that user inputs do not exceed the allocated buffer size, preventing memory corruption.

### Static Code Thompson

- **File:** [Static CodeThompson.zip](./Static%20CodeThompson.zip)
- **Description:** This assignment involved using static code analysis tools like Cppcheck and Visual Studio to identify and fix common coding issues in a banking web application. The goal was to understand and mitigate potential vulnerabilities through static analysis.

### CS 405 M5 Encryption Thompson

- **File:** [CS 405 M5 EncryptionThompson.zip](./CS%20405%20M5%20EncryptionThompson.zip)
- **Description:** This assignment required implementing XOR-based encryption for a banking application. The code handles the encryption and decryption of data, ensuring secure storage and transmission of sensitive information.

### CS 405 Unit Test Thompson

- **File:** [CS 405 Unit Test Thompson.zip](./CS%20405%20Unit%20Test%20Thompson.zip)
- **Description:** This assignment involved creating unit tests for a banking application using the Google Test framework. The tests include both positive and negative cases to ensure the application behaves as expected under various conditions.

### CS 405 Expectations Thompson

- **File:** [CS 405 Expections Thompson.zip](./CS%20405%20Expections%20Thompson.zip)
- **Description:** This assignment focused on exception handling in a banking application. The code was modified to properly catch and handle exceptions, ensuring that errors are gracefully managed without crashing the application.
