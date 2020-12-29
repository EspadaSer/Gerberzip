# Gerberzip

A Python based application to easily create a winzip file with all the necesary Gerber and Drills of a project just with one click. 

This tool is aimed for people that do a lot of protyping of PCB's, as it will save you a little bit of time every time you have to send fabrication files to the PCB manufacturer. 

![Demo](https://raw.githubusercontent.com/EspadaSer/Gerberzip/master/Gerberzip.gif)

## How does it work?

You can access the program just by right clicking the project folder and selecting "@Gerberzip" option. The program will search just for the generated Gerber files and NC drills file and merge all of them into a single winzip file with the same name as the project folder name.  

## Installation / Usage

This program is made out of two files. The exe file is the program itself and the .reg file is a registry key to make the program appear in the windows desktop context menu. 

- Download [latest Gerberzip from releases](https://github.com/EspadaSer/Gerberzip/releases)
- Extract the files
- Run Gerberzip.reg. Accept all the windows. This will create the context menu on windows to easily access the program at any time.
- Copy Gerberzip.exe and place it on C:\ .
- The program will be ready to use. Now you can just right click a project folder and left click on @Gerberzip to run it. 

## Credits

- EspadaSer