# Command
lsusb

---

## Description
lsusb  is  a  utility  for  displaying  information  about USB buses in the system and the devices connected to them.


---

## Syntax
```bash
lsusb [options]
```

---

## Options/Flags
- -v, --verbose:
    ```bash
    $ lsusb -v
    ```
    Tells lsusb to be verbose and display detailed information about the devices shown

- -t:
    ```bash
    $ lsusb -t
    ```
    Tells lsusb to dump the physical USB device hierarchy as a tree. 

- -s [[bus]:][devnum]
    ```bash
    $  lsusb -s <bus>:<device>
    ```
    Show  only  devices in specified bus and/or devnum.  Both ID's are given in decimal and may be omitted.
  .
  .
  .


---

## Author
- Thomas Sailer

---

