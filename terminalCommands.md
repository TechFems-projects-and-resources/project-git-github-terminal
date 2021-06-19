### TERMINAL INFO

You may know some of this already. It is a quick summary of the basics that can be helpful to you.

* the terminal is often called *shell*
* it is an application that you can use, just like any application (browser, calculator, Word)
* a terminal can be *bash* or *zsh* or others: these are terminal types but they do the same thing
* you cannot use the mouse in the terminal: only the arrow keys left and right
* you can run the same command again in your terminal by using the arrow UP or arrow DOWN keys

**Useful commands:**

Command | Explanation
------- | -----------
`pwd` | print working directory: this will give you the folder you are working in
`~` | go to the home folder/directory (~ stands for 'home')
`cd` | change folder/directory: this will also go to the home directory
`cd ..` | change folder/directory one level up 
`cd NAME` | go to folder/directory NAME (the file name with extension, such as .js, .txt, .html, etc.)
`ls ` | this will show a list of files in the folder/directory that you are in (we also call that 'current directory')
`clear` | clears everything in the terminal
`mkdir NAME` | makes a new directory/folder with the name of NAME
`touch NAME` | make a new file with the name of NAME
`cp NAME` | copy the file with the name NAME
`cp NAME FOLDER` | copy the file called NAME into the folder called FOLDER
`rm FILENAME ` | remove (delete) the file FILENAME
`mv CURRENT-LOCATION/FILENAME` `NEW-LOCATION` `/FILENAME` | move a file from one directory to another. The filename stays the same, but you specify another directory
`mv FILENAME NEW-FILENAME` | rename the file FILENAME to NEW-FILENAME
`cat FILENAME` | view contents of the file

**Important: Ctrl C  will terminate most of the commands that are running** but sometimes you need to use `q` (for 'quit') to get out of a screen (for example, after you have used git diff in the terminal)

**Important:** Commands that start with 'sudo' have to do with administrator privileges, so don't use them unless you are absolutely sure of what you are doing (sudo = SuperUserDo, and superuser is the administrator).