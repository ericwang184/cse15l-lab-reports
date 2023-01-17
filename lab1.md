# Lab 1 Report
This report will be on how to remote access, from installing VSCode to running some commands in the Terminal window

---
## Step 1: Installing VSCode

After downloading VSCode from the link [Link](https://code.visualstudio.com/), you should get a home page that looks similar to this:
![Image](VSCODE.png)
However, if you have downloaded VSCode before and already have open projects, then the last project you were working on will open. 

---
## Step 2: Remote Connecting
Since my Macbook already has git installed in Terminal, I don't need to install git again. 

In Terminal, I ran **ssh cs15lwi23aqw@ieng6.ucsd.edu**, then typed in the password I set up for this account. 

After a few seconds, the Terminal should look something like this:
![Image](ACCESS.png)

---
## Step 3: Trying Some Commands
1. ls -lat will show hidden files in the long versionthat I usually can't see, as well as the last time I edited those files.![Image](LAT.png)
2. ls -a will show the hidden files, but only the names. ![Image](LSA.png)
3. cp will copy the file. cat will concatonate a file. ![Image](CAT.png) Notice how when I used ls, hello.txt will appear. That's because I copied the file with the command **cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/**
