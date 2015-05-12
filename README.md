# dotfiles
My config for OSX.

Don't use any scripts for now.

## Install
In `home` folder clone this repository in default folder (which should be `dotfiles`, the name of the repo).
Then pull all the submodules and launch zsh setup.
```bash
cd ~ && git clone git@github.com:superguigui/dotfiles.git && cd dotfiles
git pull && git submodule init && git submodule update && git submodule status
sh setup-zsh
```
