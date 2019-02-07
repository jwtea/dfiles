#TMUX Project confs

Tmux confs to setup workspaces for projects.

## Usage 

* Open tmux `tmux`;
* Source the file `tmux source-file example`

## Aliasing 

To save typing `tmux source-file example` every time you switch projects you can alias this in bash ex.

* Create bash aliases file `vi ~/.bash_aliases`
* Add alias to .bash_aliases `echo 'alias example="tmux source-file example"' >> ~/.bash_aliases`
* Make sure .bash_aliases is sourced in rc or profile `echo 'source ~/.bash_aliases' >> ~/.bash_profile`
* Source file or reload terminal

Now when you are in a tmux session just type the alias name`example` 
