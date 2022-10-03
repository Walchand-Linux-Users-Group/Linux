# sudo
substitute user or switch user

---

## Description
- It is used to execute commands with the privileges of another user account, by default the root user.
- It can duplicate the functionality of sudo by use of the –c option to pass a single command to the shell.
---

## Syntax
```bash
su [options] [username [arguments]]
```
---

## Flags/options
- ###  -c or --command [command] (Runs a specific command as the specified user)
    ```bash
    $ su –c [command]
    $ su –command [command]
    ```
- ### - or -l or --login [username] (Runs a login script to change to a specific username)
    ```bash
    $ su - [other_user] 
    $ su –l [other_user]
    $ su –login [other_user]
    ```
- ### -s or --shell [shell] (Allows you to specify a different shell environment to run in)
    ```bash
    $ su -s [shell]
    $ su --shell [shell]
    ```
- ### -h or --help (Show the help file for the su command)
    ```bash
    $ su -h
    $ su --help
    ```
- ### –p or ––preserve–environment (Preserve the shell environment (HOME, SHELL, USER, LOGNAME))
    ```bash
    $ su -p
    $ su ––preserve–environment
    ```
- ### Username 
    ```bash
    $ su [username]
    ```
- ### Switch to root user
    ```bash
    $ sudo su -
    ```
---

## Original author
-  David MacKenzie

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
