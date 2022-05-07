# zsh_config
My .zshrc config

## Installation(Mac)

1. zsh
	+ ``brew intsall zsh``
	+ ``chsh -s /usr/local/bin/zsh``
2. oh\_my\_zsh
	+ ``sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"``
3. dracula
	+ ``git clone https://github.com/dracula/zsh.git``
	+ ``mv zsh/dracula.zsh-theme ~/.oh-my-zsh/themes/dracula.zsh-theme``
	+ ``mv zsh/lib ~/.oh-my-zsh/themes/lib``
	+ [offical_installation](https://draculatheme.com/zsh)
4. zsh plugins
	+ dotenv
	+ compleat
	+ zsh-autosuggestions
		+ ``git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions``
		+ [offical_installation](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
	+ zsh-syntax-highlighting
		+ ``git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting``
		+ [install](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
	+ autojump
		+ ``brew install autojump``
		+ [install](https://github.com/wting/autojump#os-x)
