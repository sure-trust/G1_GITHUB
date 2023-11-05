
cd Desktop/
mkdir mini
cd mini
git clone https://github.com/PallaSwetha/pull.git
cd pull/
git status
touch demo.txt
git status 
git add .
git commit -m "modified demo file"
git status
git push origin main
git fetch origin main
git merge origin main
git pull origin main

