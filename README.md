# Exa-zsh
[Exa](https://github.com/ogham/exa) aliases plugin for zsh. 

This plugin defines useful aliases that can be used for `exa` the moden alternative of `ls`. 

## Install

1. First, Install exa 
`brew install exa`

2. clone this repository into zsh plugins folder 

```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/MohamedElashri/exa-zsh
```

3. Add the plugin to `/.zshrc`

   You should add `exa-zsh` to the plugin list 

   plugins=(... exa-zsh)

4. Restart the terminal session

## Usage 

```
# Aliases 
alias ls='exa' # just replace ls by exa and allow all other exa arguments
alias l='ls -lbF' #   list, size, type
alias ll='ls -la' # long, all
alias llm='ll --sort=modified' # list, long, sort by modification date
alias la='ls -lbhHigUmuSa' # all list
alias lx='ls -lbhHigUmuSa@' # all list and extended
alias tree='exa --tree'0 # tree view
alias lS='exa -1' # one column by just names
```

## Customization
TBA
