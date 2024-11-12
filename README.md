# EX1  - ARITHMETIC OPERATION AND LOGICAL OPERATION IN 8086 

## AIM : 

To Write and execute ALP on fundamental arithmetic and logical operations in 8086.

## COMPONENTS REQUIRED : 

8086  emulator 

## THEORY :

Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## RUNNING THE EMULATOR :
 
1. Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory.
2. Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color. 
3. Write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations .
4. Compile the program and check for the errors 
5. Run (once there is no syntax error) 
6. Click OK to see/view the output of your program on the Emulator screen. 
7. After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
   
     ![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)
    
8. Click on emulate to start emulation.
   
     ![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

9. If no errors are found click on run the program and check the status of various flags in the flags tab as shown beloW.
	
    ![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)


##  PROGRAMS FOR ARITHMETIC OPERATION :

### ADDITION OF 8 BIT ALP :
```
MOV AL,88H
MOV BL,65H
ADD AL,BL
HLT
```
### OUTPUT : 
![image](https://github.com/user-attachments/assets/4c3d6bc2-e478-4832-9bf8-fe122d02bbc9)

 
### SUBRACTION OF 8 BIT ALP :
```
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT
```
 
### OUTPUT : 
![image](https://github.com/user-attachments/assets/47cbb277-26ca-435e-ac8d-11690ab27085)


### MULITIPLICATION OF ALP :
```
MOV AL,75H
MOV BL,32H
MUL BL
HLT
```
 ### OUTPUT :
 ![image](https://github.com/user-attachments/assets/528707a9-44fb-44c2-9bfb-78052a5e6454)



### DIVISION OF ALP :
```
MOV AL,68H
MOV BL,18H
DIV BL
HLT
```
### OUTPUT : 
![image](https://github.com/user-attachments/assets/47027162-685b-44c3-9f26-b10505df0333)

##  PROGRAMS FOR LOGICAL OPERATION :

### AND OF 8 BIT ALP :
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
### OUTPUT :
![image](https://github.com/user-attachments/assets/bfa514e8-7fc1-472a-9c5b-730cb33ff0ff)


## OR OF 8 BIT ALP :
```
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
### OUTPUT :
![image](https://github.com/user-attachments/assets/60264f41-2482-4f98-aa96-48bbd776bba1)


### NOT FOR 8 BIT ALP :
```
MOV AL,65H
NOT AL
HLT
```
### OUTPUT :
![image](https://github.com/user-attachments/assets/5a88ce6e-40d6-4d2c-8053-e954062b02b7)


## XOR FOR 8 BIT ALP :
```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```
### OUTPUT :
![image](https://github.com/user-attachments/assets/17cb8836-a849-4b77-90d3-b8a04d08396d)


## RESULT :
The execution of ALP on fundamental arithmetic and logical operations in 8086 is successfully completed.
 








