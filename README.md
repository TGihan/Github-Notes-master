# GitHub-Tutorials

<h3>1.0 Push an existing repository from the command line</h3>

1. Open git bash
2. Change the current working directory to your local project
3. git init
4. git add .
5. git commit -m "First commit"
6. git remote add origin <b>Paste Your Repository URL</b>
7. git push -u origin master
8. <b>Give username and password for GitHub</b>
 </br>
</br>
<b>Sometime you need this step before push</b> <br>
   git pull --rebase origin master

<h3>2.0 Add GIF to Readme.md
Your image should avaiable in repository as a GIF file
```
![alt tag](https://github.com/TGihan/pathto/javafxanimation.gif?raw=true)
```

# Branching
Branching is a very useful feature in github. We can create our own branch from master branch and we can commit our code changes to our new branch. If out changes have bugs those are not effect to our master branch. In this way we can manage clean and stable version of our application in master branch. When our code changes become stable we can merge it with our master branch.

Steps: (in master branch)

1. git branch "your-new-branch-name"
2. git checkout "your-branch-name" (switching to your new branch from master branch)
3. git add .

your new commits now you can puch to your new branch

#Working with branches

1. Delete a branch on your local filesystem :

   `$ git branch -d [name_of_your_new_branch]`

2. To force the deletion of local branch on your filesystem :

   `$ git branch -D [name_of_your_new_branch]`

3. Delete the branch on github :

   `$ git push origin :[name_of_your_new_branch]`

4. Create a new branch name and push origin to it (without push origin new branch name not appear in github)

   `git checkout -b [new_branch_name]`

   `git push origin [new_branch_name]`

5. See all branches and active branch

   `git branch`

# Clone specific git branch from remote repository
`git clone -b <branch> <remote_repo>`

