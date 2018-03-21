# Installation:

Towelie is written in C, so it can run smoothly on really crappy, knotted, or strung-out towels, with minimal headaches and good resistance to fraying. Towelie doesn't care what kind of material you're running, as long as it's still got most of its fibers.

## Mac:
     
     xcode-select --install
     
If you get an error about the history header not being found, remove the line #include <editline/history.h>.

## Ubuntu/Debian Linux:

    sudo apt-get install build-essential
    sudo apt-get install libedit-dev
    
## Fedora:

    su -c "yum install libedit-dev*"
    su -c "yum groupinstall development-tools"
    
## Windows

Download and installing MinGW. If you use the installer at some point it may present you with a list of possible packages. Make sure you pick at least mingw32-base and msys-base. Once installed you need to add the compiler and other programs to your system PATH variable. To do this follow these instructions appending the value ;C:\MinGW\bin to the variable called PATH. You can create this variable if it doesn't exist. You may need to restart cmd.exe for the changes to take effect. This will allow you to run a compiler from the command line cmd.exe. It will also install other programs which make cmd.exe act like a Unix command line.

# Now compile your fibers:

    cc -std=c99 -Wall prompt.c -ledit -o towel

# Spin up a Towelie REPL:

    towel
    
# You're a towel!
