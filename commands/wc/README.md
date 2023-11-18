# wc
Word Count

---

## Description
- Used to find out number of lines, word count, byte and characters count in the files specified in the file arguments.
- By default it displays four-columnar output, First column shows number of lines present in a file specified, second column shows number of words present in the file, third column shows number of characters present in file and fourth column itself is the file name which are given as argument.

---

## Syntax
```bash
wc [OPTION]... [FILE]...
```

---

## Options/Flags
- ### -l: 
  This option prints the number of lines present in a file.
    ```bash
    $ wc -l myfile.txt 
    ```   
- ### -w: 
  This option prints the number of words present in a file. 
    ```bash
    $ wc -w myfile.txt
    ```
- ### -c: 
  This option displays count of bytes present in a file.
    ```bash
    $ wc -c myfile.txt
    ```
- ###  -m: 
  Using -m option ‘wc’ command displays count of characters from a file.
    ```bash
    $ wc -m myfile.txt
    ```
- ###  -L: 
  Used to print out the length of longest (number of characters) line in a file.
    ```bash
    $ wc -L myfile.txt
    ```
---

## Exit Status 
- **0** = Successful execution
- **0 < value** = Error Occurrence

---

## Author
- Joe Ossanna

---