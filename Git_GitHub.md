## Git & GitHub

**GIT:**
- To store the source code of each version separately to rollback.
(rollback means to go back to the previous version)
- It is also known as VCS (Version Control System) and SCM (Source Code Management)
- Git is 3td generation of VCS.
- It is platform independent, Free and Open-Source.
- It is written on c-programming and it came on year 2005

**Architecture/Stages:**
1) Working Directory: Where we write the code.
2) Staging Area: Where we track the code.
3) Repository: Where we store the code.

**Git Branch:**
- Branch is an individual line of development.
- It is used to write the code individually on their individual branches.
- The default branch in git is master.
(we need an initial commit to get master branch)
Note: Whenever we create a new branch all files from current branch will carry forward to next branch.

**GitHub:**
- It is an internet based platform to organize the code.
- We can write code on local and then push it to GitHub.
- From GitHub, we can make our code accessible to our team-mates

**Commands:**

1) Install Git <br>
*#Yum install git*

2) To install local repo (.git)<br>
*#git init*

3) To track a file<br>
*#git file_name*

4) To commit a file<br>
*#git commit -m "initial commit" file_name*

5) To check file is tracked or not<br>
*#git status*

6) To show commits<br>
*#git log*

7) To show commits history in one line<br>
*#git log --oneline*

8) To list branches<br>
*#git branch*

9) To create a branch<br>
*#git branch branch_name*

10) To switch from one branch to another branch<br>
*#git checkout branch_name*

11) To create and switch to branch at a same time<br>
*#git checkout -b branch_name*

12) To rename a branch<br>
*#git branch -m old_name new_name*

13) To delete a branch<br>
*#git branch -D branch_name*

14) To connect git with github<br>
*#git remote add origin https://repo_link*

15) To push the branch<br>
*#git push origin master(branch_name)*

16) To merge files from one branch to another branch (public_repo)<br>
*#git merge branch_name2*

17) To merge files from one branch to another branch (private_repo)<br>
*#git rebase branch_name2*

18) To revert merged branch (public_repo)<br>
*#git revert branch_name*

19) To reset the branch (private_repo)<br>
*#git reset branch_name*

20) To set username<br>
*#git config user.name "name"*

21) To set email address<br>
*#git config user.email "user@mail.com"*

22) To show the number of files attached for a commit<br>
*#git show*

23) To show details about commit<br>
*#git show commit_id*

24) To merge specific files<br>
*#git cherry-pick commit_id*

25) To get back deleted files<br>
*#git restore file_name*

26) To clone repo from github<br>
*#git clone https://repo_link*