[click here](https://user-images.githubusercontent.com/140942003/280535665-092a85d8-1f44-43c3-84ef-57916cc18ae6.png)
cd Desktop
mkdir FForward
cd FForward
git init
echo swetha>mini_project.txt
git add .
git commit -m "from master"
git commit -m "from master2"
echo git and github>mini_project.txt
git add .
git branch feature
git checkout feature
echo swetha from feature>mini_project.txt
git add .
git commit -m "from feature"
git checkout master
git merge feature

