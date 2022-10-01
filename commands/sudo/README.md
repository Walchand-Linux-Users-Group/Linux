# sudo
super user do 

---

## Description
- It will run a command with safe elevated privileges which are required to perform certain administrative tasks.
- An alternative way to peform administrative tasks without switching to root user.
---

## Syntax
```bash
sudo [command]
```
---

## Flags
- ###  -V (version)
    ```bash
    $ sudo -V
    ```
- ### -l (list)
    ```bash
    $ sudo -l
    ```
- ### -h (help)
    ```bash
    $ sudo -h
    ```
- ### -v (validate)
    ```bash
    $ sudo -v
    ```
- ### -k (kill)
    ```bash
    $ sudo -k
    ```
- ### -K (sure kill)
    ```bash
    $ sudo -K
    ```
- ### -b (background)
    ```bash
    $ sudo -b
    ```
- ### -p (prompt)
    ```bash
    $ sudo -p
    ```
---

## Examples
- ###  rebooting
    ```bash
    $ sudo reboot
    ```
- ### updating
    ```bash
    $ sudo apt-get update
    ```

## Original authors
- Robert Coggeshall
- Cliff Spencer

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
