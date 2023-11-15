# unzip
Extract ZIP Archives in Linux

---

## Description
The unzip command in Linux is used to extract files from a ZIP archive. The unzip command is part of the GNU core utilities package, so it is likely pre-installed on your Linux machine.
---

## Syntax
```bash
unzip [options] zipfile [file(s)_to_extract] [-x file(s)_to_exclude]
```

---

## Options/Flags
- ### -l = List the contents of an archive without extracting them.
    ```bash
    $ unzip -l [FILE]
    ```
- ### -d = Extract files to a specific directory.
    ```bash
    $ unzip [FILE] -d [DIRECTORY]
    ```
- ### -q = Quiet mode. Suppress informational messages during extraction.
    ```bash
    $ unzip -q [FILE]
    ```
- ### -o = Overwrite files without prompting.
    ```bash
    $ unzip -o [FILE]
    ```
- ### -P = Specify a password for encrypted ZIP archives.
    ```bash
    $ unzip -P [PASSWORD] [FILE]
    ```
- ### -u = Update existing files and create new ones if needed.
    ```bash
    $ unzip -u [FILE]
    ```
- ### -v = Provide more verbose output.
    ```bash
    $ unzip -v [FILE]
    ```
- ### -f = Freshen existing files. Extract only those files that are newer than the existing ones.
    ```bash
    $ unzip -f [FILE]
    ```
- ### -j = Junk the path. Do not create directories; extract all files in the current directory.
    ```bash
    $ unzip -j [FILE]
    ```
- ### -j = Junk the path. Do not create directories; extract all files in the current directory.
    ```bash
    $ unzip -j [FILE]
    ```
- ### -T = Test the integrity of the ZIP archive.
    ```bash
    $ unzip -T [FILE]
    ```
- ### -x = Exclude specific files or directories from being extracted.
    ```bash
    $ unzip [FILE] -x [FILE(S) TO EXCLUDE]
    ```
---

## Exit Status
- **0** = Successful operation
- **1** = Operation completed with minor warnings
- **2** = Fatal error occurred
- **3** = Severe error occurred
- **50** = User specified an invalid command line option
- **60-79** = Non-fatal errors occurred
---

## Author
- Sharaneshwar Bharat Punjal
---
