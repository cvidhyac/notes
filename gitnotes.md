##git helper

### first time Git set up:

git config --list
git config --global user.name vidhya.chidambaram
git config --global user.email vidhya.chidambaram@gmail.com

### Set up IntelliJ shortcuts 

I used eclipse as my first IDE for few years, and hate the IntelliJ shortcuts in mac, especially because i type
very fast. 

* Plugins

* Maven helper - gives eclipse style maven dependency analyzer
* IDEA -> preferences -> Build and deployment menu -> Buildtools -> Maven -> Use plugin registry

* Key map shortcuts

Go to implementation - Cmd + I
Find File : Cmd + Shift + O
Find Anywhere : Cmd + Shift + F
Search within a file : Cmd + f
Replace : Cmd + R
List Methods : Cmd + F12
Prompt - Ctrl + space
Navigate back and forward from edit location : Cmd + Option + -> and cmd + Option + <-
Step into source code - Fn + F4
Format current file : Cmd + Option + L


## Other useful laptop set up notes

* Install/brew/pip all Softwares/packages
* Set up MAC LSCOLORS for better view
* Set up Git autocomplete script
* Set up PS1 entry to show directory in mac
* Set up Kerebros


Eclipse ignore settings:

Window > Preferences > Team > Ignores Resources

Patterns:
*/.git/*
.deployables
.git
.gitignore
.settings
target
mvnw
mvnw.cmd
*.class

## Git repo scripts
Refer - /notes/new_repo.sh
