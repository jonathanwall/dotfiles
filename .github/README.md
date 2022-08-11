Dotfiles
===========

Install
-------
```
# clone into temp directory
git clone --separate-git-dir=$HOME/.dotfiles https://github.com/jonathanwall/dotfiles.git dotfiles

# move dotfiles into $HOME
rsync --recursive --verbose --exclude '.git' dotfiles/ $HOME/

# remove temp directory
rm -r dotfiles
```