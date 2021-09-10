# What is Github exactly?

It is a DVCS (Distributed Version Control System) that allows multiple developers to work on a single project. It creates snapshots of your files every time you make a save (referred to as a commit). All of the changes that are made to files are then stored and tracked by Git.

Let's say that you were recently hired at a new company as a developer and you wanted to get started on the project the rest of the team is working on. Github makes it very easy to do this by cloning the repository and downloading all of the files from Github to your computer utilizing this terminal command:

> $ git clone (URL goes here)

Once you have cloned the repository to your computer you now have access to all the files contained within. You begin writing code at which point Github automatically flags it as _modified_ since changes have been made after the most recent commit(save). You can check the status of the files at any time by using the terminal command:

> $ git status

If no changes to any files have been made you will have a _clean_ working directory. Files that have been modified will show up in red letting you know that they have been modified and also have not been staged and committed. You can stage a specific file or multiple files by using the terminal commands:

> $ git add filename

or

> $ git add .

The above command will add all files that have been modified.

Once all of the files you are ready to _push_ to Github have been staged you will utilize the terminal command:

> $ git commit -m "notes on changes go here"

The next step in the process is to _push_ the files from your computer to Github once they have been staged. This can be accomplished by utilizing the terminal command:

> $ git push origin master
