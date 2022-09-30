# wget
    Wget - The non-interactive network downloader.

---

## Description
    Wget is non-interactive, meaning that it can work in the background, while the user is not logged   on.  This allows you to start a retrieval and disconnect from the system, letting Wget finish the work.  By contrast, most of the Web browsers require constant user's presence, which can be a
    great hindrance when transferring a lot of data.

---

## Syntax
```bash
    syntax of command
    $ wget [option]... [URL]...
```

---

## Options/Flags
- ###  wget -r
    Wget uses GNU getopt to process command-line arguments, every option has a long form along with the short one.  Long options are more convenient to remember, but take time to type.  You may freely mix different option styles, or specify options after the command-line arguments.
    Thus you may write:
    ```bash
        $ wget -r --tries=10 http://fly.srk.fer.hr/ -o log
        $ wget -r <URL>
    ```
- ### wget -drc <URL>
    You may put several options that do not require arguments together, like:
    ```bash
    $ wget -drc <URL>
    ```
    or 

    $ wget -d -r -c <URL>

---
