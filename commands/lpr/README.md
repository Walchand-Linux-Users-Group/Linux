# Command

lpr

---

## Description

- Fullform: Line Printer Remote/Line Printer Deamon.
- Used to print files from the Linux command line.
- It uses a spooling daemon to print the named file when facilities become available.
- If no files are specified, the `lpr` command reads from standard input.

---

## Syntax

```bash
$ lpr [OPTIONS] [FILE]...
```

---

## Options/Flags

- ### -P:
  Specifies the printer that you want to print to.
  ```bash
  $ lpr -P printerName myfile.txt
  ```
- ### -h:
  Disables banner printing.
  ```bash
  $ lpr -h myfile.txt
  ```
- ### -l:
  Specifies that the print file is already formatted for the destination and should be sent without filtering.
  ```bash
  $ lpr -l myfile.txt
  ```
- ### -#:
  Sets the number of copies that you want to print.
  ```bash
  $ lpr -# 3 myfile.txt
  ```
- ### -o page-ranges:
  Prints only specific pages, in this example, pages 1 to 3 and page 7.
  ```bash
  $ lpr -o page-ranges=1-3,7
  ```

---

## Exit Status

- **0** = Success
- **1** = The file could not be opened.
- **2** = The file could not be printed.
- **3** = The printer is not available.
- **4** = The print job was canceled.
- **5** = There was an error with the printer queue.
- **6** = The print job was aborted.
- **7** = The print job was held.
- **8** = The print job was deleted.
- **9** = The print job was paused.
- **10** = The print job was resumed.

---
