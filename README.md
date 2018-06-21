# linux-accessibility-scripts

Here are some usefull scripts to quickly and seamlessly setup the enviroment for visualy impaired programmers. It's aimed at Ubuntu and Ubuntu-like Linux distros.

## Preparation
This step will probably require assistence of an another person, it requires only a few commands to be run

### aptitude
Most software is installed from the main Ubuntu package manager, aptitude.

### snapd
It's a package repository that can be used for various distros. IDEs and code editor are downloaded from there. Before usingit for the first time, it also need to be installed.

## Languages, tools and more

### Basic tools
Scripts start with installing basic tools and compilers. They are aimed at Scala and Python programmers, so the scripts install: openjdk8, sbt, python. Git is also included.

### Accessible scala
Accessible scala is a plugin for Visual Studio Code that enable the user to easier navigate the code written in Scala language. 

### IDEs
Installed IDEs and code editors include JetBrains software (community versions) - IntelliJ IDEA and Pycharm - and Visual Studio Code. 

## Instruction
The most preferable order of executing scripts is: 
* scala.sh
* intellij.sh
* pycharm.sh
