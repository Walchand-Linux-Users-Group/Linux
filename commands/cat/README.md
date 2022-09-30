# cat
    Open a file in terminal

---

## Description
    Displays the contents of a file

---

## Syntax
```bash
    $ cat {filename}
```

---

## Options/Flags
- ###  >
    To create a file and add data to it
     unknown:
    ```bash
    $ cat > {name}
    ```
- ### -n
    To view contents of a file preceding with line numbers
    ```bash
    $ cat -n {filename}
    ```
- ### {file1} > {file2}
    copy contents from one file to another
    ```bash
    $ cat {file1} > {file2}
    ```
- ### -s
    suppress repeated empty lines in output
    ```bash
    $ cat -s {filename}
    ```
- ### {file1}>>{file2}
    append the contents of one file to the end of another file. 
    ```bash
    $ cat {file1}>>{file2}
    ```
- ### -E
    highlight the end of line. 
    ```bash
    $ cat -E {filename}
    ```

- ### --
    open dashed files. 
    ```bash
    $ cat -- {filename}
    ```
- ### >>
    write in an already existing file. 
    ```bash
    $ cat >> {filename}
    ```
- ### --help 
    display this help and exit
    ```bash
    $ cat --help
    ```
- ### --version
    output version information and exit
    ```bash
    $ cat --version
    ```
### Main AUTHOR
       Written by  Ken Thompson, Dennis Ritchie.

