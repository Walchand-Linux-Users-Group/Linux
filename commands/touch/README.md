# touch 
touch - change file timestamps

---

## Description
 Update the access and modification times of each FILE to the current time.
 A FILE argument that does not exist is created  empty, unless -c or -h is supplied.

---

## Syntax
```bash
touch [OPTION] FILE
```
---

## Options/Flags
- ###  Change only the access time
    ```bash
    $ touch -a [FILE]
    ```
- ###  Do not create any files
    ```bash
    $ touch -c [FILE]
    ```

    `OR`

    ```bash
    $ touch --no-create [FILE]
    ```

- ###  Parse STRING and use it instead of current time
    ```bash
    $ touch -d=STRING [FILE]
    ```

    `OR`

     ```bash
    $ touch --date=STRING [FILE]
    ```
- ###  Change only the modification time
    ```bash
    $ touch -m [FILE]
    ```
- ###  Use this file's times instead of current time
    ```bash
    $ touch -r=FILE [FILE]
    ```

     `OR`

     ```bash
    $ touch --reference=FILE [FILE]
    ```
- ###  Use [[CC]YY]MMDDhhmm[.ss] instead of current time
    ```bash
    $ touch -t STAMP [FILE]
    ```
- ###  Display this help and exit
    ```bash
    $ touch --help
    ```
- ###  Output version information and exit
    ```bash
    $ touch --version
    ```
- ###  Note that the -d and -t options accept different time-date formats.

  
---

## REPORTING BUGS  
- GNU coreutils online help:
       <https://www.gnu.org/software/coreutils/>
- Report any translation bugs to
       <https://translationproject.org/team/>

---

## Author
-  Paul Rubin
-  Arnold Robbins
-  Jim Kingdon
-  David MacKenzie
-  Randy Smith

---

## Copyright
 Copyright © 2020 Free Software Foundation, Inc.  License GPLv3+:
 GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
 This is free software: you are free to change and redistribute
 it.  There is NO WARRANTY, to the extent permitted by law.