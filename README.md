# EXPERIMENT--01-ALP-FOR-8086
Name : NATARAJ KUMARAN S

Roll no : 212223230137

Date of experiment : 22-08-2024





## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
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
```c
org 100h
MOV al,09h;
MOV bl,08h;
ADD al,bl;
MOV [1542h],al;
ret
```

## Output 
![image](https://github.com/user-attachments/assets/f39f4015-113e-4bf7-8e03-014bff0eb4a6)

 
## Subtraction of 8 bit numbers  ALP 
```c
org 100h
MOV al,14h;
MOV bl,[2443h];
SUB bl,al;
MOV [2443h],bl;
ret
```
 
## Output  
![image](https://github.com/user-attachments/assets/4ebb1758-6ce5-4c5b-9a71-10447ab4ac66)

## Multiplication alp
```c
org 100h
MOV al,09h;
MOV bl,08h;
ADD al,bl;
MOV [1542h],al;
ret
```
 ## Output  
 
![image](https://github.com/user-attachments/assets/819d4c0a-2889-4e2f-b092-a6c32e170f79)


## Division alp 

```c
org 100h
MOV al,32h;
MOV bl,[3343h];
DIV bl;
MOV [3343h],al;
ret

```

## Output  

![image](https://github.com/user-attachments/assets/184f44de-9f8e-4eba-a1b8-41bdeb9ebb4a)


## AND Operation

```c
org 100H
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX;
ret

```

## Output  

![image](https://github.com/user-attachments/assets/47a89897-8a91-42cc-86d3-87484372db1b)




## OR Operation

```c
org 100H
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
ret
```

## Output  

![image](https://github.com/user-attachments/assets/ba80a291-d2e8-4ab6-a8a7-4f5fc60b1236)


## NOT Operation

```c
org 100H
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
ret


```

## Output  

![image](https://github.com/user-attachments/assets/57550544-b979-4491-8600-6391cf86cebb)


## XOR Operation

```c
org 100H
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H;
XOR AX,BX;
ret


```

## Output  
![image](https://github.com/user-attachments/assets/a9dc326c-c72b-4d25-930d-6956be9a421c)



## Result :

 Thus, The ALP for Fundamental Arithmetic and logical operations are executed successfully.






