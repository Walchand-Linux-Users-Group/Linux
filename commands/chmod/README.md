# chmod
change file mode bits

---

## Description
Changes the permission on a file or directory

---

## File Permissions
There are three types of file permissions: read(r), write(w), and execute(x)
read(r): view contents of the file 
write(w): to make changes in contents of the file
execute(x): execute means to be able to run a file 

### To get permissions of all the files and folders in directory:
```bash
$ ls -l
```
### After ls -l output is:
<div align="center">
  <img src="https://github.com/Walchand-Linux-Users-Group/linux/blob/main/assets/chmodpic1.png" align="center" />
</div>
<br/>
<br/>
<div align="center">
  <img src="https://github.com/Walchand-Linux-Users-Group/linux/blob/main/assets/chmodpic3.png" align="center" height="90" width="250" />
</div>

Here first positon represent object's type: - for a file, d for a directory, and l for a symbolic link.
The next nine positions are grouped in threes and represents the permission mode.

<div align="center">
  <img src="https://github.com/Walchand-Linux-Users-Group/linux/blob/main/assets/chmodcommands2.png" align="center" />
</div>

---

## Syntax

The chmod commands modifies the permissions of the object.

```bash
chmod [OPTION]... MODE[,MODE]... FILE...
```   
---

## Explaination and Examples

- ### Changing permissions with chmod(letters)
Here plus(+) symbol adds a permission, and minus(-) symbol removes a permission.
- Example:
```bash
$ chmod u+x,g-r,o+w commands.txt
```
This command is for the commands.txt file.
  1) u+x means the user is given the permission to execute.
  2) g-r means the group dosen't have the permission to read.
  3) o+w means the others are given the permission to write.

- ### Changing permissions with chmod(numbers)
 Here r=4, w=2, x=1 use each set’s total number to establish the permission.
 - Example:
 ```bash
 $ chmod 743 commands.txt
 ```  
  Here first number i.e 7, is referred to as permisson given to user which is 4+2+1 meaning it has all the permission of read, write and execute.
  Second number i.e 4, is referred to as permission given to group which is 4+0+0 meaning it has only read permission and no write and execute permission.
  Third number i.e 3, is referred to as permission given to other which is 0+2+1 meaning it has only write and execute permission and no read permission.

---

## Author
- David MacKenzie 
- Jim Meyering.

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.

## Author
- David MacKenzie 
- Jim Meyering.

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
