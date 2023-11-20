# free
free - Display amount of free and used memory in the system

---

## Description
free displays the total amount of free and used physical and swap
       memory in the system, as well as the buffers and caches used by
       the kernel. The information is gathered by parsing /proc/meminfo.
       The displayed columns are:

       total  Total usable memory (MemTotal and SwapTotal in
              /proc/meminfo). This includes the physical and swap memory
              minus a few reserved bits and kernel binary code.

       used   Used or unavailable memory (calculated as total -
              available)

       free   Unused memory (MemFree and SwapFree in /proc/meminfo)

       shared Memory used (mostly) by tmpfs (Shmem in /proc/meminfo)

       buffers
              Memory used by kernel buffers (Buffers in /proc/meminfo)

       cache  Memory used by the page cache and slabs (Cached and
              SReclaimable in /proc/meminfo)

       buff/cache
              Sum of buffers and cache

       available
              Estimation of how much memory is available for starting
              new applications, without swapping. Unlike the data
              provided by the cache or free fields, this field takes
              into account page cache and also that not all reclaimable
              memory slabs will be reclaimed due to items being in use
              (MemAvailable in /proc/meminfo, available on kernels 3.14,
              emulated on kernels 2.6.27+, otherwise the same as free)
---

## Syntax
```bash
$ free [options]
```
---

## Options/Flags
- ###  Display the amount of memory in bytes.
    ```bash
    $ free -b, --bytes
    ```
- ### Display the amount of memory in kibibytes. This is the default.
    ```bash
    $ free -k, --kibi
    ```
- ### Display the amount of memory in mebibytes.
    ```bash
    $ free -m, --mebi
    ```
- ### Display the result count times.  Requires the -s option.
    ```bash
    $ free -c, --count
    ```


---

## Reporting Bugs
Send bug reports to <albert@users.sf.net>
---

## Author

- Brian Edmonds
---

