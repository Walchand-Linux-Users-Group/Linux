# Command

alias

---

## Description

- `alias` command instructs the shell to replace one string with another string while executing the commands.
- When we often have to use a single big command multiple times, in those cases, we create something called as _**alias**_ for that command.
- `alias` is like a shortcut command which will have same functionality as if we are writing the whole command.

---

## Syntax

```bash
$ alias [-p] [name[=value] ... ]
```

---

## Options/Flags

- ### Creating an Alias

  ```bash
  $ alias name="value"
  ```

- ### Creating an Unalias (Removing an existing alias)

  ```bash
  $ unalias [alias name]
  ```

- ### -p
  Lists all of the aliases that are currently defined in the shell.
  ```bash
  $ alias -p
  ```
- ### --help
  It displays help Information.
  ```bash
  $ alias --help
  ```

---

## How to permanently store aliases across sessions?

- We can store aliases in shell configuration files.
- For example for Bash Shell, we can write in `~/.bashrc`.
- Let us suppose we want to make an alias of changing to Documents directory as `CD`. For that go in the `.bashrc` file and write:

  ```bash
  $ alias CD="cd Documents"
  ```

---

## Note

<font color="yellow"> There must not be space before and after the '=' sign in the command. </font>

---

## Author

- Bill Joy

---

## Copyright

Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
