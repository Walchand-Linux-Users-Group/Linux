## look
 
Display lines beginning with a given string

---

## Description

 The look utility displays any lines in file which contain string as a prefix. As look performs a binary search, the lines in file must be sorted (where sort(1) was given the same options -d and/or -f that look is invoked with).
If file is not specified, the file /usr/share/dict/words is used, only alphanumeric characters are compared and the case of alphabetic characters is ignored.

---

## Syntax

```bash
look [options] string [file]
```
---

## Options/Flags

- ###  -a, --alternative
Use the alternative dictionary file.

- ###   -d, --alphanum
 Use normal dictionary character set and order, i.e., only blanks and alphanumeric characters are compared. This is on by default if no file is specified.

- ### -f, --ignore-case
Ignore the case of alphabetic characters. This is on by default if no file is specified.

- ### -t, --terminate character
Specify a string termination character, i.e., only the characters in string up to and including the first occurrence of character are compared.

- ###  -h, --help
 Display help text and exit.

---




