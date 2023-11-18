# lpq
Line Printer Queue
---

## Description
- Used to display the status of a printer's print queue. 
- It shows information about the jobs that are waiting to be printed, including their IDs, owners, and status in the print queue.

---

## Syntax
```bash
lpq [options] [printer]
```

---

## Options/Flags
- ### -a: 
  Shows the status of all printers.
    ```bash
    $ lpq -a
    ```   
- ### -l: 
  Displays additional details about each print job, such as the job ID, owner, file size, date and time of submission, and the status of the job in the queue.
    ```bash
    $ lpq -l
    ```
- ### -P printer: 
  Specifies a specific printer to check.
    ```bash
    $ lpq -P printer_name
    ```
---

## Exit Status 
- **0** = Successful execution
- **non-zero value** = Error Occurrence

---