# dpkg-deb

---

## Description


---

## Syntax
```bash
dpkg-deb [OPTIONS/FlAGS] [COMMAND]
```
---

## Options/Flags
- ###  Display information about a package.
    ```bash
    $ dpkg-deb --info [path/to/file.deb]
    ```
- ### Display the package's name and version on one line.
    ```bash
    $ dpkg-deb --show [path/to/file.deb]
    ```
- ### Create a package from a specified directory.
    ```bash
    $ dpkg-deb --build [[path/to/directory]
    ```
- ### List the package contents.
    ```bash
    $ dpkg-deb --contents [path/to/file.deb]
    ```

---

## Exit Status
- The requested action was succesfully performed.
- Fatal or unrecoverable error due to invalid command-line usage, or interaction with the system, such as accessses to the database, memory allocaton, etc.

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
