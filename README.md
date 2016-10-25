My tmux configuration

### Install tmux

```bash
$ sudo apt-get install tmux
```

### Install dependency

```bash
$ sudo apt-get install xsel
```

### Configuration

```bash
$ cd
$ rm .tmux.conf
$ git clone https://github.com/jarsonfang/tmux.git
$ ln -s tmux/tmux.conf .tmux.conf
```

add the following line to `~/.bash_aliases` file and then `source ~/.bash_aliases`:
```bash
alias tmux='tmux -2'
```
