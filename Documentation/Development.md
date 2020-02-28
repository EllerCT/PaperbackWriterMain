# Development Manual

## **Description**

This development manual will explain tech aspects of our system, required technologies to replicate the development environment,
folder structure in our code repositories, important files, and other important aspects of development.


## **Technologies Required**
These are the technologies our group have used to create our program. For our project structure language, level 11 is utilized.
- Intellij
- JDK 11
- Maven
- Git
- Intellij GUI Designer

## **Instructions**
1. Ensure you have a version of Java version 11 or later installed on the local machine.
  1. If Java is not installed, get the latest [Here](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
1. Ensure [Git](https://git-scm.com/downloads) is installed normally.
1. Ensure [IntelliJ](https://www.jetbrains.com/idea/download/) is installed and configured to taste on your machine.
1. Open IntelliJ IDE
1. Select **Check out from Version Control**
1. Paste the URL of the code repository in the text box
1. Select a directory
1. Select **Clone**
1. Wait for this to complete.
1. With the project open, ensure Maven is set to auto-import dependencies.
1. You may have to enable IntelliJ's GUI designer plugin.
1. To do this, go to *File, Settings.., Plugins, Installed...*
1. Find **UI Designer** and ensure the checkbox is clicked.
1. Press **Apply** if need be, and **OK**.


## **Folder Structure**
- Swing Frames
  - The Swing Frames folder within our code repository is used to store our UI defining classes.

- UI Elements
  - Contains custom UI elements inserted within Swing Frames

- Data Structures
  - The Data Structures folder within our code repository is used to store classes that allow the transport codification of data.

- IO Pipes
  - IO Pipes are structures which control raw data taken in by an IO System, and pump out structured information a Manager can use.

- IO Systems
  - An IO system is a class which implements the IOSystem interface, and describes how to read and write data from a given source.

- Managers
  - A manager is fed information from an IO Pipe and feeds information to it. They handle things like setting up the data structures for internal use from their files, without worrying about formatting or how it's fed. They act as wrappers for tasks.

- Utilities
  - The utilities package is a catchall for primarily static or helpful classes which contain logic, but do not belong to a different structure, such as the Settings class, which acts as an easy way to read/write from the *config.properties* file.


## **Configuration Files**
- .gitignore
- pom.xml
  - Since this program utilizes Maven, ensure auto-import is enabled to manage the dependencies.

## **Generated Files**
As part of regular use, Paper Back Writer will generate any necessary files that it is missing according to the IOSystems being used. These include...

- *config.properties* : Contains properties, stored information a user may wish to edit, or other things saved between sessions specific to the user experience or the functioning of the program.
- *EventsCSV.csv* : An EXCEL-formatted comma seperated file for event objects.
- *EmployeesCSV.csv* : An EXCEL-formatted comma seperated file for employee objects.
- *Resources.csv* : An EXCEL-formatted comma seperated file for resource objects
- *Products.csv* : An EXCEL-formatted comma seperated file of archived products.
