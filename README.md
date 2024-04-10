# my_tmux

This is a simple tmux configuration enabling to have arbitrarily many nested tmux sessions.

# Installation

```bash
 mkdir ~/.tmux.conf.d/
cd ~/.tmux.conf.d/
git clone https://github.com/aleclearmind/nested-tmux.git
mv ~/.tmux.conf ~/.tmux.conf.backup
echo "source ~/.tmux.conf.d/nested-tmux/active-row.conf" > ~/.tmux.conf
tmux
```


# Shortcuts

* `Ctrl + a`: My prefix key
* `Ctrl + a, Ctrl + c` or `Ctrl + t`: create a new window
* `Ctrl + a, Ctrl + s`: create a new nested tmux session and ask a name for it
* `Ctrl + a, Ctrl + A`: switch to last window
* `Ctrl + a, Ctrl + f`: find session
* `Ctrl + a, A`: rename current window
* `Alt + Right`: move to the next window of the current row
* `Alt + Left`: move to the previous window of the current row
* `Alt + Up`: move to the inner tmux session
* `Alt + Down`: move to the outer tmux session

