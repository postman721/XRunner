# XRunner
XRunner is a program launcher written with Java, which means it is very portable between different distributions.

XRunner v.2 Copyright (c) 2017 JJ Posti <techtimejourney.net> This program comes with ABSOLUTELY NO WARRANTY; for details see: http://www.gnu.org/copyleft/gpl.html. This is free software, and you are welcome to redistribute it under  GPL Version 2, June 1991")
________

![runner2](https://user-images.githubusercontent.com/29865797/36945732-3d557d82-1faa-11e8-8c11-abf399d0cda8.jpg)

______________________
About project’s structure:

dist folder has .jar files. These are the executables you want to run.
src folder has project sources.
nbproject folder has Netbeans project files.
____________________


Dependencies:

The program need Java JRE 1.8 or equivalent to run.

Linux: openjdk-8-jre. Debian/Ubuntu users can install something like: default-jre.

To build the project yourself install Netbeans. Netbeans should be available in most current distributions.

_____________________________
 
Run program with: java -jar something.jar

This program is tested with Windows 10 and PostX Gnu/Linux(Debian family). You should be able to run the .jar files easily without compiling the project.

While this program works on Windows, you might not get the desired results by default. Windows has only some commands(like notepad) ready for launching – without the full executable pathway.

One way to overcome the issue above, in Windows, is to create a series of custom launchers and then start the custom launchers via XRunner.

______________
Original post is at: http://www.techtimejourney.net/xrunnerjava-arrives/
