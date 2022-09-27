NAME:
mkdir :- To make directory

SYNTAX:
mkdir [options...][directories...]

COMMANDS:
=====================================================================================

-version:
IT DISPLAYS THE VERSION NUMBER.

SYNTAX:
mkdir --version



for e.g. 

=====================================================================================
mkdir (GNU coreutils) 8.32

Copyright (C) 2020 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
=====================================================================================
-help 
It show the information about the mkdir command

SYNTAX
mkdir --help

for eg --help command will give


=====================================================================================
By using mkdir -- help

Output on Terminal


Usage: mkdir [OPTION]... DIRECTORY...
Create the DIRECTORY(ies), if they do not already exist.

Mandatory arguments to long options are mandatory for short options too.
  -m, --mode=MODE   set file mode (as in chmod), not a=rwx - umask
  -p, --parents     no error if existing, make parent directories as needed
  -v, --verbose     print a message for each created directory
  -Z                   set SELinux security context of each created directory
                         to the default type
      --context[=CTX]  like -Z, or if CTX is specified then set the SELinux
                         or SMACK security context to CTX
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Full documentation <https://www.gnu.org/software/coreutils/mkdir>
or available locally via: info '(coreutils) mkdir invocation'

=====================================================================================


-v or verbose:


This will give the message of the file has been created.


SYNTAX
mkdir -v [directories]

for eg.
mkdir -v first second third

Output on terminal.

mkdir: created directory 'first'
mkdir: created directory 'second'
mkdir: created directory 'third'


=====================================================================================


-p: A flag which enables the command to create parent directories as necessary.
    If the directories exist, no error is specified. 

SYNTAX:
mkdir -p [directories]

=====================================================================================
-m: This flag will help in setting up the file mode.


SYNTAX:
mkdir -m a=rwx [directories]

=====================================================================================