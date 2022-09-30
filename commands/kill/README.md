# kill
    send a signal to a process

---

## Description
    The default signal for kill is TERM.  Use -l or -L to list available signals.  Particularly useful signals include HUP, INT, KILL, STOP, CONT, and 0.
    Alternate signals may be specified in three ways: -9, -SIGKILL or -KILL.  Negative PID values may be used to choose whole  process  groups;  see  the
    PGID column in ps command output.  A PID of -1 is special; it indicates all processes except the kill process itself and init.

---

## Syntax
```bash
    $ kill <process>
    or
    $ kill [options] <pid> [...]
```

---

## Options/Flags
- ###  <pid> [...]
    pid is process id.
    ```bash
    $ kill <pid>
    ```
- ### -<signal>
    ```bash
    $ kill -<signal>
    ```
- ### -q, --queue value
    ```bash
    $ kill 
    ```
- ### -l, --list [signal]
    ```bash
    $ kill -l
    or
    $ kill --list
    ```
- ### -L, --table
    List signal names in a nice table.
    ```bash
    $ kill -L
    or
    $ kill --table
    ```

## Examples
EXAMPLES
    ```bash
       $ kill -9 -1
    ```
              Kill all processes you can kill.
    ```bash   
       kill -l 11
    ```   
              Translate number 11 into a signal name.

    ```bash
       kill -L
    ```
              List the available signal choices in a nice table.

    ```bash
       kill 123 543 2341 3453
    ```
              Send the default signal, SIGTERM, to all those processes.

## AUTHOR
       Albert  Cahalan  ⟨albert@users.sf.net⟩  wrote kill in 1999 to replace a bsdutils one that was not standards compliant.  The util-linux one might also
       work correctly