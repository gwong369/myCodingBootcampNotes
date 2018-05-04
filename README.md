# myCodingBootcampNotes
Coding Class Notes

### This is my Readme file

# Terminal Commands:
## cd < some directory >
Change directory. This changes the working directory. Working Directory is the file path you are currently on in GitBash

< some directory > Can be any folder on your system. If it doesn't start with / like Documents/Misc it means that your current diecgtory should have Documents

If it isn't there, it will give you this error: 

`-bash: cd: Documents: No such file or directory`

## pwd

stands for present working directory. It lists the directory you are in.

## ls

Lists files and directories in current directory

## ls < some directory >
Lists files and directories in some directory

## mkdir
makes a new directory

## touch < filename >
Creates a new file with the name filename

## rm < filename >
removes or deletes a file

## rmdir < directory >
removes or deletes a directory

## git add .
The git add command adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit. However, git add doesn't really affect the repository in any significant way—changes are not actually recorded until you run git commit .

## git commit -m
Saves/commits with notes in quotations

## git push
Shows up in repository

## git clone
to pull the full repository, this is how you start and should only do once

## git status
Diagnostics, shows where you are currently at

## cp < targetfile > < destination file >
Copies a file from target to destination

## mv < targetfile > < destination file >
Moves a file from target to destination

## Special directories:

~/ - User directory 
../ - One directory up (parent directory)
./ - Current directory
/ - root directory (C drive)
