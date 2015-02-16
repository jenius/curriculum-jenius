
###How does the terminal work?

In order to understand the terminal, we must first understand  "the shell". The shell is a program that operates when we input text from the keyboard. The shell takes these commands and gives them to the operating system to perform. The shell is simply a program that takes commands

When we open the terminal we are brought to a shell prompt. In my case it is the name of my computer, followed by my name and a $. In Jeff's case it is a custom lightning bolt  mark. Either way it functions the same. 

To understand how something works, it can sometimes help to understand how it doesn't work. For instance, if we typed gibberish into the command line – we will receive an error message. We must wonder why?

The answer is deceptively simple. The shell looks for commands/programs (code that runs the machine) which are also known as binaries.  These programs are referenced within a variable called $PATH. Then, if it finds one, it executes the program, and if it doesn't it throws an error.

 The $PATH is a list of paths separated by colons. The path variable holds a variety of folders. These folders can be seen by using the command 'echo $PATH'. Thus the command line works by searching for executable files (binaries) that are stored within specified folders contained in the path variable. That is it. 