## whereis

Locate the binary, source, and manual page files for a command.

---

## Description

- `whereis` locates the binary, source, and manual files for the specified command names. The supplied names are first stripped of leading pathname components. Prefixes of s. resulting from the use of source code control are also dealt with. `whereis` then attempts to locate the desired program in the standard Linux places, and in the places specified by _**$PATH**_ and _**$MANPATH**_.
- The search restrictions (options -b, -m, and -s) are cumulative and apply to the subsequent name patterns on the command line. Any new search restriction resets the search mask.

---

## Syntax

```bash 
$ whereis [options] filename...
```

---

## Options/Flags

- ### -b
  Search for binaries.
  ```bash
  $ whereis -b filename
  ```

- ### -m
  Search for manuals.
  ```bash
  $ whereis -m filename
  ```

- ### -s
  Search for sources.
  ```bash
  $ whereis -s filename
  ```

- ### -u
  Only show the command names that have unusual entries. A command is said to be unusual if it does not have just one entry of each explicitly requested type. Thus `whereis -m -u *` asks for those files in the current directory which have no documentation file, or more than one.
  ```bash
  $ whereis -u filename
  ```
  
- ###  -B list
  Limit the places where `whereis` searches for binaries, by a whitespace-separated list of directories.
  ```bash
  $ whereis -B directory_list filename
  ```

- ### -M list
  Limit the places where `whereis` searches for manuals and documentation in Info format, by a whitespace-separated list of directories.
  ```bash
  $ whereis -M directory_list filename
  ```

- ###   -S list
  Limit the places where `whereis` searches for sources, by a whitespace-separated list of directories.
  ```bash
  $ whereis -S directory_list filename
  ```

- ### -f
  Terminates the directory list and signals the start of filenames. It must be used when any of the -B, -M, or -S options is used.
   ```bash
  $ whereis -f -B directory_list -M directory_list -S directory_list filename
  ```

- ###  -l
  Output the list of effective lookup paths that `whereis` is using. When none of -B, -M, or -S is specified, the option will output the hard-coded paths that the command was able to find on the system.
   ```bash
  $ whereis -l
  ```

- ### -h, --help
  Display help text and exit.
  ```bash
  $ whereis -h
  ```

- ### -V, --version
  Print version and exit.
  ```bash
  $ whereis -V
  ```

---

## Author
- Michael Haardt
---

## Copyright

Copyright © [Year] Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.<br/>
This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.

