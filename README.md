# My C Programming Setup
This is just my new c programming setup, which is setup with VSCode. It's done in a way that allows me to efficiently and productively write C code by having command prompt on one side of the screen while having VSCode on the other and I can use keyboard shortcuts to switch back and forth between them and run a build script from within my current working directory.

Cloning this anywhere on your machine and adding its path to your PATH environment variable will give you access to run the build.bat script which runs the cbuilder.py file. It uses the cl command that comes built in with visual studio. My command prompt's shortcut uses the following command when starting up

`%windir%\system32\cmd.exe /k C:\cbuilder\start.bat`

This command will execute every time you open cmd using the shortcut and it will execute a script installed by visual studio when you download the vs express package, and it will setup your PATH var to give you access to windows command line compiler called 'cl'.

Running build.bat will handle running the 'cl' command for you.