# Git Intro  

---

Version Control is a system that allows you to revisit various versions of a file or set of files by recording the changes. This is very similar to commiting the changes on your Github document, except you can do it locally. It is very useful for co-collaberating with other coders on a single project.  

This also eliminates the risk of the server going down, and no-one being able to work until it is restored.  

## What is Git?  

---

Git is a DVCS that stores data in a file system made up of snapshots. Every time you commit a change to your file, you are creating a new snapshot. This is useful in case something goes wrong and you need to restore it to a previous version.  

Git works in three different stages.  

-**Committed**-Data is securely stored in a local database

-**Modified**-File has been changed but not committed to the database  

-**Staged**-Flagged a file’s changed version to be committed in the next snapshot  
![GitDiagram](GitDiagram.png)  

## Working with Git and Github

---

1. First step is to clone your repository from Github. To do this you will need to copy the code of said repository off of Github. Go into your Terminal and use the command "git clone (your repository URL)"  
2. Next step is to make any changes you want to locally.  
3. To update your work on the server you must next open your terminal back up. Input the command "git add ." This will add all of the changes you have made.  
4. Next input git commit -m"". In between the quotes you want to write a short message describing what changes you made.  
5. Finally input "git push main origin". This will update Github with the current work you have completed.



