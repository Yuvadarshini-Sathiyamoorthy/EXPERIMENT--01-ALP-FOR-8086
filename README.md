```
Name : Yuvadarshini S
Roll no : 212221230126
```
# EXPERIMENT 01: ALP FOR 8086

## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor.
It is developed with a built-in 8086 assembler. 
This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1. Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2. Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3. Write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4. Compile the program and check for the errors 
5. Run (once there is no syntax error) 
6. Click OK to see/view the output of your program on the Emulator screen. 
7. After running the program, another menu screen will be displayed, where you have the option to “View” symbol table<br>
8. ![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)<br>
9. Click on emulate to start emulation<br>
![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)
10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below<br>
![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition of 8 bit numbers ALP 
```
org 100h
MOV al,15H;
MOV bl,20H;
ADD al,bl;
MOV [43a1h], al;
ret
```
## Output  
 ![8086_add](https://github.com/Yuvadarshini-Sathiyamoorthy/EXPERIMENT--01-ALP-FOR-8086/assets/93482485/1f6d92b1-68ca-4c01-aeeb-0a4bc8900eb8)


## Subtraction of 8 bit numbers ALP 
```
org 100h
MOV al,25H;
MOV bl,20H;
ADD al,bl;
MOV [43a1h], al;
ret
```
## Output  
![8086_sub](https://github.com/Yuvadarshini-Sathiyamoorthy/EXPERIMENT--01-ALP-FOR-8086/assets/93482485/db6ffff7-cca7-4f72-80b9-ed8f6ed8edb2)


## Multiplication of 8 bit numbers ALP
```
org 100h
MOV al,25H;
MOV bl,20H;
MUL bl;
MOV [43a1h], al;
ret
```
## Output  
![8086_mul](https://github.com/Yuvadarshini-Sathiyamoorthy/EXPERIMENT--01-ALP-FOR-8086/assets/93482485/775d869f-a6f3-40d1-96d2-bd9e532d3b0d)

## Division of 8 bit numbers ALP
```
org 100h
MOV al,9DH;
MOV bl,2AH;
DIV bl;
MOV [43a1h], al;
ret
```
## Output  
![8086_div](https://github.com/Yuvadarshini-Sathiyamoorthy/EXPERIMENT--01-ALP-FOR-8086/assets/93482485/50468785-ea09-4337-961a-0b3e2389c647)

## Program for logical  operations
```
org 100H  

MOV SI,0532H;

MOV AX,0A32H;

MOV BX,0B13H;

OR AX,BX;

MOV [SI],AX;

MOV AX,0A32H;

MOV BX,0B13H;

AND AX,BX; 

MOV [SI+2],AX;

MOV AX,0A32H;

MOV BX,0B13H; 

XOR AX,BX;    

MOV [SI+4],AX;

MOV AX,0A32H;

NOT AX; 

MOV [SI+6],AX;

ret 
```
### Output:
![8086_div](https://github.com/amal-2006/EXPERIMENT--01-ALP-FOR-8086/assets/148410730/69b341bd-d8c5-4911-bfac-829daa209c65)

## Result :
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.
 






