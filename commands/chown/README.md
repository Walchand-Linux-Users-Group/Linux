# chown
Change the ownership of the file.

---


## Description
Used to change the ownership of files and directories, allowing the assignment of new owners and groups.

---


## File Ownership
- Each file has an owner (a user) and a group associated with it.
- The owner is usually the user who created the file, and the group may include multiple users.
- File ownership is crucial for determining who can access or modify a file.


### To view ownership of all the files and folders in the directory use the command:
```bash
$ ls -l
```

## Syntax

The chown commands modifies the permissions of the object.

```bash
chown [options] new_owner[:new_group] file(s)
```   
---


## Options/Flags
- ###  -c
    Reports when a file change is made. 
    ```bash
    $ chown -c owner_name file1.txt
    ```
- ###  -v
    It is used to show verbose information for every file processed. 
    ```bash
    $ chown -v owner_name file1.txt
    ```
- ###  -f
    When you are not permitted to change group permissions and an error occurs, this option forcefully/silently changes the ownership.
    ```bash
    $ chown -f owner_name file.txt
    ```
- ###  --from=user:group
    Change the ownership only if the file is currently owned by the specified user and group.
    ```bash
    $ chown --from=old_owner:old_group new_owner:new_group file.txt
    ```
- ###  --reference=file
    Use the ownership of another file or directory as a reference.
    ```bash
    $ chown --reference=reference_file.txt file.txt
    ```
---


## Exit Status
- **0** = The command executed successfully and all requested changes were made.
- **>0** = An error occurred.

---


## Author
- Ken Thompson                 
- Dennis Ritchie


---


## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
