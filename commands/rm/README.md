# rm
remove files or directories

---

## Description
By default, it does not remove directories.

       If the -I or --interactive=once option is given, and there are more than three  files
       or the -r, -R, or --recursive are given, then rm prompts the user for whether to pro‐
       ceed with the entire operation.  If the response is not affirmative, the entire  com‐
       mand is aborted.

       Otherwise,  if  a  file  is  unwritable,  standard input is a terminal, and the -f or
       --force option is not given, or the -i or --interactive=always option  is  given,  rm
       prompts the user for whether to remove the file.  If the response is not affirmative,
       the file is skipped.

---

## Syntax
```bash
rm [OPTION]... [FILE]...
```
---

## Options/Flags
- ###  ignore nonexistent files and arguments, never prompt.
    ```bash
    $ rm -f, --force
    ```
- ### prompt before every removal.
    ```bash
    $ rm -i
    ```
- ### remove directories and their contents recursively.
    ```bash
    $ rm -r, -R, --recursive
    ```
- ### remove empty directories.
    ```bash
    $ rm -d, --dir
    ```
- ### explain what is being done.
    ```bash
    $ rm -v, --verbose
    ```
- ### To remove a file whose name starts with a '-', for example '-foo', use one  of  these commands:
    ```bash
    $ rm -- -foo
    $ rm ./-foo
    ```
---

## Reporting Bugs
GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
---

## Author
- Richard M. Stallman.
- David MacKenzie.
- Paul Rubin.
- Jim Meyering.

---

## Copyright
Copyright © 2020 Free Software Foundation, Inc.  License GPLv3+: GNU GPL version 3 or
       later <https://gnu.org/licenses/gpl.html>.
       This is free software: you are free to change and redistribute it.  There is NO  WAR‐
       RANTY, to the extent permitted by law.
