# 22BDO10055_labmst1
4. The task
You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git.
Hint: git switch will make you switch from one branch to another.

1.Use git branch to see the two branches that are relevant for this exercise.
2.	What branch are you on?
3.	Use git branch mybranch to create a new branch called mybranch.
4.	Use git branch again to see the new branch created.
5.	Use git switch mybranch to switch to your new branch.
6.	How does the output from git status change when you switch between the master and the new branch that you have created?
7.	How does the workspace change when you change between the two branches?
8.	Make sure you are on your mybranch branch before you continue.
9.	Create a file called file1.txt with your name.
10.	Add the file and commit with this change.
11.	Use git log --oneline --graph to see your branch pointing to the new commit.
12.	Switch back to the branch called master.
13.	Use git log --oneline --graph and notice how the commit you made on the mybranch branch is missing on the master branch.
14.	Make a new file called file2.txt and commit that file.
15.	Use git log --oneline --graph --all to see your branch pointing to the new commit, and that the two branches now have different commits on them.
16.	Switch to your branch mybranch.
17.	What happened to your working directory? Can you see your file2.txt?
18.	Use git diff mybranch master to see the difference between the two branches.

# Steps-
1.Use git branch to see the 2 branches that are already there.
2.Use git branch to see on which branch you are on.
3. git branch mybranch
4. use git branch to see the new branch created.
5. git checkout mybranch
6. Output changes when we use git status it shows we have switched from master to mybranch.
7. Workspace changes as now we can work on mybranch as we have switched on it.
8. git branch to check we are on mybranch or not.
9. touch ayushifile1.txt then vi ayushifile1.txt
10. add some text and then commit it.
11. By using git log --oneline --graph will help to see that branch is pointing to the new commit that we have done (as we added ayushifile1.txt).
12. git checkout  master
13. By using git log --oneline --graph will help to see that we have made changes on different branches.
14. use touch touch file2.txt then vi file2.txt add some text and then commit it.
15.By using git log --oneline --graph --all to see all the commit  that we have already done.
16.git checkout mybranch
17.New files are added and committed we can easily see both the files by using ls command.
18.By using git diff mybranch we can easily see the differences between both the files.


   
