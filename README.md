# Dependencies:

On Mac the editline library comes with Command Line Tools. Refer to buildyourownlisp.com if you have problems.

On Debian Linux you can install editline with:

    sudo apt-get install libedit-dev
    
On Fedora you can use the command:

    su -c "yum install libedit-dev*"
    
Windows gets a free pass this time. Whoop woop...

To compile:

    cc -std=c99 -Wall prompt.c -ledit -o prompt


