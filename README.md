# oh-my-zsh-theme
Customized oh-my-zsh theme 

__install (oh-my-)zsh with:__
```
sudo apt update && apt install zsh git curl -y
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" -y
chsh -s $(which zsh) $(whoami)
```

__install with theme:__
```
curl -H "Accept: application/vnd.github.v3.raw" https://api.github.com/repos/ChielWH/oh-my-zsh-theme/contents/my.zsh-theme >> ~/.oh-my-zsh/themes/my.zsh-theme
sed -i 's/ZSH_THEME="robbyrussell"/ZSH_THEME="my"/' ~/.zshrc
source ~/.zshrc
```

__handy plugins:__
```
omz plugin load git
omz plugin load pip
omz plugin load python
omz plugin load docker
omz plugin load docker-compose
omz plugin load celery

omz plugin enable git
omz plugin enable pip
omz plugin enable python
omz plugin enable docker
omz plugin enable docker-compose
omz plugin enable celery
```
