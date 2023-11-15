## which

Find the location of the executable file associated with the command.

---

## Description

Which command in Linux is a command which is used to locate the executable file associated with the given command by searching it in the path environment variable.

---

## Syntax

 ```bash
 which [filename1] [filename2] ...
 ```
---

## Options/Flags

### -a
Used to display all the occurrences of the file.
```bash
which -a [filename]
```

### -v
Used to display more verbose output.
```bash
which -v [command]
```

## Exit Status

- **0** = If all specified commands are found and executable.

- **1** = If one or more specified commands is nonexistent or not executable

- **2** = If an invalid option is specified.

---

## Copyright

Its copyright is held by the contributors to the GNU Core Utilities project, and it is distributed under the terms of the GPL

