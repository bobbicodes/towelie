#deps

On Mac the editline library comes with Command Line Tools.
On Linux you can install editline with
    sudo apt-get install libedit-dev
    On Fedora you can use the command
        su -c "yum install libedit-dev*"

To compile:

    cc -std=c99 -Wall prompt.c -ledit -o prompt


