# phase-0-gps-1
GPS 1.1 for DevBootcamp Phase 0

# Git Commands
Assuming "git" is type before each of the following commands.
## push
Push transfers a set of commits between last push and present push to a remote repository. This is used most commonly when working from a local repo with the intent of transfering commits to a shared repository.
## checkout
Checkout switches to a preexisting branch in a given repo. the -b flag allow the user to both create a new branch and switch to it.

#Terminal Commands
## pwd
pwd stands for print working directory which tells the user which folder they are currently in in their terminal.
## cd <directory path>
cd stands for change directory, which moves the user to the specified directory
## touch <filename>
touch creates a file in the user's current directory.
## subl <filename>
subl opens the specified file in Sublime Text.
## history
history shows a list of all commands used in terminal, with an option to show *everything* from the beginning of time

# How git works
## Tracks changes:
The user can track changes via git by adding and commiting changes in their files, which effectively creates a save point.
## Process:
* Make a change in a given file or files
* Use "git add --all" / "git add <filename> ..." to stage files for committing (this allows for asyncronous adding but all one commit)
* Use "git commit -m <message>" to commit the changes and make a note as to what the differences are between the current commit and the last commit.
* Rinse and repeat.

