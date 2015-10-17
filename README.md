
# TikiOne Steam Cleaner Plus

Tikione Steam Cleaner is an open source and free software written in Java 8 and helps you to find and remove all games's redistribuable packages downloaded by **Steam** (http://store.steampowered.com). For MS Windows only.

# Download installer

TikiOne Steam Cleaner installer is hosted on [Releases](https://github.com/wbsdty331/TikiOne-steam-Cleaner-Plus/releases).


## Build, test and package

TikiOne Steam Cleaner is built with [NetBeans](http://netbeans.org) and the latest version of Oracle JDK8.

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

You can ask questions, share ideas or insult me by email (<jonathan.lermitage@gmail.com>) or discuss via [Twitter](https://twitter.com/JLermitage).

中文用户请发送到(<wbsdty331@126.com>)，最好说明产生问题的时间，系统平台和截图，以便于核实。

## Contributors
* Dmitry Bolotov (Дмитрий Болотов): Russian and Ukrainian translations
* Boris Klein: German translation
* Ulli Kunz: German translation
* Hauwertlhaufn: German translation
* Zsolt Brechler: Hungarian translation
* Piotr Swat: Polish translation
* wbsdty331: Simplified Chinese translation
* Pedro Henrique Viegas Diniz: Portuguese translation
* "ZoSH": Spanish translation
* Petr Kudlička: redist detection improvements
* Brian Huqueriza: redist detection improvements
* Antti Mieskolainen: redist detection improvements, GOG and Origin support
* Members of the [CanardPC forum](http://forum.canardpc.com), for their support and cheerfulness

## History
[changelog](https://github.com/jonathanlermitage/tikione-steam-cleaner/blob/master/CHANGELOG.md).

## License

LGPL License
