# history

Display the history of commands executed.

---


## Description
It is a Linux command that displays a list of previously executed commands in the current shell session,
providing a chronological record of command history for reference and reuse.

---


## Syntax

```bash
history [options] 
```   
---


## Options/Flags
- ###  -c
    Clear the history list by deleting all of the entries.
    ```bash
    $ history -c
    ```
- ###  -d
   Delete the history entry at offset OFFSET.
    ```bash
    $ history -d OFFSET
    ```
- ###  -a
   Append history lines from this session to the history file.
    ```bash
    $ history –a
    ```
- ###  -n
    Read all history lines not already read from the history file.
    ```bash
    $ history -n
    ```
- ###  -r
    Read the history file and append the contents to the history list.
    ```bash
    $ history -r
    ```
- ###  -w
    Write the current history to the history file and append it to the history list
    ```bash
    $ history -w
    ```

---


## Exit Status

- **0** = The command executed successfully.
  
---


## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.<br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
