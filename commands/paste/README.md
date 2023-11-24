# Command

paste

---

## Description

- Used to join files horizontally (parallel merging) by outputting lines consisting of lines from each file specified, separated by tab as delimiter, to the standard output.

---

## Syntax

```bash
$ paste [OPTION]... [FILE]...
```

---

## Options/Flags

- ### -d (delimiter):
  The `paste` command uses the tab delimiter by default for merging the files.
  The delimiter can be changed to any other character by using the `-d` option.
  ```bash
  $ paste -d "|" filename1 filename2 filename3
  ```
- ### -s (serial):
  We can merge the files in a sequential manner using the `-s` option.
  ```bash
  $ paste -s filename1 filename2 filename3
  ```

---

## Exit Status

- **0** = Successful execution
- **1** = Error Occurrence

---
