# echo
echo - display a line of text

---

## Description
Echo the STRING(s) to standard output.

---

## Syntax
```bash
echo [SHORT-OPTION] [STRING]
echo LONG-OPTION
```
---

## Options/Flags
- ###  Do not output the trailing newline.
    ```bash
    $ echo -n [STRING]
    ```
- ###  Enable interpretation of backslash escapes.
    ```bash
    $ echo -e [STRING]
    ```
- ###  Disable interpretation of backslash escapes (default)
    ```bash
    $ echo -E [STRING]
    ```
- ###  Display this help and exit
    ```bash
    $ echo --help
    ```
- ###  output version information and exit
    ```bash
    $ echo --version
    ```
- ###  If -e is in effect, the following sequences are recognized:
        ```bash
       \\     backslash

       \a     alert (BEL)

       \b     backspace

       \c     produce no further output

       \e     escape

       \f     form feed

       \n     new line

       \r     carriage return

       \t     horizontal tab

       \v     vertical tab
        ```
---

## Author
- Brian Fox
- Chet Ramey

---

## REPORTING BUGS  
- GNU coreutils online help:
  <https://www.gnu.org/software/coreutils/>
- Report any translation bugs to
  <https://translationproject.org/team/>

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
