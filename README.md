
# TikiOne Steam Cleaner Plus

Tikione Steam Cleaner is an open source and free software written in Java 8 and helps you to find and remove all games's redistribuable packages downloaded by **Steam** (http://store.steampowered.com). For MS Windows only.、

Support Windows XP/Vista/7/8/8.1/10 with JDK [Click to Download](http://www.java.com/download/).

If you want to Build this Project,Please Download JDK8.

# Download installer

TikiOne Steam Cleaner installer is hosted on [Releases](https://github.com/wbsdty331/TikiOne-steam-Cleaner-Plus/releases).

## Build, test and package [Thanks for Jonathan Lermitage]

TikiOne Steam Cleaner is built with [NetBeans 8](http://netbeans.org) and the latest version of Oracle JDK8.

To build the project:

* load the project with NetBeans and a Java 8 compatible JDK (I use the latest version of NetBeans and Oracle JDK8)
* dependencies should be automatically loaded from the ``./dependencies/`` folder.
* set the working directory to the "dist2" folder. It contains additional configuration files used by base application.

You can now build and run the project.

To package the application, simply merge the "dist" and "dist2" folders.

To bundle a JVM (version 8 or better), copy it into a "jre" folder in the "dist2" folder and launch the NSIS script: it will package TikiOne steam Cleaner with the provided JVM into an EXE installer based on NSIS-Unicode (Nullsoft Scriptable Install System, Unicode version: I use version 2.46-5 from [Google Code](http://code.google.com/p/unsis/downloads/list)).

## Author
* Original Author: Jonathan Lermitage (<jonathan.lermitage@gmail.com>)
* wbsdty331 (<wbsdty331@126.com>)

## Contact

You can ask questions, share ideas or insult me by email (<wbsdty331@126.com>)

## History
[changelog](https://github.com/wbsdty331/TikiOne-steam-Cleaner-Plus/blob/master/CHANGELOG.md).

## License

LGPL License
