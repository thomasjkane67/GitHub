### or create a new repository on the command line

echo "# GitHub" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin https://github.com/thomasjkane67/GitHub.git
- git push -u origin master

### or push an existing repository from the command line

- git remote add origin https://github.com/thomasjkane67/GitHub.git
- git push -u origin master

### or import code from another repository

- You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

https://github.com/thomasjkane67/GitHub/import

### Add un-tracked files

- **git add <filename>** _or_ **git add .** (to add all files)
- git commit -m "first commit" .
- git push -u origin master

#### oneline

- git add .; git commit -m "commit"; git push -u origin master
- git add .; git commit -m "commit"; git push -u origin master --force
  
https://learn.sparkfun.com/tutorials/using-github-to-share-with-sparkfun/all

### Pull down files

- git pull --all

### Markdown

- https://guides.github.com/features/mastering-markdown/
