由于作者已经停止更新，经作者同意，本人接手了开发.

Tikione Steam Cleaner Plus
Download installer
TikiOne Steam Cleaner installer is hosted on GitHub releases.

Build, test and package
TikiOne Steam Cleaner is built with NetBeans and the latest version of Oracle JDK8.

To build the project:

load the project with NetBeans and a Java 8 compatible JDK (I use the latest version of NetBeans and Oracle JDK8)
dependencies should be automatically loaded from the ./dependencies/ folder.
set the working directory to the "dist2" folder. It contains additional configuration files used by base application.
You can now build and run the project.

To package the application, simply merge the "dist" and "dist2" folders.

To bundle a JVM (version 8 or better), copy it into a "jre" folder in the "dist2" folder and launch the NSIS script: it will package TikiOne steam Cleaner with the provided JVM into an EXE installer based on NSIS-Unicode (Nullsoft Scriptable Install System, Unicode version: I use version 2.46-5 from Google Code).

Author
Jonathan Lermitage (jonathan.lermitage@gmail.com)
wbsdty331 (wbsdty331@gmail.com)
Contact
You can ask questions, share ideas or insult me by email (jonathan.lermitage@gmail.com) or discuss via Twitter.

中文问题请发送到(wbsdty331@126.com)，或者Twitter@我.

Contributors
Dmitry Bolotov (Дмитрий Болотов): Russian and Ukrainian translations
Boris Klein: German translation
Ulli Kunz: German translation
Hauwertlhaufn: German translation
Zsolt Brechler: Hungarian translation
Piotr Swat: Polish translation
Pedro Henrique Viegas Diniz: Portuguese translation
"ZoSH": Spanish translation
wbsdty331 : Simplified Chinese translation
Petr Kudlička: redist detection improvements
Brian Huqueriza: redist detection improvements
Antti Mieskolainen: redist detection improvements, GOG and Origin support
Members of the CanardPC forum, for their support and cheerfulness
History
I'm working on this software since Janurary 2012. Here is the full changelog.

License
LGPL License