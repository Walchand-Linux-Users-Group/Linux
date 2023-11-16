# pidof
process id of

---

## Description
It finds the process id's (pids) of the named running process.
It prints those id's on the standard input.


---

## Syntax
```bash
pidof [options] program1 program2 .... programN
```
---

## Flags
- ###  Single shot - Instructs the program to display only 1 pid.
    ```bash
    $ pidof -s program_name
    ```
- ### Excludes a process with a given pid from the command output.
    ```bash
    $ pidof -o pid program_name
    ```
- ### Returns the pids of the processes that are running with the same root directory.
    ```bash
    $ pidof -c pid program_name
    ```
- ### Quiet mode, suppress any output and only sets the exit status accordingly.
    ```bash
    $ pidof -q process_name
    ```
- ### Scripts too - this causes the program to also return process id's of shells running the named scripts.
    ```bash
    $ pidof -x 
    ```
- ### Tells pidof to try to detect the sleeping and zombie processes, at the risk of failing or hanging.
    ```bash
    $ pidof -z
    ```
---

## Exit Status
- **0** = Atleast one program was found with the requested name.
- **1** = No program was found with the requested name.
---

## Author
- Jaromir Capik ⟨jcapik@redhat.com⟩

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
