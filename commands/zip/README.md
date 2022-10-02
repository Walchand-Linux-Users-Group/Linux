# zip
Compress a file

---

## Description
It is used to compress a file, allows us to create an archive of files and directories.
It is used when you have a limited bandwidth between two servers and want to transfer the files faster then zip the files and transfer.

---

## Syntax
```bash
zip [options] zipfile files_list
Ex: zip myfile.zip filename.txt
```
---

## Options/Flags
- ###  -d
    Removes the file from the zip archive
    ```bash
    $ zip –d filename.zip file.txt
    ```
- ###  -u
    Used to update the specified list of files or add new files to the existing zip file.
    ```bash
    $ zip –u filename.zip file.txt
    ```
- ###  -m
    Deletes the original file after zipping.
    ```bash
    $ zip –m filename.zip file.txt
    ```
- ###  -r
    Helps to zip all the files present in the specified directory.
    ```bash
    $ zip –r filename.zip directory_name
    ```
- ###  -x
    Used to exclude some unwanted files while creating a zip archive of a directory.
    ```bash
    $ zip –x filename.zip file_to_be_excluded
    ```
- ###  -e
    Used to create basic password protected ZIP files i.e to encrypt a zip file with password.
    Below command will prompt user to enter a password and verify it.
    ```bash
    $ zip –e filename.zip file.txt
    ```
  
---

## Exit Status
- **0** = OK
- **2** = The zipfile is either truncated or damaged
- **3** = The structure of the zipfile is invalid
- **4** = Unable to allocate sufficient memory to complete the command
- **9** = Zip was interrupted by user (or superuser) action
---

## Author
- Phil Katz






