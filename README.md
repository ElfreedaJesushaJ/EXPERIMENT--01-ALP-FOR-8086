# EXPERIMENT--01-ALP-FOR-8086
Name :J Elfreeda Jesusha
Roll no:212224040084 
Date of experiment :18.03.2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
Mov AL,74H
Mov BL,69H
ADD AL,BL
HLT
```

## Output
![8bit add](https://github.com/user-attachments/assets/b539d674-2fc3-4739-bf91-c3e3e00b7d6a)

 
## Subtraction   of 8 bit numbers  ALP 
```
Mov AL,74H
Mov BL,69H
SUB AL,BL
HLT
```
 
## Output
![8bit sub](https://github.com/user-attachments/assets/435a8990-3037-44e9-8a5a-430ee6af398a)

## Multiplication alp
```
Mov AL,75H
Mov BL,32H
MUL BL
HLT
```
 ## Output  

![8bit mul](https://github.com/user-attachments/assets/d727f1e6-c66b-47d2-a923-60b73ab64e86)

## Division alp 
```
org 100h
MOV AL,68H
MOV BL,18H
DIV BL
HLT
ret
```

## Output  
![8bit div](https://github.com/user-attachments/assets/bfd18afa-f636-4345-aa85-b668f1524c8d)

## Programs for logical operations

## AND Operation alp
```
Mov AL,33H
Mov BL,44H
AND AL,BL
HLT
```
## Output
![and op](https://github.com/user-attachments/assets/0d1a3fb9-9dbc-47b9-84a9-a6605d6b0b21)

## OR Operation alp
```
Mov AL,33H
Mov BL,44H
OR AL,BL
HLT
```
## Output
![or op](https://github.com/user-attachments/assets/a8a6c20a-b217-46ec-b5c1-eb774afb82df)

## NOT Operation alp
```
Mov AL,65H
NOT AL
HLT
```
## Output
![not op](https://github.com/user-attachments/assets/ea682b42-466a-432f-b5db-95888af2e17f)

## XOR Operation alp
```
Mov AL,66H
Mov BL,77H
XOR AL,BL
HLT
```
## Output

![xor op](https://github.com/user-attachments/assets/083a9054-afa7-4396-a2b0-d96475601715)

## Result :
   The fundamentals of arithmetic and logical operations are written and executed successfully on ALP.








