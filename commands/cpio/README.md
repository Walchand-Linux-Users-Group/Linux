# command
cpio

---


## Description
cpio stands for "copy in, copy out".It is a command-line utility in Linux/UNIX for creating, listing and extracting archive files. It creates a .cpio archive file.It can copy the complete file system to an archive file
---

## Modes
There are three modes in cpio command.<br/>
- Copy-out mode: In this mode, cpio copies files into an archive with the -o or --create option.It reads a list of filenames from the standard input and writes to an archive file

- Copy-in mode: cpio copies files out of an  archive or prints the archive contents. In this mode,cpio uses the -i or --extract option to read the archives from the standard input.

- Copy-pass mode: cpio copies files from one directory tree to another in this mode.It does not create an archive file.


## Syntax
- Copy-out mode:
```bash
cpio -o [option] < name-list > archive
```   

- Copy-in mode:
```bash
cpio -i [option] < archive
``` 

- Copy-pass mode:
```bash
cpio -p [option] destination-directory < name-list
``` 
---


## Options/Flags
- ###  -v
    This option displays the list of files processed by the cpio command

    ```bash
    $ cpio -ov < name-list > archive
    ```
    Here -ov is used as -o create the new archive and -v list the files processed

     ```bash
    $ cpio -iv < archive
    ```
    We can extract *.cpio files containing files and directory with the help of cpio -i option


- ###  -t
   The -t option prints the table of contents and doesn't copy any files.
    ```bash
    $ cpio -itv < /home/linux/commands.cpio
    ```
- ###  -H
     The -H option allows you to specify the archive format
    ```bash
    $ cpio -ov -H tar > archive
    ```
- ###  -F
     To specify tar filename which you want to extract
    ```bash
    $ cpio -iv -F < archive
    ```

---


## Exit Status

- **0**: Successful completion
- **>0**: An error occurred


---


## Author
- Dick Haight
---


## Copyright
GNU cpio: GPLv3
libarchive bsdcpio: New BSD License
