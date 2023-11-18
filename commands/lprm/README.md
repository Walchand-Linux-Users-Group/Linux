# lprm
Line Printer Remove
---

## Description
-  This command allows users to delete or cancel print jobs that have been sent to a printer but have not yet been printed or are waiting in the print queue.

---

## Syntax
```bash
lprm [options] [job ID(s)]
```

---

## Options/Flags
- ### -#: 
  Removes the specified job ID from the print queue. Replace # with the job number you want to remove.
    ```bash
    $ lprm 3
    ```   
- ### -P printer: 
  Specifies the printer from which you want to remove the print job. Replace printer with the name of the printer.
    ```bash
    $ lprm -P printer1
    ```
- ### -U username: 
  Removes all jobs from the print queue sent by the specified username.
    ```bash
    $ lprm -U user1
    ```
- ### -a: 
  Removes all jobs from all printers in the queue.
    ```bash
    $ lprm -a
    ```
- ### -h server: 
  Specifies the server where the printer is located.
    ```bash
    $ lprm -h serverName jobId
    ```
---

## Exit Status 
- **0** = Successful execution
- **non-zero value** = Error Occurrence

---