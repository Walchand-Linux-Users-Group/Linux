# rmdir
Remove empty directories.

---

## Description
Remove the DIRECTORY(ies), if they are empty.

---

## Syntax
```bash
$ rmdir [option] [directory]
```

---

## Options/Flags
- ### --ignore-fail-on-non-empty:
  #### Ignore each failure that is solely because a directory is non-empty.
    ```bash
    $ rmdir --ignore-fail-on-non-empty [directory_name]
    ```
- ### -p, --parents:
  #### Remove DIRECTORY and its ancestors.
    ```bash
    $ rmdir -p [directory_name]
    ```
- ### -v, --verbose:
  #### Output a diagnostic for every directory processed.
    ```bash
    $ rmdir -v [directory_name]
    ```
- ### --help:
  #### Print a short help text and exit.
    ```bash
    $ rmdir --help
    ```
- ### --version:
  #### Output version information and exit.
    ```bash
    $ rmdir --version
    ```

---

## Exit Status
- **0** = The command executed successfully and all requested changes were made.
- **1** = An error occurred or the directory was not empty (if --ignore-fail-on-non-empty is not used).

---


## Author
- Ken Thompson
- Dennis Ritchie

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. <br/>
License GPLv3+: GNU GPL version 3 or later. <br/>
https://gnu.org/licenses/gpl.html <br/>
This is free software: you are free to change and redistribute it. <br/>
There is NO WARRANTY, to the extent permitted by law. <br/>

---
