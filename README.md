# c INTRODUCTION
 SAY HELLO WORLD USING C


STEP 1:
 installing vs code for IDE:
 donot make changes, keep default settings while installation.
 installing compiler (MinGW-gcc) for windows:
 1) go to site:  https://sourceforge.net/projects/mingw/
 2) download the application from given link (mingw-get-setup)
 3) then it will open the mingw installation manager setup tool.
 4) click on install and continue with the default path.
 5) it will download some small files and then click on finish on comlplision.
 6) Then Mingw installation manager will open, click on basic setup if not selected on left side.
 7) now tick mark the Mingw32-gcc-g++ (bin) for C++ compiler and mingw32-gcc-objc (bin) for c compiler by right clicking it and select mark for installation.
 8) Now go to tool bar at the top and select installation.
 9) inside it click on update catalogue.
 10) Update package catalogue will start. close it when done.
 11) to check whether gcc is installed, go to cmd
 12) type gcc++ --version.
 13) if it shows the version, your compiler is successfully installed, else there is some error.
 14) now open file explorer. go to dick c, then you will find your mingw folder. If not, go to program files and find mingw folger.
 15) Go to mingw folder and go to bin. Copy the link from address bar.
 16) now right click on my PC on desktop, go to advanced system settings.
 17) go to environment variables and click on path.
 18) Click on new and paste the path. Click ok and close it.
STEP 2:
 now open vs code and download c/c++ extension.
STEP 3:
 now make a new page with extension .c on any folder you wish.
 make a new main function
 and print hello world by syntax-"printf("Hello world\n");"
 write another line on top of main as include<stdio>.
 now open new terminal and write gcc.
 if it shows no input files, you are on right path.
 now write gcc <filename> and enter.
 now you will find a new file on the file bar as a.exe.
 now run the command : .\a.exe
 you will get output as hello world.
