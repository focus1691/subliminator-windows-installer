# Creating Subliminator installer for Windows

## Tools used:

* [Launch4j](http://launch4j.sourceforge.net/) — Cross-platform Java executable wrapper.
  * **.xml** file is the Launch4j configuration file.
* [Inno Setup](https://jrsoftware.org/ishelp.php) — free installer for Windows programs.
  * **.iss** file is the Inno Setup configuration file.

**Bundle the .jar to a .exe with Launch4j, and create an installer with Inno Setup.**

## Installation Steps

1) Load the .xml file into Launch4j, and compile the program. This will generate the .exe file.
2) Load the .iss file into Inno Setup, and compile. This will generate the subliminator.exe installer in an *output folder*.

## Required files

* Subliminator.jar — needs to be added to the project directory. Create a runnable jar file.
