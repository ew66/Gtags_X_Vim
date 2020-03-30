# Gtags_X_Vim

automated vim the file and jump to the location of the function you want to see 

## Installation
### bash

1. Put bash_edit_function to your HOME directory.

`cp bash_edit_function ~/.bash_edit_function`
  
2. Edit your ~/.bashrc then add `source ~/.bash_edit_function` in it.

`echo "source ~/.bash_edit_function" >> ~/.bashrc`

### zsh

1. Put zsh_edit_function to your HOME directory.

  `cp zsh_edit_function ~/.zsh_edit_function`
  
2. Edit your ~/.zsh_rc then add `source ~/.zsh_edit_function` in it.
  `echo "source ~/.bash_edit_function" >> ~/.zshrc`
  
## Usage
### vscode
`gcode [global parameters]`

e.g.
  - `gcode ClassABC`
  - `gcode -r methodABC`
  - `gcode -s VariableABC`
  
### vim
`xvim [global parameters]`

e.g.
  - `xvim ClassABC`
  - `xvim -r methodABC`
  - `xvim -s VariableABC`

