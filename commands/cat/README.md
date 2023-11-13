# cat

Open a file in the terminal.

---

## Description
- It is used to print the content of a file onto the standard output stream.
- It is also allows us to write some texts into a file.

---

## Syntax
```bash
    $ cat {filename}
```

---

## Options/Flags
- ###  >
    Create a file and add data to it
    ```bash
    $ cat > {name}
    ```
- ### >>
    Write in an already existing file
    ```bash
    $ cat >> {filename}
    ```
- ### {file1} > {file2}
    Copy contents from one file to another
    ```bash
    $ cat {file1} > {file2}
    ```
- ### {file1} >> {file2}
    Append the contents of one file to the end of another file
    ```bash
    $ cat {file1} >> {file2}
    ```
- ### -E
    Highlight the end of the line.
    ```bash
    $ cat -E {filename}
    ```
- ### -n
    View the contents of a file preceding with line numbers
    ```bash
    $ cat -n {filename}
    ```
- ### -t
    Show TAB separated lines
    ```bash
    $ cat -t [file]
    ```
- ### -s
    Remove blank lines
    ```bash
    $ cat -s [file]
    ```
- ### -s
    Suppress repeated empty lines in output
    ```bash
    $ cat -s {filename}
    ```
- ### --
    Open dashed files
    ```bash
    $ cat -- {filename}
    ```
- ### --help 
    Display this help and exit
    ```bash
    $ cat --help
    ```
- ### --version
    Output version information and exit
    ```bash
    $ cat --version
    ```

## Other functionalities:

- ### Display contents of multiple files
    ```bash
    $ cat [file1] [file2]
    ```
- ### Redirect contents of multiple files
    ```bash
    $ cat [file1] [file2] > [file3]
    ```
- ### Display the contents in reverse order
    ```bash
    $ tac [file]
    ```
- ### More and less options (manage large files)
    ```bash
    $ cat [file] | more
    $ cat [file] | less
    ```
---

## Author
-  Ken Thompson
-  Dennis Ritchie

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
