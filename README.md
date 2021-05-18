# imageGallery
# Author: Ravi Ranjan
# Creation_Date: 19-May-2021
# Location: Hyderabad
Dear User,

Its collection of images which I'm using during sevral projects.
Following are basic command to setup your git repo...
echo "# imageGallery" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/penseurtank/imageGallery.git
git push -u origin main

#Cheat Sheet for git command.
1. Know you branch
git branch

2. Know your all branch which is related to current repo.
git branch -a

3. To add signle file or multiple file through git command.
adding single file...
git add <file_name>
git add index.js

adding multiple file...
git add <dot: . > here dot(.) represents all new file which never been added before.
git add .

4. If you are add any file in your local projects and the time of taking pull if it is not able take pull scuessfully then apply stash command. So Stash command will remove all local change, till last pull request.
git stash
 
