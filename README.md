# GIT_Assessment

7.23.18 Homework

Know the following:  
* Why do we use Git?  
    We use Git to allow many programmers on a team make revisions to files/projects.  It is a VCS.  
* What is the difference between Git and GitHub?  
    Git is a Version Control System in which you can make revisions and commit them.  GitHub is a web based service that acts as a "hub" or space to hold backups of Git repositories.  
* How does Git work?  
    Git works by adding file versions to repositories.  You can make changes to a file and then commit those changes as a new version of the file to a repository.  You can then push the new commit to GitHub.  
* What is a Git repository?  
    A Git repository is a directory on your computer's file system that has been initialized with the Git VCS.  
* Initialize a Git repository.  
    cd the directory and git init.  
* Add and commit changes to a Git repository.
    git add + file name. git commit -m 'with a message'  
* Add remote destinations to your local Git repository.  
    git remote add origin + destination  
* push commits from your local Git repository to a remote repository.  
    git push -u origin master  

Explain and be able to do the following:  
* Fork and Clone:  To fork a project is to make a copy, rename it, and create a new project from that copy.  To clone is to make a copy of the original and add it to a local repository to make changes.  
* 'git add' :  add a file (git add filename) that is brand new to a local directory. You can also add all new changes and files with a period (.) after git add.  
* 'git push' :  pushes the commit to the defined current remote directory.  
* 'git commit -m 'Some message' :  commits the changes to a file and includes a message about what changes were made.  
* 'git push origin master' : pushes the commit to the defined origin master remote directory.  
* 'git remote -v' : This shows the url of the remote directory.  
* 'git status' : This shows the status of your commit to show staged or unstaged changes.  
* 'git remote add [remote url here]' : adds a remote named for the repository at the specific url.  
* 'git remote remove origin': removes the remote origin.
