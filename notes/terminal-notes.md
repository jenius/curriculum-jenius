#Terminal Commands

### Commands

- `touch` - create file (name of file)
- `mv` - move a file (name of file, name of destination)
- `open` - open a file, folder, application etc
- `pkill` - to end a process (useful more on vps)
- `pwd`- prints working dir
-  `mkdir` -makes directory  
-  `ls` -lists files
-  `rm` -removes file
- `rmdir`  -removes dir
- `cd`- changes to  above working dir
- `cd~` - home dir shortcut
- `cp` - copies files
-  `sudo rm -rf curemap-slang` removes all files/folders

`killall` - useful more for OSX apps
`rm -rf`  -all files in a directory

####Where are you?
. - the current folder
.. - the parent folder
~ - home directory
**NOTE: always use tab**
   
#####Examples 

- `touch “banana muffins.txt”`
-  `cp "banana.txt" /Users/Oldpuppet/Document`  
- `rm -R ./public`  -deletes public folder

## Seeing Whats Running

- To see what programs are running on your computer, there are also a few options
- The graphical interface is called Activity Monitor, which you can open via spotlight. It's found in `/Applications/Utilities/Activity\ Monitor.app`. It will show all running processes and has a button to terminate a program, which will send a `TERM` signal.
- There is a terminal version of activity monitor as well, which you can pull up with the command `top`. This command will show you an interactive view of running processes. You can quit out of it with `q`, as is the usual with interactive terminal programs.
- Finally, you can use `ps aux`, which will spit out a snapshot of the running programs at the time that you ran the command. This one is useful to be able to search through quickly for a specific running process. So for example, you could run `ps aux | grep mongo` to see if mongo is running on your system.

### Man Pages
- To see the manual pages for a command, type `man` followed by that command
- To exit the man page, type `q`

## Dealing with Vim!

- If you get stuck in vim, do not press any keys under any circumstances.
- To get out of it, hit the escape key at least 5 times, then type in `:wq` then press enter.

## Terminating Programs

- When you want to terminate a program in unix, you send it a signal
- A typical signal to send is TERM or SIGTERM, which tells the program that you'd like it to exit. The author of the program can catch this signal and run code to clean things up and have it exit correctly if they want. If it's not caught, it will just be terminated
- If a program is really stubborn and not quitting even after a sigterm, you can send it a KILL signal (9), which will immediately exit with no chance of survival or handling via the program
- There are a few command line utilities that help with killing a program. The original one is `kill` which takes a process id and ends it, by default with a `TERM` signal, but optionally you can pass another number for a signal code in if you'd like.
- Another is `pkill`, which is a slightly more flexible option you can pass either an id or a name to
- Finally you can use `killall` which only accepts a process name, no id.
- If you want more details on any of these commands, check their `man` pages.
- [Here's a screenshot](https://www.dropbox.com/s/1jw8dt8i9vn360c/Screenshot%202015-01-26%2019.29.23.png?dl=0)
- sudo (be very careful ...no backtracking)
- i.e. `  sudo rm -rf curemap-slang/ `
