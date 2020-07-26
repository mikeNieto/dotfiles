# Local terminal configutration

First install TMUX and Oh_my_zsh

## BASH
- In .bash.rc add at the end
`[[ $TERM != "screen" ]] && exec tmux`


- Copy from the tmux folder the file `.tmux.conf` in the home folder

- Then copy from the zsh the file `.zshrc` to the home folder

- Finally copy the content pf the `custom` forder to the `.oh-my-zsh/custom` folder
