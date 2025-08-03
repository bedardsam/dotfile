# dotfile

- [markdown cheat sheet](https://www.markdownguide.org/cheat-sheet)
- [fish for bash user](https://fishshell.com/docs/current/fish_for_bash_users.html)
- [tmux cheat sheet](https://tmuxcheatsheet.com/)
- [tmux guide](https://github.com/tmux/tmux/wiki#welcome-to-tmux)
- [tmux status line](https://arcolinux.com/everything-you-need-to-know-about-tmux-status-bar/)

for tmux clipboard
- https://github.com/tmux/tmux/wiki/Clipboard



# vim
- [comment block](https://stackoverflow.com/questions/1676632/whats-a-quick-way-to-comment-uncomment-lines-in-vim)
- [kickstart](https://github.com/nvim-lua/kickstart.nvim)

# font
- [cascadia code](https://github.com/microsoft/cascadia-code)

# tmux
- [tmux theme](https://github.com/jimeh/tmux-themepack)

for color issue sometime starting with this it works
```shell
tmux -2
```

for ssh not displaying powerline properly use below

https://stackoverflow.com/questions/67929676/tmux-powerline-symbols-not-rendering-properly-despite-having-proper-fonts-instal
```shell
tmux -u
```

reload config
```shell
tmux source ~/.tmux.conf
```
# Powershell
Start up command to use posh

```powershell
powershell.exe -noprofile -noexit -command "invoke-expression '. ''~/.config/posh/profileWT.ps1''' "
```
