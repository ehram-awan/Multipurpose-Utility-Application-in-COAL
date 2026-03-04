# Multi-Purpose Utility Application (The COAL Project)

## Description
[cite_start]This project is a comprehensive multi-purpose utility application developed in **x86 Assembly Language** using the **emu8086** emulator[cite: 4, 18]. [cite_start]Designed with a modular approach, the application provides a centralized main menu that allows users to perform various mathematical and administrative tasks directly through low-level system interactions[cite: 5, 6].

## Features
The application is divided into four primary modules:

1.  [cite_start]**Arithmetic Calculator:** Performs addition, subtraction, multiplication, and division on user-provided numbers[cite: 10, 54].
2.  [cite_start]**Logical Operator:** Executes bitwise logic operations including `AND`, `OR`, `XOR`, and `NOT` on two inputs[cite: 12, 56].
3.  [cite_start]**Binary Converter:** Automatically converts decimal numbers into their binary equivalents using a repeated division algorithm[cite: 14, 59].
4.  [cite_start]**Student Registration System:** A mini-database module that prompts for and stores student details such as Name, Reg No, Program, Semester, and CGPA, then displays them back to the user[cite: 16, 17].

## Project Structure
- [cite_start]**Main Menu:** The entry point where users select their desired operation (1-5)[cite: 8, 38].
- [cite_start]**Data Section:** Defines all messages, buffers for student records, and numerical variables[cite: 32, 35].
- [cite_start]**Code Section:** Contains the procedural logic for each utility, utilizing DOS interrupts (e.g., `INT 21H`) for I/O operations[cite: 37, 51].

## Requirements
- [cite_start]**Emulator:** [emu8086](https://emu8086-microprocessor-emulator.en.softonic.com/) or any compatible x86 8086 assembler[cite: 18, 20].
- **Operating System:** Windows (supporting emu8086).

## How to Run
1.  Clone this repository to your local machine.
2.  [cite_start]Open the `.asm` file (e.g., `coal1.asm`) in the **emu8086** environment[cite: 18, 20].
3.  [cite_start]Click on the **Compile** button to generate the executable[cite: 20].
4.  [cite_start]Click **Emulate** and then **Run** to start the application[cite: 20].
5.  [cite_start]Follow the on-screen prompts in the main menu to navigate through different utilities[cite: 52, 53].

