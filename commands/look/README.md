## look
 
Display lines beginning with a given string.

---

## Description

- The look utility displays any lines in a file that contain a string as a prefix. As `look` performs a binary search, the lines in the file must be sorted (where sort(1) was given the same options `-d` and/or `-f` that look is invoked with).
- If a file is not specified, then the file `/usr/share/dict/words` is used, only alphanumeric characters are compared and the case of alphabetic characters is ignored.

---

## Syntax

```bash
$ look [options] string [file]
```
---

## Options/Flags

- ###  -a, --alternative
  Use the alternative dictionary file.
  ```bash
  $ look -a string
  ```

- ###   -d, --alphanum
  Use normal dictionary character set and order, i.e. only blanks and alphanumeric characters are compared. This is on by default if no file is specified.
  ```bash
  $ look -d string
  ```

- ### -f, --ignore-case
  Ignore the case of alphabetic characters. This is on by default if no file is specified.
  ```bash
  $ look -f string
  ```

- ### -t, --terminate character
  Specify a string termination character, i.e. only the characters in the string up to and including the first occurrence of character are compared.
  ```bash
  $ look -t= character string
  ```

- ###  -h, --help
  Display help text and exit.
  ```bash
  $ look -h
  ```
  
---

## Exit Status
- **0:** The command executed successfully, and lines beginning with the specified string were found.
- **1:** No lines beginning with the specified string were found.
- **>1:** An error occurred.




