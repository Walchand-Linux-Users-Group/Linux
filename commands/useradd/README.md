# useradd
    To create new user
## Description
    Create the new user

## Syntax
    ```useradd [OPTIONS] USERNAME```
## Optional Flags
-   ### -m 
    Use the -m (--create-home) option to create the user home directory as /home/username:
    ```sudo useradd -m username```

- ### -u 
    In Linux and Unix-like operating systems, users are identified by unique UID and username.
    By default, when a new user is created, the system assigns the next available UID from the range of user IDs specified in the login.defs file.
    Invoke useradd with the -u (--uid) option to create a user with a specific UID.

    ```sudo useradd -u 1500 username```
- ### -g
    The -g (--gid) option allows you to create a user with a specific initial login group. You can specify either the group name or the GID number. The group name or GID must already exist.
    ```sudo useradd -g users username```
- ### -G
    To create user and assign the multiple group
    ```sudo useradd -g users -G wheel,developers username```
- ### -D
    The default useradd options can be viewed and changed using the -D, --defaults option, or by manually editing the values in the /etc/default/useradd file.
    ```useradd -D```
- ### -r
    To create the system user use r flag
    ```sudo useradd -r username```
- ### -e
    To create the user with expire Date
    ```sudo useradd -e 2019-01-22 username```














