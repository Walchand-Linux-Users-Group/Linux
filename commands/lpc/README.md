# lpc
Line Printer Control
---

## Description
- Used to manage printer queues and printer status within the Line Printer Daemon (LPD) printing system.
- It allows users to interact with and control printers, print queues, and jobs in a similar fashion to lpq and lprm, but with more advanced capabilities.

---

## Syntax
```bash
lpc [command] [printer]
```

---

## Commands
- ### status [printer]: 
  Displays the status of the specified printer.
    ```bash
    $ lpc status printer_name
    ```   
- ### stop [printer]: 
  Stops the specified printer, preventing new print jobs from being processed.
    ```bash
    $ lpc stop printer_name
    ```
- ### start [printer]: 
  Starts a stopped printer, allowing it to process print jobs again.
    ```bash
    $ lpc start printer_name
    ```
- ### abort [printer]: 
  Aborts the current print job being processed by the printer.
    ```bash
    $ lpc abort printer_name
    ```
- ### disable [printer]: 
  Disables the printer, preventing any print jobs from being accepted.
    ```bash
    $ lpc disable printer_name
    ```
- ### enable [printer]: 
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