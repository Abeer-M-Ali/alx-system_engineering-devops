# Shell Basics Tasks :


## mandatory


### Where am I?

0. Write a script that prints the absolute path name of the current working directory.

### What’s in there?

1. Display the contents list of your current directory.

### There is no place like home

2. Write a script that changes the working directory to the user’s home directory.
   - You are not allowed to use any shell variables

### The long format

3. Display current directory contents in a long format

### Hidden files

4. Display current directory contents, including hidden files (starting with `.`). Use the long format.

### I love numbers

5. Display current directory contents.
   - Long format
     - with user and group IDs displayed numerically
     	- And hidden files (starting with .)

### Welcome

6. Create a script that creates a directory named `my_first_directory` in the `/tmp/` directory.

### Betty in my first directory

7. Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

### Bye bye Betty

8. Delete the file `betty`.
   - The file `betty` is in `/tmp/my_first_directory`

* The file `hello` will be in the working directory You are not allowed to use commas for this script

### Bye bye My first directory

9. Delete the directory `my_first_directory` that is in the `/tmp` directory.

### Back to the future

10. Write a script that changes the working directory to the previous one.

** Note: the mode of `olleh` will not always be 664. Make sure your script works for any mode.

### Lists

11. Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.

### File type

12. Write a script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we will run your script.

** Note that depending on the file, the output of your script will be different.

### We are symbols, and inhabit symbols

13. Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.

### Copy HTML files

14. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

** You can consider that all HTML files have the extension `.html`


## advanced


### Let’s move

15. Create a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.
   - You can assume that the directory `/tmp/u` will exist when we will run your script

### Clean Emacs

16. Create a script that deletes all files in the current working directory that end with the character `~`.

### Tree

17. Create a script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory.

** You are only allowed to use two spaces (and lines) in your script, not more.

### Life is a series of commas, not periods

18. Write a command that lists all the files and directories of the current directory, separated by commas (`,`).
   - Directory names should end with a slash (`/`)
     - Files and directories starting with a dot (`.`) should be listed
       - The listing should be alpha ordered, except for the directories `.` and `..` which should be listed at the very beginning
         - Only digits and letters are used to sort; Digits should come first
           - You can assume that all the files we will test with will have at least one letter or one digit
     	       - The listing should end with a new line

### File type: School

18. Create a magic file `school.mgc` that can be used with the command file to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0.

## Author :octocat:

- [Abeer Ragab](https://github.com/Abeer-M-Ali) | [Linkedin](https://www.linkedin.com/in/abeer-ragab-b25872260/)