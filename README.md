# Git Testing Repository
I use this repo for testing out my knowledge on git and submitting code remotely to GitHub.

# Cloning a repository using git
Working in the terminal in VS Code I used the command 
'$ git clone https.....' and I copy and pasted the HTTPS link from GitHub connect my local repository remotely 

# Pushing a file to GitHub in git
$ git status

$ git add git-test.js

$ git status
    On branch main
    Your branch is up to date with 'origin/main'.

    Changes to be committed:
      (use "git restore --staged <file>..." to unstage)
            new file:   git-test.js
  
$ git commit -m "first commit test"
  
    [main 603d5a3] first commit test
    1 file changed, 1 insertion(+)
    create mode 100644 git-test.js  
    
$ git status
     On branch main
     Your branch is ahead of 'origin/main' by 1 commit.
       (use "git push" to publish your local commits)

     nothing to commit, working tree clean 
     
$ git push
