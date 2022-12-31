First steps to follow while working locally --


* echo "# git-practice" >> README.md   ---- creates a file called README.md and appends '# git-practice' to it
* git init   --- initializes the repository for git, from this point every change to this directory will be watched/tracked by git locally, which is considered as working directory
* git add README.md   --- the file is ready to track and added to the staging directory, which is a temporary location which ensures everything is set to go
git commit -m "first commit"  --- file is commited and this version of the file will be saved permenantly
git branch -M main   --- by default git creates the branch in master, this command moves everything/ renames it  to main
git remote add origin https://github.com/Skandesh/git-practice.git
git push -u origin main