# Local terminal configutration

First install TMUX and Oh_my_zsh

## BASH
- In .bash.rc add at the end
`[[ $TERM != "screen" ]] && exec tmux`


- Copy from the tmux folder the file `.tmux.conf` in the home folder

- Then copy from the zsh the file `.zshrc` to the home folder

- Finally copy the content of the `custom` forder to the `.oh-my-zsh/custom` folder


### Install Plugins:
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
