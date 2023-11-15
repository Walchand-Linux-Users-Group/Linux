# clear
Clear the terminal screen.

---

## Description
`clear` clears your terminal's screen including the terminal's scrollback buffer.

---

## Syntax
```bash
$ clear [options]
```

---

## Options/Flags
- ### -V:
  Reports the version of ncurses used in this program and exits.
    ```bash
    $ clear -V
    ```
- ### -x:
  Do not attempt to clear the terminal's scrollback buffer using the extended “E3” capability.
    ```bash
    $ clear -x
    ```

---

## Exit Status
- **0**: The command executed successfully.
- **Non-zero:** = An error occurred.

---


