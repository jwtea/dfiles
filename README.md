# Configs

## Tools

- Docker
- Node
- Php 7.2
- Xcode
- Git
- vsCode
- Unity
- Chrome
- Firefox
- Adobe suite
- Epic games Launcher
- OBS
- Golang
- Elixir

## Tmux

Tmux config file .tmux.conf

### Requirements

- [tmux plugin manager](https://github.com/tmux-plugins/tpm) `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`
- [tmux-mem-cpu-load](https://github.com/thewtex/tmux-mem-cpu-load) `brew install tmux-mem-cpu-load`
- Install plugins ctrl+b `I`

### TMUX Project confs

Tmux confs to setup workspaces for projects.

#### Usage

- Open tmux `tmux`
- Source the file `tmux source-file example`

#### Aliasing

To save typing `tmux source-file example` every time you switch projects you can alias this in bash ex.

- Create bash aliases file `vi ~/.bash_aliases`
- Add alias to .bash_aliases `echo 'alias example="tmux source-file example"' >> ~/.bash_aliases`
- Make sure .bash_aliases is sourced in rc or profile `echo 'source ~/.bash_aliases' >> ~/.bash_profile`
- Source file or reload terminal

Now when you are in a tmux session just type the alias name`example`
