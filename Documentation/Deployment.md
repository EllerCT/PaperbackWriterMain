# Deployment Manual

## **Description**
Paper Back Writer utilizes Java for its mobility and ease of deployment, and should be as easy as downloading and running.

## Requirements
- A version of Oracle's [Java](https://www.oracle.com/technetwork/java/javase/downloads/index.html) version 11 or later downloaded and installed

## To install
1. Ensure your version of Java is up to date.
  * Remember Java may not always be enabled on your machine, enable it if necessary.
1. Go to the [Latest Release](https://github.com/cteller-bsu/PaperBackWriter/releases)
1. Find that releases version of PaperBackWriter.jar
  * [Example](ImageResources/downloadJar.PNG)
1. Download the .jar to a directory
1. If necessary, ensure that PaperBackWriter has permission to execute. It will also generate files on its first run!

## To start Paper Back Writer
1. Once installed, simply double click the .jar to execute. If this does not work, proceed to step 2.
1. Open the terminal for your OS
1. Navigate the terminal to the folder with PaperBackWriter.jar
1. From the command line, run **java -jar PaperBackWriter.jar**
  * Remember, PaperBackWriter may be named something like **PaperBackWriter_v0.2.0.jar**, most operating systems allow tab completion of the name!

## To close Paper Back Writer
1. Simply exit the 'Paper Back Writer' main menu.

## Troubleshooting
* Ensure Java of at least JDK 11 is installed
* Ensure Java is enabled
* Ensure PaperBackWriter is not located in a protected folder

### My ___ didn't save!
* PaperBackWriter saves many things automatically for ease of use in the background. If the program lacks read-write permissions, it will be unable to save.
* Ensure that you have not entered duplicate information! If an ID, or Pin, or Code exists within the system already, it will NOT automatically replace duplicates. It will instead silently discard duplicate information.

### It won't start
Unfortunately, there are difficulties with reproducibility on certain macOS systems. If you can get other JAR files to run on your system, please get into contact with us with errors displayed, or a system log of the reason it failed to load. We are unable to resolve system-specific difficulties without ready access to such a system.
