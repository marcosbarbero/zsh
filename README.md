ZSH installation
---

Step 1
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Step 2
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Step 3
```
vim ~/.zshrc

setopt hist_ignore_alldups hist_ignore_dups share_history inc_append_history extended_history

HISTSIZE=99999
SAVEHIST=99999
```

Step 4 - Set zsh as default
```
chsh -s $(which zsh)
```