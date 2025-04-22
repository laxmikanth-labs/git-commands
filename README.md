What is Git?
Git is a version control system. It helps developer to track and manage changes to their code over time. Its run locally on your machine  and you don’t need internet to use git itself

	1. Commit your works
	2. Go back to earlier version
	3. Work on new feature in branches without messing up the main code
	4. Collaborate with others without overwriting each other works.

What is GitHub?

GitHub is a platform/website where you can store your git repositories online. It adds powerful tools  for collaborations. GitHub basically host your code and add team work feature on top of git.

	1. Sharing code with others
	2. Managing issues and bugs
	3. Create pull request
	4. Track who changed and what and why

The default important coding

Git -v / --version
Git -h / --help


echo "# git-commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/laxmikanth-labs/git-commands.git
git push -u origin main


Git init  this commands states that any changes of this folder will track the changes




> Git init
Create any index.html file and some content in the file
> Git add index.html
> Git commit -m "add index file"

> git remote add origin https://github.com/laxmikanth-labs/git-commands.git
> git push -u origin main'

Now your code backup to online.

Command	What it does
git init	Start tracking a folder with Git
git status	See what’s changed
git add .	Stage all changes
git commit -m "message"	Save a snapshot with a message
git log	View commit history
git branch	List branches
git checkout -b new-feature	Create and switch to a new branch
git push	Upload your code to GitHub
git pull	Download the latest from GitHub

Checkout command is used to change the current branch focus
Merge command is used to merge the source and target branches

git checkout main
git checkout -b cool-feature
git merge cool-feature

Delete the branch from local or remote by the use the below commands

git checkout main
git branch -d branch-name
git branch -D branch-name

-d = delete safely (only deletes if it’s already merged into main)

git push origin --delete branch-name
git push origin --delete feature/contact-form

git branch         # Shows local branches
git branch -r      # Shows remote branches
git branch -a      # Shows all (local + remote)
![image](https://github.com/user-attachments/assets/9a78fc75-df79-4092-9112-8511fecea12f)
