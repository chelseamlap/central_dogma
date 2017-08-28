This is a test file."# central_dogma" 

Steps for using GIT with files on your computer
1. Make the folder (local respository) on your desktop (mkdir -p)
2. Add a README.md or README.txt file explaining what the repository is for
3. Make the repository on GITHUB
4. Use the commands below to sync the repository with github

Initialize
Add (readme)
Commit -m (commit w/message)
remote add origin (add origin / master branch to location in github -- will be prompted for password)
push -u [git push [remote-name] [branch-name]]

echo "# central_dogma" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:chelseamlap/central_dogma.git
git push -u origin master