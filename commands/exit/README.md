# exit
Exit the shell.

---

## Description
The 'exit' command is used to exit the current shell or terminal session.

---

## Syntax
```bash
exit [n]
```

---

## Options/Flags
- ###  --help : Print a short help text and exit.
    ```bash
    $ exit --help
    ```

---

## Note
### The exit status(n) is a numeric value that indicates the success or failure of the last executed command. A value of 0 usually means success, and any other value indicates an error.
- #### If 'n' is omitted, it will exit the current shell or terminal session and the exit status is that of the last command executed. 
- #### If you provide an optional exit status 'n', it will exit the shell with that status.

---

## Exit Status
- **0** = Success
- **!0** = Failure

---
