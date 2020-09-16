# Macbook setup

### first time Git set up:

```
git config --list
git config --global user.name vidhya.chidambaram
git config --global user.email vidhya.chidambaram@gmail.com
```

### IntelliJ Customizations

I used eclipse as my first IDE for few years, and windoze user for many, many years.
Hence, I prefer a two-key approach vs three-key on my mac book. 

### IntelliJ Plugins

* Maven helper - gives eclipse style maven dependency analyzer
* Rainbow Brackets
* KeyPromoter X
* IDEA -> preferences -> Build and deployment menu -> Buildtools -> Maven -> Use plugin registry

## Key map shortcuts

| Function | Value to change in Keymap preferences |
|--------|----------|
| Go to implementation | Cmd + I|
| Find File | Cmd + Shift + O|
| Find Anywhere | Cmd + Shift + F|
| Search within a file | Cmd + F|
| Replace | Cmd + R|
| List Methods | Cmd + F12|
| Autocomplete | Option + space|
| Navigate back forth in tabs | Cmd + Option + -> and cmd + Option + <-|
| Step into source code | Fn + F4|
| Format the current file | Cmd + Option + L |
| Remove Unused imports | Option + o |
| Debugger | Fn + F8, Fn + F9 |


## Other useful laptop set up notes

* Install/brew/pip all Softwares/packages
* Remember to Set up MAC LSCOLORS for better view
* Remember to Set up Git autocomplete script
* Remember Set up PS1 entry to show directory in mac
* Set up Kerebros (if the company provides one)

## SSH tool
iterm (Ctrl + D for vertical split)

## Eclipse ignore settings:

Window > Preferences > Team > Ignores Resources

### Ignore Patterns
```
*/.git/*
.deployables
.git
.gitignore
.settings
target
mvnw
mvnw.cmd
*.class
```


## Git repo scripts
Refer : [github_shortcuts.md](github_shortcuts.md)

## Brew packages
Refer : [brew_dump.md](brew_dump.md)

## SDKMan
Refer : [https://sdkman.io/install](https://sdkman.io/install)