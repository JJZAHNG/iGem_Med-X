create a new repository on the command line
```ssh
echo "# iGem_Med-X" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/JJZAHNG/iGem_Med-X.git
git push -u origin main
```
push an existing repository from the command line
```ssh
git remote add origin https://github.com/JJZAHNG/iGem_Med-X.git
git branch -M main
git push -u origin main
```