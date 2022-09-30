# tac
Reverse of concatenation

---

## Description
It is used to concatenate specific files in reversed order.
We can view the content of the file in reverse order if lines.

---

## Syntax
```bash
tac [FILE]
```
---

## Options/Flags
- ###  Attach the separator before instead of after.
    ```bash
    $ tac -b [FILE]
    ```
- ### Interpret the seperator as a regular expression.
    ```bash
    $ tac -r [FILE]
    ```
- ### Use STRING as the separator instead of newline
    ```bash
    $ tac -s=STRING [FILE]
    ```
- ### For Help
    ```bash
    $ tac --help
    ```
- ### Output Version Information.
    ```bash
    $ tac --version
    ```

---

## Exit Status
- **0** = OK
---

## Author
- Jay Lepreau and David MacKenzie

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
