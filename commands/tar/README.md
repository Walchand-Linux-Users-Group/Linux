# tar


---

## Description
The "tar" command is used to create, view, extract, or manipulate archive files in Linux. It can be used to compress multiple files and directories into a single archive file, which can then be easily transferred or stored.into a file.

---

## Syntax
```bash
    $ tar [options] [archive-file] [files or directories to be archived]
```

---

## Options/Flags
- ###  -c
    To create a new archive fil
    ```bash
    $ tar -cvf archive.tar file1 file2
    ```
- ### -x
    To extract files from an archive
    ```bash
    $ tar -xvf archive.tar
    ```
- ### -t
    To list the contents of an archive file.
    ```bash
    $ tar -tvf archive.tar

    ```
- ### -z
    to compress or decompress an archive using gzip.
    ```bash
    $ tar -czvf archive.tar.gz file1 file2
    ```
- ### -j
    To compress or decompress an archive using bzip2.
    ```bash
    $ tar -cjvf archive.tar.bz2 file1 file2
    ```
- ### -f
    to specify the filename of the archive.
    ```bash
    $ tar -cvf myarchive.tar file1 file2
    ```
## Author
-  Archana Saroj
---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.