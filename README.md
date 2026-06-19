# Git Commands and Parameters
##1. Setup and Configuration
git config --global user.name "Your Name"  
git config --global user.email "youremail@example.com"  
●	Sets your name and email for commits.
git config --list  
●	Lists all configured settings.
##2. Repository Management
git clone <repo-url>  
●	Clones an existing repository to your local machine.
##3. Staging and Committing Changes
git add <file>  
git add .  
●	Stages a specific file or all changes for commit.
git commit -m "Commit message"  
●	Commits staged changes with a message.
git commit --amend -m "Updated commit message"  
●	Amends the last commit with a new message.
##4. Branching and Merging
git branch  
●	Lists all branches.
git branch <branch-name>  
●	Creates a new branch.
git checkout <branch-name>  
●	Switches to the specified branch.
git checkout -b <branch-name>  
●	Creates and switches to a new branch.
git merge <branch-name>  
●	Merges the specified branch into the current branch.
git branch -d <branch-name>  
●	Deletes a branch.
##5. Viewing History
git log  
●	Displays commit history.
git log --oneline  
●	Shows commit history in one line per commit.
git log --graph --decorate  
●	Visualizes the commit history with a graph.
##6. Undoing Changes
git reset <file>  
git reset --hard <commit-hash>  
●	Unstages changes or resets to a specific commit.
git revert <commit-hash>  
●	Reverts changes made by a specific commit.
##7. Synchronizing with Remote
git fetch  
●	Downloads changes from the remote but does not apply them.
git pull  
●	Fetches and merges changes from the remote repository.
git push origin <branch-name>  
●	Pushes changes to the specified branch on the remote.
##8. Ignoring Files
touch .gitignore  
●	Creates a .gitignore file to specify files Git should ignore.
##9. Miscellaneous Commands
git status  
●	Shows the status of changes in the working directory.
git diff  
●	Displays differences between the working directory and the index.
##Common Git Parameters
Command	Parameter	Description
git commit	-m "message"	Adds a commit message directly in the command.
git log	--oneline	Displays one commit per line.
git log	--graph	Shows a graphical representation of branches.
git push	-u origin <branch>	Sets the upstream branch for future pushes.
git reset	--hard	Resets the working directory and index to a commit.
git checkout	-b <branch>	Creates and switches to a new branch.


<img width="468" height="640" alt="image" src="https://github.com/user-attachments/assets/a6201953-9501-4238-bfec-8e5b6a546b60" />
