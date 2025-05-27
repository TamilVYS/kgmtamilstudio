Pushing first file from cmd to GitHub
<<<<<<< HEAD

Commands:
git clone https://github.com/TamilVYS/kgmtamilstudio.git
git status
del .git
git status
git init
git status
git add sample.txt	
git status
git diff
git commit -am "updated"
git branch -M main
git remote add origin https://github.com/TamilVYS/kgmtamilstudio.git
git push -u origin main

don't want to track a file:
touch test.txt
touch .gitignore
echo "text.txt" > .gitignore
git add .
git commit -am "updated"
git push -u origin main

if another developer changed the file, we need to pull:
git pull origin main
git add .
git commit -m "resolved merge conflict"
git push -u origin main