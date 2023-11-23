# Command

cut

---

## Description

- Used to cut out the sections from each line of files and write the result to standard output.
- It can be used to cut parts of a line by byte position, character and field.

---

## Syntax

```bash
cut [OPTION]... [FILE]...
```

---

## Options/Flags

- ### -b:

  - To extract the specific bytes, you need to follow `-b` option with the list of byte numbers separated by `,`.

    - List without ranges:
      ```bash
      $ cut -b 1,2,3 myfile.txt
      ```
    - List with ranges:
      ```bash
      $ cut -b 1-3,5-7 myfile.txt
      ```

  - It uses a special form for selecting bytes from the beginning upto the end of the line.

    - In this, 1- indicates from the 1st byte to the end byte of a line:
      ```bash
      $ cut -b 1- myfile.txt
      ```
    - In this, -3 indicates from the 1st byte to the 3rd byte of a line:
      ```bash
      $ cut -b -3 myfile.txt
      ```

- ### -c:

  - To cut by character use the -c option.

    - List without ranges:
      ```bash
      $ cut -c 2,5,7 myfile.txt
      ```
    - List with ranges:
      ```bash
      $ cut -c 1-3,5-7 myfile.txt
      ```

  - Cut uses a special form for selecting characters from the beginning upto the end of the line.

    - In this, 1- indicate from 1st character to the end character of a line:
      ```bash
      $ cut -c 1- myfile.txt
      ```
    - In this, -5 indicates from the 1st character to the 5th character of a line:
      ```bash
      $ cut -b -5 myfile.txt
      ```

- ### -f:

  - Used for fixed-length lines.

    ```bash
    $ cut -f 1 myfile.txt
    ```

---

## Exit Status

- **0** = Successful execution
- **non-zero value** = Error Occurrence

---
