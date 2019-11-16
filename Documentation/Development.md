# Development Manual

## **Description**

This development manual will explain tech aspects of our system, required technologies to replicate the development environment,
folder structure in our code repositories, important files, and other important aspects of development.


## **Technologies Required**
These are the technologies our group have used to create our program. For our project structure language, level 11 is utilized.
- Intellij
- JDK 11
- Maven/Apache Commons
- Git
- Intellij GUI Designer


## **Folder Structure**
- Swing Frames
  
  - The Swing Frames folder within our code repository is used to store our UI defining classes.

- Data Structures
  - The Data Structures folder within our code repository is used to store classes that utilize geters and seters
    to create and manage important aspects of our program such as Employee, Events, and PIN Number. 

- I_O Pipes

    - Input/Output pipes folder within our code repository is used to write and format our outputs files for employees and events.

- I_O Systems
  - I_O systems is a folder to store classes that create and store our csv files within our system.

- Managers
  - Managers is a folder used to modify and store logic for Employee, Events, and Time Clock. These managers are used for our
    controller classes communicate with the UI.


## **Configuration Files**
- .gitignore
- pom.xml
  - Since this program utilizes Maven, ensure auto-import is enabled to manage the dependencies.
