# Mini Project:

**Problem Statement:** Follow the instructions given and give the commands used to carry out given instructions.

1. List all the files of your desktop
2. Make a new folder named "Assignment_1"
3. Go into the folder
4. Initialize a git repository
5. Create a branch called 'development_feature'
6. In the main/master branch, create a simple text file named main.txt (and the content - "your name and from main branch"
7. In the development_feature branch, create a simple text file named main.txt (and the content - "your name and from development_feature branch"
8. Commit your changes in both branches.
9. Now, your task is to perform a fast-forward merge from the feature branch into the main branch.


# Submission:

1. List all contents of desktop(home) with hidden files.
```
ls -a
```
<img width="406" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/62392ba4-a6d9-4bcd-a7fa-9d364e65b4af">


2. New folder with name "Assignment_1".
```
mkdir Assignment_1
```
<img width="407" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/e9cbc4fc-5dae-4a06-977d-a94b3951f571">


3. Enter into the folder.
```
cd Assignment_1
```
<img width="405" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/0ffef942-99b4-4f96-a899-443dec4c0b9f">


4. Initialize a git repository.
```
git init
```
<img width="406" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/ee82527e-e392-4297-870c-e47aff1dc842">


5. Create 1 branch known as "development_feature"
```
git checkout -b development_feature
```
<img width="407" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/88cdee52-2f4f-4bd1-a478-6ee73b3efa14">


6. In the main/master branch, create a simple text file named main.txt (and the content - "your name and from main branch")
  - First checkout to main branch
  - Create a new file
  - Edit it as specified
  - Save, stage and commit changes 
```
git checkout main
vim main.txt
```
```
git add main.txt
git commit -m "From main branch"
```
<img width="404" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/20417e27-67e9-4759-800f-bb902f8cddf7">


7. In the development_feature branch, create a simple text file named main.txt (and the content - "your name and from development_feature branch")
   - First checkout to development_feature branch
   - Create a new file
   - Edit it as specified

8. Save, stage and commit changes
```
git checkout development_feature
vim main.txt
```
```
git add main.txt
git commit -m "From development_feature branch"
```
<img width="406" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/ee95adac-768a-4378-824f-932b8cbfafda">


9. Fast forward merge from `development_feature` branch to `main` branch
```
git checkout main
git merge development_feature
```
<img width="406" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/73bb5935-7dbf-42d1-9e29-f08521874455">


### Checking the log to see commit history
```
git log
```
<img width="407" alt="image" src="https://github.com/devchadha-jmi/G1_GITHUB/assets/82091082/042ed77d-d9f5-4a34-92cd-349dd650b525">
