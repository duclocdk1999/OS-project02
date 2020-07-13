# OS-project02-simpleShell
## this project is implemented to simulate how a shell works.
## requirement:
    Linux operating system
    gcc                 # could be isntalled by command: sudo apt-get install gcc
    make                # could be installed by command: sudo apt-get install make
## Open terminal, type:
    make all
    ./main
#
## The console will display this term: oppa:$
#
## Type a command line, for example: 
    python3 --version
#
## To check input-redirection, type:
    ls -l > output.txt
#   
## To check output-redirection, create and write a list of number to input.txt, then type:
    sort < input.txt
    # example of input.txt:
        1
        9
        7
        5
        2
        4
        6
        8
        3
    # output on terminal should be at this form:
        1
        2
        3
        4
        5
        6
        7
        8
        9
#
## To check pipe function, type:
    ls                  # this will show on screen something like: main.c main makefile README.txt
    ls | grep main      # this will show on screen something like: main.c main
#
## To check history command line, type:
    !!                  # this will execute your previous command line (which is saved in .history)
