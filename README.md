# Encapsulation: Smart Door Access System for UMaT

This repository contains a Python implementation of an Object-Oriented Programming (OOP) solution designed for the University of Mines and Technology (UMaT). 

## Project Overview

The objective of this project is to develop a smart door access system for the UMaT admin staff as requested by the **Dean of ORIC, UMaT**. To ensure high security, each staff member's access code is strictly protected from direct external modification using foundational OOP principles—specifically **Encapsulation**.

## Core Features & Requirements

The implementation centers around a `Staff` class incorporating:
*   **Public Attribute:** `s_name` (Staff Name)
*   **Private Attribute:** `__access_code` (Protected hidden attribute)
*   **Encapsulation via Decorators:** Utilizes Pythonic `@property` and `@access_code.setter` mechanisms instead of conventional boilerplate getter/setter methods.
*   **Data Validation:** Restricts access code updates by validating string length criteria before finalizing changes.
*   **Information Display:** A secure built-in method to display staff parameters cleanly.

