# rename
rename files

---

## Description
It is used to rename files.
We can change one or multiple filename at a time

---

## Syntax
```bash
rename [foo] [bar] [*]
```
---

## Options/Flags
- ###  Rename without performing them.
    ```bash
    $ rename -vn [foo] [bar] [*]
    ```
- ### Rename without overwriting existing files
    ```bash
    $ rename -o [foo] [bar] [*]
    ```
- ### Prepend "foo" to all filenames in current directory.
    ```bash
    $ rename [''] ['foo'] [*]
    ```
- ### Change file extensions.
    ```bash
    $ rename [.pdf] [.txt] [*.pdf]
    ```

---

## Exit Status
- **0** = OK
- **1** = All Failed
- **2** = Some Failed
- **4** = Nothing renamed
- **64** = Unanticipated Error Occcured
---

## Author
- Ravi Jha

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
