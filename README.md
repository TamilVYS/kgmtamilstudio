Pushing first file from cmd to GitHub<br>
<<<<<<< HEAD
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
=======
<br>
Commands: <br>
git clone https://github.com/TamilVYS/kgmtamilstudio.git <br>
git status <br>
del .git <br>
git status <br>
git init <br>
git status <br>
git add sample.txt <br>
git status <br>
git diff <br>
git commit -am "updated" <br>
git branch -M main <br>
git remote add origin https://github.com/TamilVYS/kgmtamilstudio.git <br>
git push -u origin main <br>
<br>
don't want to track a file: <br>
touch test.txt <br>
touch .gitignore <br>
echo "text.txt" > .gitignore <br>
git add . <br>
git commit -am "updated" <br>
git push -u origin main <br>
=======
>>>>>>> b8a9674a17c6a877e1e71f7c606297b26dac3f73
