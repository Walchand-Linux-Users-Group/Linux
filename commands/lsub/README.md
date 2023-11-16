# Command
lsusb

---

## Description
`lsusb`  is  a  utility  for  displaying  information  about USB buses in the system and the devices connected to them.


---

## Syntax
```bash
$ lsusb [options]
```

---

## Options/Flags
- ### -v, --verbose:
  Tells `lsusb` to be verbose and display detailed information about the devices shown.
    ```bash
    $ lsusb -v
    ```
    

- ### -t:
  Tells `lsusb` to dump the physical USB device hierarchy as a tree. 
    ```bash
    $ lsusb -t
    ```
    

- ### -s [[bus]:][devnum]
  Show  only  devices in specified bus and/or devnum. Both ID's are given in decimal and may be omitted.
    ```bash
    $  lsusb -s <bus>:<device>
    ```

---

## Author
- Thomas Sailer

---

## Copyright

Copyright © [Year] Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.<br/>
This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.

