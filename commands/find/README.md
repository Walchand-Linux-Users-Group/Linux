# Command

find

---

## Description

- Used to find files as well as directories and perform subsequent operations on them.
- It supports searching by file, folder, name, creation date, modification date, owner and permissions.

---

## Syntax

```bash
find [where to start searching from]
[expression determines what to find] [-options] [what to find]
```

---

## Symbols used to specify the directory

- `.` : For current directory name.
- `/` : For the root directory.

## Options/Flags

- ### -name _pattern_:
  To check that the file name is the same as the given shell-glob pattern or not.
  ```bash
  $ find . -name "*.txt"
  ```
- ### -type _type_:
  To specify the file type.
  ```bash
  $ find . -type d -name "*.bak"
  ```
- ### -delete:
  To find and delete a specific file.
  ```bash
  $ find . -name myfile.txt -delete
  ```
- ### -mtime:
  To find the files by modification, followed by the number of days.
  ```bash
  $ find ./MyDirectory -mtime -1
  ```
- ### -perm:
  To find files by permission.
  ```bash
  $ find ./MyDirectory -perm 777
  ```

---

## Exit Status

- **0** = Successful execution
- **non-zero value** = Error Occurrence

---

## Author

- Eric Decker

### Later enhanced by

- David MacKenzie
- Jay Plett
- Tim Wood

---

## Copyright

Copyright © 2023 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.

---
