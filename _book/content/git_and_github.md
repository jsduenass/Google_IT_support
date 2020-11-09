
# Intro to git
git is a **version control software** that allows manage the changes made to a code project. it does so by creating a repository and saving different version by a commit where

## knowing the shell
git is an application that is tipicaly interacted with via Command Line Interface (CLI), this might or might not be your first time in front of a (CLI) there are of course tools than help you and give you a graphical interface but they can limit your ability and control on what you can do because you don't understand the work that is going behind the scenes. I would advise you to try the command line and give it a shot. without further to do let's start.

access the git shell by searching for it in the windows search bar

![gitBash](images/git_and_github/openingGitBash.png )

Once in the  shell try typing or the following commands. __Note:__ inside the command line the # symbol means the begining of a comment the machine will ignore everthing that is after it.
 
```shell
    # getting to know the command line 
    
	# where am i?
    pwd
	
	# look around ls show you the folder you are in
	ls
	
	# new folder 
	mkdir  my_folder
	
	# change directory
	cd ./my_folder
	
```

the shell is like your file browser  the command `pwd` prints the working directory you are on,  `ls` shows a the files inside the folder and `cd` allows to change the folder. this are basic terminal command if you want to know more you can find a more in depth dive [here]().


### config a git user 
In order to start using git the first thing that needs to be set is a username and a email, git use them in the commit process in order to generate a a unique number (hash) to each state of the project.

once inside the shell we config the user name and a asociated email

```shell
    git config --global user.name "yourName"
    git config --global user.email "yourmail@address.com"
```

### starting a repository

Move to the folder here you are hosting your code project

```shell
    cd "~/MyProyect"
    git init 
```

In order to check that the repository was succesfully created  run the following command and you should be able to see a  *.git*  folder

```shell
    ls -a
```

### create your first commit

To add the file you want to keep track of you simply list them with the following command or use the `.` symbol to select them all. if you want to just add the files contained you put the folder name in the command instead, if you want all the files with a certain  or 

```
    git add [files names]
    git add .                       # for all 
	git add [folder name]
	git add *.txt 
```

### using ssh 

```
    ssh-keygen -t rsa -b 4096 -C "yourmail@address.com"
    eval $( ssh-agent -s)         esta corriendo el agente ssh
    ssh-add ~/.ssh/id_rsa 
```



# github time to get remote



a adding an existing local repository to an empty remote repo.
```
	git remote add origin [remote repo URL]
	git push -u origin master
```


```


    # git config --global user.name ""
    # ssh-keygen -t rsa -b 4096 -C "jsduenass@unal.edu.co"
    # eval $( ssh-agent -s)         esta corriendo el agente ssh
    # ssh-add ~/.ssh/id_rsa
    # configurate github send public key
    #  git log --stat
    # git status
    # git diff [commit_id] [commit_id]
    # git checkout [commit_id]
    # git reset HEAD quita los archivos de stage
    # git clone [url]
    # git push enviar
    # git fetch
    # git merge
    # git pull = fetch + merge
    # branch experiment  rama experimental
    # git switch experiment
    # git  remote add origin  [url] 
    # git remote -v
    # git push origin master     git push [to_there] [from_here]
    # git pull origin master    git pull [from_there] [to_here]
    # git pull origin master --allow-unrelated-histories
    # git remote set-url origin [ssh direction] git@github.com:jsduenass/CRUD_app.git
    # alias git_history=git log --all --graph --decorate --oneline
    # git tag -a v0.1 - m "commint message" [commit_id]
    # git tag -d [tag_name]
    #git push origin --tag

    # gitk show branch history
    # git remote upstream

    #terminal.integrated.shell.* can only be defined in user settings and not at workspace scope
    #git config --global core.editor "code"
    # git clone [url]

    # git branch -r         ramas remotas
```

