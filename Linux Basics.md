# Shell Basics 
There are a variety of Shells available for linux including BASH, CSH, KSH, and TCSH. Methods of access include
the terminal, SSH and using the console. 

# Finding current shell name
This command displays valid shells within your linux environment. It is very possible to see multiple shells supported.
- Bash Shells
   - bash, ksh, sh, zsh
- C-shell
   - bcsh, csh, tcsh

~~~
cat /etc/shells
~~~
~~~
echo $SHELL
ps $$
ps -p $$
~~~

# Basic CLi Editing
- CTRL + L : Clear the screen.
- CTRL + W : Delete the word starting at cursor.
- CTRL + U : Clear the line i.e. Delete all words from command line.
- Up and Down arrow keys : Recall commands (see command history).
- Tab : Auto-complete files, directory, command names and much more.
- CTRL + R : Search through previously used commands (see command history)
- CTRL + C : Cancel currently running commands.
- CTRL + T : Swap the last two characters before the cursor.
- ESC + T : Swap the last two words before the cursor.
- CTRL + H : Delete the letter starting at cursor.
