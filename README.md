# Multi-Purpose Utility Application (The COAL Project)

## Description
This project is a comprehensive multi-purpose utility application developed in **x86 Assembly Language** using the **emu8086** emulator. 
Designed with a modular approach, the application provides a centralized main menu that allows users to perform various mathematical and administrative tasks directly through low-level system interactions.

## Features
The application is divided into four primary modules:

1. **Arithmetic Calculator:** Performs addition, subtraction, multiplication, and division on user-provided numbers.
2. **Logical Operator:** Executes bitwise logic operations including `AND`, `OR`, `XOR`, and `NOT` on two inputs.
3. **Binary Converter:** Automatically converts decimal numbers into their binary equivalents using a repeated division algorithm.
4. **Student Registration System:** A mini-database module that prompts for and stores student details such as Name, Reg No, Program, Semester, and CGPA, then displays them back to the user.

## Project Structure
**Main Menu:** The entry point where users select their desired operation (1-5).
**Data Section:** Defines all messages, buffers for student records, and numerical variables.
**Code Section:** Contains the procedural logic for each utility, utilizing DOS interrupts (e.g., `INT 21H`) for I/O operations.

## Requirements
]**Emulator:** [emu8086](https://emu8086-microprocessor-emulator.en.softonic.com/) or any compatible x86 8086 assembler.
- **Operating System:** Windows (supporting emu8086).

## How to Run
1.  Clone this repository to your local machine.
2. Open the `.asm` file (e.g., `coal1.asm`) in the **emu8086** environment.
3. Click on the **Compile** button to generate the executable.
4. Click **Emulate** and then **Run** to start the application.
5. Follow the on-screen prompts in the main menu to navigate through different utilities.

