# Disclaimer
This document is a work in progress. It is a place where I, Marco Guardigli, mgua@tomware.it organize my notes about use configuration of Windows Terminal


# Introduction
what is a terminal application

windows terminal: an open source from Microsoft
settings for windows terminal, to access local and remote resources, like terminal applications, local WSL, remote servers, WSLs on other computers


## Windows terminal installation and upgrades


## Windows terminal configuration management


## Font setup
- non ascii characters considerations
- nerdfonts

## curses/ncurses support
- gmc: GNU midnight commander
- far manager

## Session management tools
- screen
- tmux


## clipboard considerations
OSC52
integration with text editors (vi/vim/neovim)
copy/pasting from local to remote
copy/pasting from remote to local
with tmux
with nvim
with nvim inside tmux
emacs?


## Applications
Windows terminal allows interactions with local character based applications, like local CLI (Command Line Interaction) shells like CMD, BASH, PWSH, etc...
- local Windows CMD command prompt
- local powershell
- powershell with oh-my-posh integration
- powershell with psprofile

### local git bash
set Command Line to 
```
    C:/Users/mgua/AppData/Local/Programs/Git/bin/bash.exe -i -l
```
last options are dash lowercase "I" and dash lowercase "L"

### local cygwin
set Command Line to 
```
    C:\cygwin64\bin\mintty.exe -i /Cygwin-Terminal.ico -
```
set icon path to:
```
    C:\cygwin64\Cygwin.ico
```
thanks to this post by Paul Trancone: https://www.commandlinewizardry.com/post/how-to-add-git-bash-to-windows-terminal#:~:text=You%20can%20easily%20add%20this%20emulator%20to%20Windows,or%20a%20similar%20title%20in%20the%20%22Name%22%20field. 


###` local vim/neovim

### Local WSLs

### remote SSH hosts unix/linux

### remote windows with ssh server
Installation and configuration issues
winget across terminal session


### WSLs on remote windows machines


## Editing files thru terminal
Console text file Editing tools
copy file across terminal sessions: sz/rz oldstyle tools
midnight commander, far manager
ssh links


## ssh port management features
multiple hops
tunneling connections
reverse connections



## other tools
console sessions over serial
putty
kitty
teraterm
tools for arduino or similar microcontroller serial integration
serial over tcp: port servers

## Integrating Windows Terminal with other applications
- vscode
- vim
- neovim
- 

