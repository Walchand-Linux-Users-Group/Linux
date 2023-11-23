# Command

lpc

## Description

- Fullform: Line Printer Control.
- Used to manage printer queues and printer status within the **_Line Printer Daemon (LPD)_** printing system.
- It allows users to interact with and control printers, print queues, and jobs in a similar fashion to lpq and lprm, but with more advanced capabilities.

---

## Syntax

```bash
$ lpc [command]
```

---

## Commands

- ### -p
  To list available printers.
  ```bash
  $ lpstat -p
  ```
- ### status:
  Displays the status of the specified printer.
  ```bash
  $ lpc status printer_name
  ```
- ### stop:
  Stops the specified printer, preventing new print jobs from being processed.
  ```bash
  $ lpc stop printer_name
  ```
- ### start:
  Starts a stopped printer, allowing it to process print jobs again.
  ```bash
  $ lpc start printer_name
  ```
- ### abort:
  Aborts the current print job being processed by the printer.
  ```bash
  $ lpc abort printer_name
  ```
- ### disable:
  Disables the printer, preventing any print jobs from being accepted.
  ```bash
  $ lpc disable printer_name
  ```
- ### enable:
  Enables a disabled printer, allowing it to accept print jobs again.
  ```bash
  $ lpc enable printer_name
  ```
- ### exit:
  Exits the lpc command interface.
  ```bash
  $ lpc exit
  ```

---

## Exit Status

- **0** = Successful execution
- **non-zero value** = Error Occurrence

---

## Note

The availability and behavior of the `lpc` command may vary between different Unix-like systems, depending on the printing subsystem in use.

---

## Author

- [Patrick Powell](papowell@lprng.com)

---

## Copyright

Copyright © Regents of the University of California. All rights reserved. <br/>
This software is provided by the Regents and its contributors "as is" and any express or implied warranties are disclaimed.

---
