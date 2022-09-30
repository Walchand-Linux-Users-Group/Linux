# rm
rm

    removes file or directories.
---

## Description
    removes the file and directory.
    rm removes each specified file.  By default, it does not re‐move directories.
    This is used for perticularly removing a file.

---

## Syntax
```bash
    $ rm [OPTION]... [FILE]...
```

---

## Options/Flags
There are alot of options are available.
- ### -f, --force
    ```bash
    $ rm -f or rm --force
    ```
- ### -i --> prompt before every removal
    ```bash
    $ rm -i
    ```
- ### -I 
    prompt once before removing more than three files, or  when  re‐moving  recursively;  less intrusive than -i, while still giving protection against most mistakes
    ```bash
    $ rm -I
    ```
- ### --interactive
    prompt according to WHEN: never,  once  (-I),  or  always  (-i);
    without WHEN, prompt always
    ```bash
    $ rm --interactive
    ```
- ### --one-file-system
    when  removing  a hierarchy recursively, skip any directory that is on a file system different from  that  of  the  corresponding command line argument.

- ### --no-preserve-root
    do not remove '/' (default); with 'all', reject any command line argument on a separate device from its parent.
    **It do not treat '/' specially**
     ```bash
     $ rm --no-preserve-root
     ```
- ### -r, -R, --recursive
    remove directories and their contents recursively
    ```bash
     $ rm -r
     $ rm -R
     $ rm --recursive 
     ```
- ### -d, --dir
    remove empty directories
    ```bash
    $ rm -d
    $ rm --dir
    ``` 
- ### -v, --verbose
    explain what is being done
    ```bash
    $ rm -v
    $ rm -verbose
    ```
- ### --help
    display this help and exit
---

