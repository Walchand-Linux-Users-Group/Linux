# Command
ps
report a snapshot of the current processes.
---

## Description
ps displays information about a selection of the active processes.
---

## Syntax
```bash
ps [options]
```
---

## Options/Flag
- ps -e/-A = select every processes on the system.
## usage
  ```bash
  ps -e
  ```
  ```bash
  ps -A
  ```
- ps T = Select all processes associated with this terminal.
## usage
  ```bash
  ps T
  ```
- ps r = Restrict the selection to only running processes.
## usage
  ```bash
  ps r
  ```
- ps -d = Select all processes except session leaders.
## usage
  ```bash
  ps -d
  ```
## Authors
- Branko Lankester
- Michael K. Johnson

---
