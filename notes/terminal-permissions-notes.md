# Terminal Permissions

### Info About $PATH

- `$PATH` is a list of paths, separated by colons
- The computer uses `$PATH` to try to locate commands that you type in to the command line
- So when I type `cd`, we are doing a search through each of the folders in $PATH in order, until we can find a program (file) called `cd`.
- As soon as it does find one it executes it

### Useful Shortcuts

Close window/tab: CMD+W
Hide Application: CMD+H
Switch Applications: CMD+TAB
Switch Between Windows in an Application: CMD+~

### Permissions

- Owner, Groups, Others
- Read, Write, Execute

**Original**: drwxrwxr-x

Owner: rwx
Groups: rwx
Others: r-x

**English**: " The owner of the file can read, write, and execute it, groups can read, write, and execute, and others can read and execute"

Others: users that do not own the file. (everyone regular accts(
Groups: could belong to staff or admins

### What You Can Do With a File

- view the file
- make changes to the file
- pass the file to a program and ask it to run it (the code in it)
-unset "-"?

### Homework

**Challenge**: Is there a command that will change who the owner of a file is? What is that command? How do you use it?

**Solution**  Change File Permissions

- navigate in terminal to where file resides
- cd into the file i.e (chaz/desktop/example.md)
- check file permissions first by *ls* with flag of -l (l=long format)
- *d* indicates directory 

-man chmod for help
1. specify (User/Group, Other) 
2. decide operation (add, delete, clear or defaults)
3. chmod ugo  (chmod go+wx) 
4. chown- changes ownership of files and folders
I
 
**Resources

[chmod resource](http://www.chriswrites.com/how-to-change-file-permissions-using-the-terminal/)

For example, the following would transfer the ownership of a file named file1 and a directory named dir1 to a new owner named alice:

chown alice file1 dir1

[chown resource] (http://www.linfo.org/chown.html)
