# oh-my-zsh-theme
Customized oh-my-zsh theme 

__install (oh-my-)zsh with:__
```
sudo apt update && apt install zsh git curl -y
sudo sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" -y
chsh -s $(which zsh) $(whoami)
```

__install with theme:__
```
curl -H "Accept: application/vnd.github.v3.raw" https://api.github.com/repos/ChielWH/oh-my-zsh-theme/contents/my.zsh-theme >> ~/.oh-my-zsh/themes/my.zsh-theme
sed -i 's/ZSH_THEME="robbyrussell"/ZSH_THEME="my"/' ~/.zshrc
source ~/.zshrc
```
