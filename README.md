# POLITO-LANDTIGER-BOARD-GAME
This project contains codes of a small video game developed as a semester project at Polito based on ARM Land Tiger board, using mainly on-board potentio-meter and GLCD.
This project includes file named "Obstace avoidance game Del(WALID,TAHIR).rar" that contains compiled project.
To run it on your LandTiger V2 board, upload this project and enjoy:)
We used libraries from keil website for GLCD,ADC,ASCII,System and Core libraries. 
We modiefied the Draw Circle(LCD_Circle) function inside the library to draw a filled circle.

If the project shows that it cannot find a file or file does not exist than it is probably because path of LPC17xx.h file is incorrrect in GLCD.h header file.
Go to GLCD.h and modify the path of LPC17xx.h according to file location in your PC.
