# uname
    print system information

---

## Description
    Print certain system information.

---

## Syntax
```bash
    $ uname
```

---

## Options/Flags
- ###  -a, -all
    print all information, in the following order, except omit -p and -i if unknown:
    ```bash
    $ uname -a
    or
    $ uname -all
    ```
- ### -s, --kernel-name
    print the kernel name
    ```bash
    $ uname -s
    or
    $ uname --kernel-name
    ```
- ### -n, --nodename
    print the network node hostname
    ```bash
    $ uname -n
    or
    $ uname --nodename
    ```
- ### -r, --kernel-release
    print the kernel release
    ```bash
    $ uname -r
    or 
    $ uname --kernel-release
    ```
- ### -v, --kernel-version
    print the kernel version
    ```bash
    $ uname -v
    ```
- ### -m, --machine
    print the machine hardware name
    ```bash
    $ uname -m
    or 
    $ uname -machine
    ```

- ### -p, --processor
    print the processor type (non-portable)
    ```bash
    $ uname -p
    or
    $ uname --processor
    ```
- ### -i, --hardware-platform
    print the hardware platform (non-portable)
    ```bash
    $ uname -i
    or 
    $ uname --hardware-platform
    ```
- ### -o, --operating-system
    print the operating system
    ```bash
    $ uname -o
    or 
    $ uname --operating-system
    ```
- ### --help 
    display this help and exit
    ```bash
    $ uname --help
    ```
- ### --version
    output version information and exit
    ```bash
    $ uname --version
    ```
### Main AUTHOR
       Written by David MacKenzie.

