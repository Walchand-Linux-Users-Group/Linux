# Command

shred

---

## Description
Overwrite the specified FILE(s) repeatedly, in order to make it harder for even very expensive hardware probing to recover the data.

Mandatory arguments to long options are mandatory for short options too.

---

## Syntax
```bash
$ shred [OPTION]... FILE...
```
---

## Options/Flags
- ###  change permissions to allow writing if necessary
    ```bash
    $ shred -f, --force
    ```
- ### overwrite N times instead of the default (3)
    ```bash
    $ shred -n, --iterations=N
    ```
- ### truncate and remove file after overwriting
    ```bash
    $ shred -u, --remove
    ```
- ### do not round file sizes up to the next full block; this is the default for non-regular files
    ```bash
    $ shred -x, --exact
    ```


---

## Reporting Bugs
Report shred bugs to bug-coreutils@gnu.org
GNU coreutils home page: <http://www.gnu.org/software/coreutils/>
General help using GNU software: <http://www.gnu.org/gethelp/>
Report shred translation bugs to <http://translationproject.org/team/>

---

## Author

- Colin Plumb
---

## Copyright
Copyright Â© 2010 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.
