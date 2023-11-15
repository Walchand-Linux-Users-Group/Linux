# which
Locate a command.

---

## Description
`which` returns the pathnames of the files (or links) that would be executed in the current environment. It does this by searching the PATH for executable files matching the names of the arguments. It does not canonicalize path names. 

---

## Syntax
### Common usage:
```bash
$ which [command]
```

### With flags:
```bash
$ which [flag] [filename]...
```

---

## Options/Flags
- ### -a:
  #### Print all matching pathnames of each argument.
    ```bash
    $ which -a [filename]...
    ```

---

## Exit Status
- **0** = If all specified commands are found and executable
- **1** = If one or more specified commands are nonexistent or not executable
- **2** = If an invalid option is specified

---
