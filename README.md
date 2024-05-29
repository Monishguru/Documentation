# Java & Spring Framework Training Program

Welcome to the Java & Spring Framework Training Program. This document provides the necessary information on the computer requirements, software installations, and setup needed for this course.

## Computer Requirements

To ensure a smooth learning experience, please ensure your computer meets the following minimum specifications:

- **Operating System**: Windows 10 or later, macOS 10.15 or later, or a modern Linux distribution
- **Processor**: Intel i5 or AMD equivalent (Quad-core or higher recommended)
- **RAM**: 8GB minimum (16GB recommended)
- **Storage**: At least 20GB of free space
- **Internet Connection**: Stable internet connection for downloading software and accessing online resources

 **NOTE**: Any modern day laptop or desktop should work fine. Above are just good to have minimum requirements. If you miss something, dont worry we can figure out a way

## Software to Install

### 1. Java Development Kit (JDK)

- **Version**: JDK 11 or later
- **Download Link**: [Oracle JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or [OpenJDK](https://openjdk.java.net/install/)

### 2. Integrated Development Environment (IDE)

- **Recommended IDE**: IntelliJ IDEA Community Edition
- **Download Link**: [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)

### 3. Postman

- **Purpose**: API development and testing tool
- **Download Link**: [Postman](https://www.postman.com/downloads/)

## Setup Instructions

### 1. Installing JDK

1. Download the JDK installer from the provided link.
2. Run the installer and follow the on-screen instructions.
3. Set the `JAVA_HOME` environment variable:
   - **Windows**: 
     1. Open `System Properties` > `Environment Variables`.
     2. Add a new system variable `JAVA_HOME` with the path to your JDK installation directory.
     3. Update the `Path` variable and add `%JAVA_HOME%\bin`.
   - **macOS/Linux**: Add the following lines to your `.bash_profile`, `.bashrc`, or `.zshrc` file:
     ```sh
     export JAVA_HOME=/path/to/your/jdk
     export PATH=$JAVA_HOME/bin:$PATH
     ```

### 2. Installing IntelliJ IDEA

1. Download the IntelliJ IDEA installer.
2. Run the installer and follow the on-screen instructions.
