# Git and Github Notes
### If you want, you can contribute

<br>

## __ACTUAL MY DAILY USES GIT COMMANDS:__

---

### __Directory Command:__
```
mkdir       #For making directory
cd          #For switching directory
touch       #For makin file
ls -a       #For See list of files folder
```

### __Git Config Command:__
```
git config --global user.name   #For config user name global
git config --global user.email  #For config email global
git config --list               #For see config list
```
```
Notes: if you want to change, user.name and user.email you can change it. just use same command and entry new data.
```

### __Basic (Git Command):__
```
git init                #For initialize
git status              #For status check
git add .               #For add all
git commit -m           #For commit
&&                      #For multiple command run at the same time (if possible)
git commit -am          #For add & commit
git restore             #For restore before add & commit
git diff                #For check changing before add & commit
git log                 #For commit history check (details)
git log --oneline       #For commit history check (short)
```

### __branch (Basic Git Command):__
```
git branch              #For branch list check
git checkout -b         #For branch making & switching
git checkout -d         #For branch deleting
git checkout            #For move into any commit & branch
git merge               #For branch merging
```

### __Remote & Local Connection (Basic Git Command):__
```
git remote              #For check are remote repo available?
git remote -u           #For remote repo connect wit local repo
git branch -M master    #For rename remote repo branch name main to master
git push                #For push repo default branch
git push -u             #For push repo fixed branch
git clone               #For repo clone into local
git pull                #For local repo update with remote repo changing
```

### __.gitignore file:__
```
fileName.fileExtention (test.txt)       #For this file ignore
.fileExtention (.env)                   #For .env file ignore
*.fileExtention (*.txt)                 #For txt file ignore
!fileName.fileExtention (!test.txt)     #For ignore all txt file  without it
fileName?.fileExtention (test?.txt)     #For just ignore test.txt file without all (means: test1.txt)
folderName/ (folder/)                   #For folder ignore

```