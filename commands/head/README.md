# Command
head

---

## Description
Print  the  first  10  lines  of  each  FILE to standard output.  With more than one FILE, precede each with a header giving the file name.

---

## Syntax
```bash
$ head [OPTION]... [FILE]...
```

---

## Options/Flags
- ### -n, --lines=[-]NUM
   Print the first NUM lines instead of the first 10; with the leading '-', print all but the last NUM lines of each file.
    ```bash
    $ head -n 10 filename
    ```

- ### -c, --bytes=[-]NUM
  print the first NUM bytes of each file; with the leading '-',  print  all  but  the last NUM bytes of each file.
    ```bash
    $ head -c 20 filename
    ```
    
- ### -q, --quiet, --silent
  Never print headers giving file names.
    ```bash
    $  head -q file1 file2
    ```
---

## Author
- David MacKenzie
- Jim Meyering

---

## Copyright
   Copyright © 2022 Free Software Foundation, Inc.  License GPLv3+:  GNU  GPL  version 3 or later <https://gnu.org/licenses/gpl.html>. This  is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.

---

