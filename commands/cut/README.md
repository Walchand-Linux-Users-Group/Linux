# cut
cut

---

## Description
- Used to cut out the sections from each line of files and writing the result to standard output.
- It can be used to cut parts of a line by byte position, character and field.

---

## Syntax
```bash
cut [OPTION]... [FILE]...
```

---

## Options/Flags
- ### -b: 
  To extract the specific bytes, you need to follow -b option with the list of byte numbers separated by comma.
  List without ranges:
    ```bash
    $ cut -b 1,2,3 myfile.txt  
    ```   
  List with ranges:
    ```bash
    $ cut -b 1-3,5-7 myfile.txt
    ```
  It uses a special form for selecting bytes from beginning upto the end of the line:  
  In this, 1- indicate from 1st byte to end byte of a line.
    ```bash
    $ cut -b 1- state.txt 
    ```
  In this, -3 indicate from 1st byte to 3rd byte of a line.
    ```bash
    $ cut -b -3 state.txt 
    ```
- ### -c: 
  To cut by character use the -c option
  List without ranges:
    ```bash
    $ cut -c 2,5,7 state.txt 
    ```
  List with ranges:
    ```bash
    $ cut -c 1-3,5-7 myfile.txt 
    ```
  Cut uses a special form for selecting characters from beginning upto the end of the line:
  In this, 1- indicate from 1st character to end character of a line.
    ```bash
    $ cut -c 1- state.txt
    ```
  In this, -5 indicate from 1st character to 5th character of a line:
    ```bash
    $ cut -b -5 state.txt 
    ```
---

## Exit Status 
- **0** = Successful execution
- **non-zero value** = Error Occurrence

---
uu