Objective
=========
Save last line to a file specified , builds python script as a stack of commands
i.e. pushes statements to the file in append mode

Usage
======
%savef [options]

Options
======

-s: SET new file to write , otherwise would write to temp.py

-f: force create new file ( overwrite original to be used with -s )

-r: use 'raw' input.  By default, the 'processed' history is used,
    so that magics are loaded in their transformed version to valid
    Python.  If this option is given, the raw input as typed as the
    command line is used instead.

It works in modes either you can start a file or write commands,not both simultaneously
This function serves as an extension to %save magic function.It writes to
a file line by line instead of block for rapid development.
Possible Enhancements (1) merge with save



Thanks
======
- Matthias Bussonnier for help with configuration ,bitbucket and PyPi. 
