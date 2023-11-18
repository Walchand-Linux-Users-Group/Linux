# Command

passwd

---

## Description
- `passwd` command in Linux is used to change the user account passwords.
- The root user reserves the privilege to change the password for any user on the system, while a normal user can only change the account password for his or her own account.

---

## Syntax
```bash
$ passwd [options] [username] 
```

---

## Options/Flags
- ###  -d, --delete
    Deletes the user password and makes the account password-less.
    ```bash
    $ passwd -d
    ```
- ### -e, --expire
    Immediately expires the account password and forces the user to change the password on their next login.
    ```bash
    $ passwd -e
    ```
- ### -h, --help
    Display help related to the passwd command.
    ```bash
    $ passwd -h
    ```
- ### -a, --all
    Reports password status on all accounts.
    ```bash
    $ passwd -a
    ```
- ### -k, --keep-tokens
    Used when you only want to change the password if it is expired.
    ```bash
    $ passwd -k
    ```
- ### -l, --lock
    Locks the password of user.
    ```bash
    $ passwd -l
    ```
- ### -q, --quiet
    - This option is used for quiet mode.
    - While using this option to change a password, the message “Changing password for $user.”, which usually gets printed before changing a password, does not get echoed.
    ```bash
    $ passwd -q 
    ```
- ### -S
    - Shows the password status (7 fields) of a user in the following format:
        ```bash
        $ pratiksha P 11/16/2023 0 99999 7 -1
        ```

    ```bash
    $ passwd -S
    ```
- ### -u,--unlock
    Unlocks the password of an account.
    ```bash
    $ passwd -u
    ```

---

## Author
-  Julie Haugh 

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
