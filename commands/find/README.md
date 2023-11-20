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
- (.) : For current directory name
- (/) : For the root directory

## Options/Flags
- ### -name pattern:
    To check that the file name is the same as the given shell-glob pattern or not.
    ```bash
    $ find . -name "*.txt"   
    ```   
- ### -type type: 
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

## Autor
- Dick Haight

---
