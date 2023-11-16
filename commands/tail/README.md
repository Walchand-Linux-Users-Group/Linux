# Command
tail

---

## Description
  Print the last 10 lines of each FILE to standard output.  With more than one FILE, precede each with a header giving the file name.

---

## Syntax
```bash
$ tail [options] [file(s)]
```

---

## Options/Flags
- ### -n, --lines=[+]NUM
   Output  the  last  NUM  lines,  instead  of  the  last 10; or use -n +NUM to output starting with line NUM.
    ```bash
    $  tail -n 10 filename
    ```
  
- ### -c, --bytes=[+]NUM
  Output the last NUM bytes; or use -c +NUM to output starting with byte NUM of  each file.
    ```bash
    $  tail -c 20 filename
    ```
     
-  ### -f, --follow[={name|descriptor}]
    Output appended data as the file grows, Absent option argument means 'descriptor'.
    ```bash
    $ tail -f filename
    ```

---

## Author
- Paul Rubin
- Ian Lance Taylor
- Jim Meyering

---

## Copyright
Copyright  ©  2022  Free  Software  Foundation, Inc.  License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>. <br/>
This is free software: you are free to change and redistribute it.  There is NO  WARRANTY, to the extent permitted by law.


---
