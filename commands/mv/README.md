# Command
mv
move files from source to directory
---

## Description
Rename source to destination, or move source to directory

---

## Syntax
```bash
mv [OPTION]...[-T]SOURCE DEST
mv [OPTION]...[-T]SOURCE... DIRECTORY
mv [OPTION]...-t DIRECTORY SOURCE
```

---

## Options/Flags
- mv -b = make a backup of each existing file.
    ```bash
    $ mv -b a.txt b.txt
    ```
- mv -f = do not promt before overwriting.
    ```bash
    $ mv -f a.txt b.txt
    ```
- mv -n = do not overwrite an existing file.
    ```bash
    $ mv -n a.txt b.txt
    ```
---
## Author
- Mike Parker,David MacKenzie
- Jim Meyering.

##Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
---