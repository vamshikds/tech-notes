# Bash Terminal Cheet Sheet
Quick reference on various commands used in Bash Scripting
## Navigation:
+ `pwd`- print working directory - shows your current directory (folder) path
+ `cd..`- takes you one level back on directory level.
+ `cd <folder_name>` - goes to that specific folder in the same directory level
+ `mkdir <dir_name>` - creates a new directory in the current path.
  + *example:* `mkdir python` - creates a folder by name python.
+  `mv <source> <destination>` - move or rename a file or folder to the destination.
+ `ls` - lists the files and folders in the current directory.
  + `ls -l` - flag `-l` lists as ls but in long format with fie permissions, the number of links, the owner, the group, file size in bytes and last modified date/time
  + `ls -a` - the flag `-a` shows all files and folders including hidden ones.
  + `ls -la` - the flag `-la` lists all in a long format - combined long + hidden.
  + `ls -h` - the flag `-h`is for Human readable sizes - converts raw sizes like `1024` into `1k` or `12M` or `2G`
  + `ls -t` - the flag `-t` sorts by modification time showing most recent changes first.
  + `ls -r` - the flag `-r` sorts the modification time in reverse order showing oldest first.
  + `ls -R` -- the flag `-R` is for Recursive Listing i-e-. lists all the contents of the directory plus contents of every subfolder inside it recursively.

