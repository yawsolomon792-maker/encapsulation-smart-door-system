📘 Encapsulation Smart Door System
📌 Introduction

This repository contains a Python implementation of a Smart Door Access System developed as part of a case study for UMAT. The system is designed for administrative staff and focuses on protecting sensitive access credentials using Object-Oriented Programming (OOP) principles.

🧩 Task Summary

The task involves designing a Staff class to simulate a secure door access system with the following requirements:

Each staff member has:
A public name attribute (s_name)
A private access code (__access_code) that must not be directly modified
The system must:
Allow authorized users to view the access code
Allow updating the access code only after validation (minimum length requirement)
Provide a method to display staff information
Use Python’s @property decorator instead of traditional getter and setter methods
🎯 Purpose of the Project

The main goal of this project is to demonstrate the concept of encapsulation, where sensitive data is hidden and only accessed through controlled methods, improving security and data integrity.

🛠 Implementation Overview
Programming Language: Python
Concept Used: Encapsulation
Key Feature: Controlled access to private data using @property
📂 Repository Contents
main.py → Contains the implementation of the Staff class and test cases
README.md → Documentation and summary of the task
✅ Conclusion

This project shows how encapsulation can be applied in real-world systems to protect sensitive information such as access codes, ensuring that only authorized and validated operations are allowed.
