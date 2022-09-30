# pstree 
 Shows the running process as tree.


---

## Description
 pstree command in Linux that shows the running processes as a tree which is a more convenient way to display the processes hierarchy and makes the output more visually appealing.

---

## Syntax
```bash
pstree [options] {pid or username}
```
---

## Options/Flags
- ###  To display process tree
    ```bash
    $ pstree
    ```
- ###  To include command line arguments in output
    ```bash
    $ pstree -a
    ```
- ###  To display PIDs
    ```bash
    $ pstree -p
    ```
- ###  To force pstree to expand identical subtrees in output.
    ```bash
    $ pstree -c
    ```
- ###  To sort processes wrt PIDs
    ```bash
    $ pstree -n
    ```
- ###  To see who is the owner/user of a process
    ```bash
    $ pstree -u
    ```
- ###  To highlight the current process or any other process
    ```bash
    $ pstree -h
    ```
- ###  To show process group IDs in output
    ```bash
    $ pstree -g
    ```
- ###  To make pstree display process tree specific to a user.
    ```bash
    $ pstree {username}
    ```
- ###  To display version information
    ```bash
    $ pstree -v
    ```  
---

## Author
 Werner Almesberger
 Craig Small

---

## Copyright
 Copyright © 2020 Free Software Foundation, Inc.  License GPLv3+:
 GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
 This is free software: you are free to change and redistribute
 it.  There is NO WARRANTY, to the extent permitted by law.