# demo
This is a demo repo to understand the git and github
<br>
This is to commit from the github...
<br>
This is a change from local
<br>

# Git commands:-
<br>
git config --global user.name "user name"
<br>
git config --global user.email "user email@gmail.com"
<br>

git config --list
<br>
git clone <link>
<br>
git status
<br>
git add filename (for each file)
<br>
git add . (for multiple files)
<br>
git commit -m "some message"
<br>
git log (lists out all the commits)
<br>
git push origin main
<br>

git init (to make local folder to git repository)
<br>
git remote add origin <link> (to link remote repository to local folder)
<br>
git branch (to check current branch and also lists all the branches that are available)
<br>
git branch -M main  (to rename branch)
<br>
git checkout -b <new branch name> (to create new branch)
<br>
git checkout <branch name> (to navigate to other branch)
<br>
git checkout -d <new branch name> (to delete new branch)
<br>
git push origin <branch name> (to push the files from local to remote or github)
<br>
	or
<br>
git push -u origin main (-u stands for declaring the next operations are origin main)
<br>


git diff <branch name> (to compare branches,commits,files and more)
<br>
git merge <branch name> (to merge two branches)
<br>

git pull origin <branch name> (to fetch and download the content from remote or github to local)
<br>



Undoing Changes
<br>
Case 1(added but not commited):<br>
	git reset <file name> (for specific file)<br>
	git reset (all the files)<br>

Case 2(Commited changes for one commit):<br>
	git reset HEAD~1<br>

Case 3(Commited changes for multiple or many commits):<br>
	git reset <commit hash> (through git log we can find the commit hash)<br>
	git reset --hard <commit hash> (the changes also results in the vscode)<br>