
# Exa-zsh Plugin

[Exa](https://github.com/ogham/exa) aliases plugin for zsh.

This plugin defines useful aliases that can be used for `exa` the moden alternative of `ls`.



## Installation 
This plugin is written with MacOS in mind. but it should work on any unix based OS.

1. First, Install exa 

```bash
brew install exa
```
2. Clone this repository into zsh plugins folder 
   ```bash
    cd ~/.oh-my-zsh/custom/plugins
    git clone https://github.com/MohamedElashri/exa-zsh
   ```
 or 

```bash
cd $ZSH_CUSTOM/plugins/
git clone https://github.com/MohamedElashri/exa-zsh
```
3. Add the plugin to `/.zshrc`

   You should add `exa-zsh` to the plugin list 

   `plugins=(... exa-zsh)`

4. Restart the terminal session














## Screenshot

Insert gif or link to demo

  
## Usage/Examples
This project contain some useful aliasses that you can run in your terminal that zsh supported like `Iterm2`. 

You can type in the alias in your terminal. This is a list of available aliasses.


| Alias | Command            | Help                                                     |
|:-----:|:------------------:|:--------------------------------------------------------:|
| ls    | exa                | just replace ls by exa and allow all other exa arguments |
| l     | ls -lbF            | list, size, type                                         |
| ll    | ls -la             | long, all                                                |
| llm   | ll --sort=modified | list, long, sort by modification date                    |
| la    | ls -lbhHigUmuSa    | all list                                                 |
| lx    | ls -lbhHigUmuSa@   | all list and extended                                    |
| tree  | exa --tree         | tree view                                                |
| lS    | exa -1             | one column by just names                                 |

  
## Contributing

Contributions are always welcome!

Pull requests are welcome. I will try to they are compatible. 

Please make sure to update tests as appropriate.


  
## Authors

- [@MohamedElashri](https://www.github.com/MohamedElashri)

  
## License

[MIT](https://choosealicense.com/licenses/mit/)

  