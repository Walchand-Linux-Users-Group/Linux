# Command

diff

---

## Description

This command is used to display the differences in the files by comparing the files line by line.

---

## Syntax

```bash
$ diff [options] File1 File2
```

---

## Options/Flags

- ### -q
  Report only when files differ.
  ```bash
  $ diff -q
  ```
- ### -s
  Report when two files are the same.
  ```bash
  $ diff -s
  ```
- ### -c
  View differences in context mode.
  ```bash
  $ diff -c
  ```
- ### -u
  View differences in unified mode.
  ```bash
  $ diff -u
  ```
- ### -e
  Output an ed script.
  ```bash
  $ diff -e
  ```
- ### -y
  Output in two columns.
  ```bash
  $ diff -y
  ```
- ### -n
  Output an RCS format diff.
  ```bash
  $ diff -n
  ```

---

## Author

- Paul Eggert
- Mike Haertel
- David Hayes
- Richard Stallman
- Len Tower

---

## Copyright

Copyright © 2021 Free Software Foundation, Inc. License GPLv3+: GNU
GPL version 3 or later <https://gnu.org/licenses/gpl.html>.<br/>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

---
