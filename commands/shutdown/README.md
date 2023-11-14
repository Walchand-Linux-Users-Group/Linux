# shutdown
Power-off the machine.

---

## Description
`shutdown` may be used to halt, power off, or reboot the machine.

---

## Syntax
```bash
$ shutdown [OPTIONS...] [TIME] [WALL...]
```

---

## Options/Flags
- ###  --help:
  Print a short help text and exit.
    ```bash
    $ shutdown --help
    ```
- ### -H, --halt :
  Halt the machine. 
    ```bash
    $ shutdown -H
    ```
- ### -P, --poweroff:
  Power the machine off (the default).
    ```bash
    $ shutdown
    ```
    or
    ```bash
    $ shutdown -P
    ```
- ### -r, --reboot:
  Reboot the machine.
    ```bash
    $ shutdown -r
    ```
- ### -k:
  Do not halt, power off, or reboot, but just write the wall message. 
    ```bash
    $ shutdown -k
    ```
- ### --no-wall:
  Do not send wall message before halt, power off, or reboot.
    ```bash
    $ shutdown --no-wall
    ```
- ### -c:
  Cancel a pending shutdown.
    ```bash
    $ shutdown -c
    ```
- ### --show:
  Show a pending shutdown action and time if there is any.
    ```bash
    $ shutdown --show
    ```

---

## Exit Status
- **0** = Success
- **!0** = Failure
---
