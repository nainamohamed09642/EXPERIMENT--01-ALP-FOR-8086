# EXPERIMENT--01-ALP-FOR-8086
## Name : NAINA MOHAMED Z
## Roll no : 212223230131
## Date of experiment : 07/03/2025





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
MOV AL,32H
MOV BL,66H
add AL,BL
HLT
```



## Output  
 ![Screenshot 2025-03-07 131801](https://github.com/user-attachments/assets/e4f0b76b-ec6b-4f29-a338-a5ecead21820)
## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,32H
MOV BL,66H
sub AL,BL
HLT
```
## Output  
![Screenshot 2025-03-07 132140](https://github.com/user-attachments/assets/f325eec1-a69d-41c7-9a12-fa49c18e4d68)

## Multiplication alp 
 ```
MOV AL,32H
MOV BL,66H
mul AL
HLT
```
 ## Output
 ![Screenshot 2025-03-07 132402](https://github.com/user-attachments/assets/10b1a936-8904-47d2-a5ac-20839d3336d9)



## Division alp 
 ```
MOV AL,32H
MOV BL,66H
div AL
HLT
```

## Output  
![Screenshot 2025-03-07 132533](https://github.com/user-attachments/assets/8fba6c28-295f-480d-aceb-de542435f7e2)

## AND OPERATION of 8 bit ALP
```
MOV AL,32H
MOV BL,66H
and AL,BL
HLT
```
## Output
![Screenshot 2025-03-07 132625](https://github.com/user-attachments/assets/eb93b1eb-9ab9-46bb-bec6-74562176c4d9)

## OR OPERATION of 8 bit ALP
```
MOV AL,32H
MOV BL,66H
or AL,BL
HLT
```
## Output
![Screenshot 2025-03-07 132711](https://github.com/user-attachments/assets/a932c654-5fab-41f4-9b95-f532757ff965)
## NOT OPERATION of 8 bit ALP
```
MOV AL,32H
not AL
HLT
```
## Output
![Screenshot 2025-03-07 132913](https://github.com/user-attachments/assets/fc81c134-2814-4b0f-9955-ee353a606dab)

## NAND OPERATION of 8 bit ALP
```
MOV AL,32H
MOV BL,66H
AND AL,BL
not AL
HLT
```
## Output
![Screenshot 2025-03-07 133021](https://github.com/user-attachments/assets/08b3c580-be28-41ad-99c4-a39b15ac3cce)

## XOR OPERATION of 8 bit ALP
```
MOV AL,32H
MOV BL,66H
OR AL,BL
not AL
HLT
```
## Output
![Screenshot 2025-03-07 133120](https://github.com/user-attachments/assets/25ac85ae-c903-42fc-87e8-4d5993b04cf0)

## Result :
Thus Writing and execution ALP on fundamental arithmetic and logical operations have been done and verified. 

 








