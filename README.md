
# 8085---Zadaca9
Систем базиран на 8085 служи за контрола на
влегување во заштитена просторија. По добивање на знак за
старт, на тастатурата на влезот од просторијата, за време од 5
сек треба да се внесат 2 бајти. Да се нацрта хардверско
поврзување и напише процедура за опслужување на
тајмерот.

РЕШЕНИЕ:


![sl1](https://github.com/nikolovskaaleksandra/8085-zad9/assets/170895283/42a63d21-964c-453c-8e96-21705b95f7bd)


fosc =5MHz  t=0,2µsec  ts=0.4µsec

2^14=16384 6.5 msec ;8156 може да брои max 6.5 msec

TH,TL 16000 -> 6.4 msec ;ако TH и TL се наполнат со 16000d, 8156 ќе јавува интерапт на секои 6.4 msec

6.4*156=1000ms=1 sec ;потребно е 156 пати 8155 да јави интерапт за да знаеме дека изминала 1 sec.

**Developed by:**

(https://github.com/nikolovskaaleksandra)


**Subject**

Microcomputer's systems

**Built With**

This project is built using the following tools:

- [8085 simulator](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file): Assembler and emulator for the Intel 8085 microprocessor.

**Getting Started**

To get a local copy up and running, follow these steps.

**Prerequisites**

In order to run this project you need:

A working computer
Connection to internet
Setup

**How to Run**

To run the program, you need an 8085 emulator or assembler. You can use emulators like DOSBox or TASM (Turbo Assembler). Here's how to run the program using e8085.exe:

1. Download and install 8085 simulator from [here](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file).
2. Clone this repository to your local machine.
3. Open 8085 simulator and load the `zadaca9.asm` file.
4. Assemble the code by pressing the Assemble button.
5. Run the program by pressing the Run button or by pressing F10.

