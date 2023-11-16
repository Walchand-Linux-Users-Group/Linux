# fg

foreground

---

## Description
- It is used to put a background job in foreground.

---

## Syntax
```bash
    $ fg [jobID]
```

---

## The jobID can be
- PID (process id)
- %Number -> Refers to a job by the job number.
- %String -> Refers to a job whose name begins with the specified string.
- %?String -> Refers to a job whose name contains the specified string.
- %+ OR %% -> Refers to the current job.
- %- -> Refers to the previous job.

---

## Note
- If the jobID parameter is not supplied, the fg command uses the job most recently suspended, placed in the background, or run as a background job.

---

## Options/Flags
- ### --help
    It displays help Information. 
    ```bash
    $ fg --help
    ```

---

## You can also use the fg command to bring a job to the foreground from a different terminal.
- To do this, you would use the following command:
    ```bash
    $ fg <remote_host>:<job_number>
    ```

---

## Exit status
- **0** -> Successful completion.
- **>0** -> An error occurred.
---

## Author
-  Unknown

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.