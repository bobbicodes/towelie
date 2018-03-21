# Installation

## Dependencies

### Mac:
     
     xcode-select --install
     
If you get an error about the history header not being found, remove the line #include <editline/history.h>.

### Debian Linux:

    sudo apt-get install libedit-dev
    
### Fedora:

    su -c "yum install libedit-dev*"
    
### Windows

You get a free pass this time. Whoop woop...

## To compile:

    cc -std=c99 -Wall prompt.c -ledit -o prompt


