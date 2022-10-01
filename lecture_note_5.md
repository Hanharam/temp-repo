### **Shell command**

#### >
create and save the output in a file.

### <

input from a file

### >>

append output to an extising file.

#### cat

display the content of a text file.

#### |
(pipelines)
command1 | command2 | command3

output of previous command to input of next command.

#### echo
Expansion

echo * : all file in directory
echo ~ : user home directory

#### chomod
changing permission

example : chmod 600 some_file

owner/group/others
-rwx/rwx/rwx 
r = Read, w = Write, x = Execute

```sh
777: (rwxrwxrwx) No restrictions on permissions. Anybody may do anything.
775: (rwxr-xr-x) Owner read, write and execute. All others read and execute the file.
700: (rwx------) Owner read, write and execute. Nobody else has any rights.
656: (rw-rw-rw-) All user may read and write the file.
644: (rw-r--r--) The owner may read and write file, while all others may only read the file.
600: (rw-------) The owner may read and write a file. All others have no rights.
```

#### sudo
Superuser has all system administation authority.

sudo some_command

#### Shell Script
nano myscript.sh

---

```sh
ls | wc -l : the number of directories.
\ (backslash) : ignore line chage in command, to enter a long command in multiple lines.
history : see previous command history.
```
