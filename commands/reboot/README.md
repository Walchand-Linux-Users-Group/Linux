# reboot
Reboot, halt, or power-off the system.

---

## Description
`reboot`, `halt`, and `poweroff` are commands used to initiate a system reboot, halt, or power-off. All three commands may take the same options.

---

## Syntax
```bash
$ reboot [options]
```
or
```bash
$ halt [options]
```
or
```bash
$ poweroff [options]
```

---

## Options/Flags
- ###  --help:
  #### Print a short help text and exit.
    ```bash
    $ reboot --help
    ```
    or
    ```bash
    $ halt --help
    ```
    or
    ```bash
    $ poweroff --help
    ```
- ### --halt:
  #### Halt the machine, regardless of which one of the three commands is invoked.
    ```bash
    $ reboot --halt
    ```
    or
    ```bash
    $ halt
    ```
    or
    ```bash
    $ poweroff --halt
    ```
- ### -p, --poweroff:
  #### Power-off the machine, when either `halt` or `poweroff` is invoked. This option is ignored when reboot is invoked.
    ```bash
    $ halt -p
    ```
    or
    ```bash
    $ poweroff
    ```
- ### --reboot:
  #### Reboot the machine, regardless of which one of the three commands is invoked.
    ```bash
    $ reboot
    ```
    or
    ```bash
    $ halt --reboot
    ```
    or
    ```bash
    $ poweroff --reboot
- ### -f, --force:
  #### Force immediate halt, power-off, reboot.
    ```bash
    $ reboot -f
    ```

    ```bash
    $ halt -f
    ```

    ```bash
    $ poweroff -f
- ### -w, --wtmp-only:
  #### Only write wtmp shutdown entry, do not actually halt, power-off, reboot.
    ```bash
    $ reboot -w
    ```

    ```bash
    $ halt -w
    ```

    ```bash
    $ poweroff -w
    ```
- ### -d, --no-wtmp:
  #### Do not write wtmp shutdown entry.
    ```bash
    $ reboot -d
    ```

    ```bash
    $ halt -d
    ```

    ```bash
    $ poweroff -d
    ```
- ### -n, --no-sync:
  #### Don't sync hard disks/storage media before halt, power-off, reboot.
    ```bash
    $ reboot -n
    ```

    ```bash
    $ halt -n
    ```

    ```bash
    $ poweroff -n
    ```
- ### --no-wall:
  #### Do not send wall message before halt, power-off, or reboot.
    ```bash
    $ reboot --no-wall
    ```

    ```bash
    $ halt --no-wall
    ```

    ```bash
    $ poweroff --no-wall
    ```

---

## Exit Status
- **0** = Success
- **!0** = Failure
---
