# watch
Execute a program periodically.

---

## Description
The watch command is used for running user-defined commands at regular intervals.
By default, the specified command will run every 2 seconds and watch will run until interrupted.

---

## Syntax
```bash
$ watch [option] [command]
```

---

## Options/Flags
- ###  -n:
  Allows you to specify the interval between output updates.
    ```bash
    $ watch -n [command]
    ```
- ### -d:
  Highlights the differences between output updates.
    ```bash
    $ watch -d [command]
    ```
- ### -g:
  Exits the watch command when the output of the user-defined command changes.
    ```bash
    $ watch -g [command]
    ```
- ### -t:
  Removes the header showing the interval, command, current time and date.
    ```bash
    $ watch -t [command]
    ```
- ### -b:
  Plays a sound alert (beep) if the command exits with an error.
    ```bash
    $ watch -b [command]
    ```
- ### -p:
  Attempts to run the command after the exact number of seconds defined by the --interval option.
    ```bash
    $ watch -p [command]
    ```
- ### -e:
  Stops output updates on an error and exits the command after a key press.
    ```bash
    $ watch -e [command]
    ```
- ### -c:
  Interprets ANSI color and style sequences.
    ```bash
    $ watch -c [command]
    ```
- ### -x:
  Passes the user-defined command to exec, reducing the need for extra quoting.
    ```bash
    $ watch -x [command]
    ```
- ### -w:
  Turns off line wrapping and truncates long lines instead.
    ```bash
    $ watch -w [command]
    ```
- ### -h:
  Displays help text and exits.
    ```bash
    $ watch -h
    ```
- ### -v:
  Displays version information and exits.
    ```bash
    $ watch -v
    ```   

---

## Exit Status
- **0**: The command executed successfully.
- **1**: An error occurred during the execution of the command.

---

## Author
- Tony Rems
- Rob Warren

---

## Copyright
- The `watch` command is part of the procps-ng package.
- Copyright © 2012-2021 Free Software Foundation, Inc.
- License GPLv3+: GNU GPL version 3 or later.
- This is free software; you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.

---
