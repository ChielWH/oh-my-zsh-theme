# oh-my-zsh-theme
Customized oh-my-zsh theme 

__install with:__
```
apt update && apt install zsh git curl -y
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" -y
chsh -s $(which zsh) $(whoami)
curl -H "Accept: application/vnd.github.v3.raw" https://api.github.com/repos/ChielWH/oh-my-zsh-theme/contents/my.zsh-theme >> ~/.oh-my-zsh/themes/my.zsh-theme
sed -i 's/ZSH_THEME="robbyrussell"/ZSH_THEME="my"/' ~/.zshrc
source ~/.zshrc
```
