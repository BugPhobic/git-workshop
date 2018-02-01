# Intro
This is a little guide to help you get introduced to git. 
`Anything that looks like this should be executed in the terminal.`
# Part 0: Setup
1. Install git: https://git-scm.com/download
2. Set user info (needed before you can commit)
    * `git config --global user.email "you@example.com"`
    * `git config --global user.name "Your Name"`
3. Create github account with your Brock email: https://github.com/
4. Get your github education pack: https://education.github.com/pack 

# Part 1: Working Locally
1. Create a folder called "git-stuff".
2. Create a text file in that folder.
2. Open either git bash or cmd, and navigate to your folder
3. `git init`
4. `git add file.txt`
5. `git commit -m "Created file"` (Creates a commit with the given commit message)
6. Open file.txt and type "Hello World". Save, close.
7. `git diff` (Shows the difference between your working directory and the git repo)
9. `git add .` (Adds files in the current directory)
10. `git status` (Shows the changes that will happen when you commit)
11. `git commit -m "Added text"`

# Part 2: Working with Github
1. Go to github and create a new project: https://github.com/new
2. Name it something descriptive, and make it private (So you can control who sees it), then click "Create repository"
3. The page you go to gives you instructions on how to push an existing repository (the one you created earlier)
4. `git remote add origin https://github.com/Jesse-longname/something-descriptive.git`
5. `git push -u origin master` (When you push, it will ask you to sign in)
6. Refresh the github page with the instructions. Your repo should be there!
7. Locally, add a new file and put some text in it.
8. Add it to your repo, and commit it. 
9. `git push` (Pushes the repo to github)
10. Refresh your github repo page, and you'll see the new file on it
11. On your repo in github, click "Create new file". Name it something, give it some contents, and create it.
12. Now we will get it onto your computer
13. `git pull`
14. Go to your folder, and you will see that the new file is there

