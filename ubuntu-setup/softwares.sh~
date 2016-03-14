#zsh
sudo apt-get install zsh -y

sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"


# It adds two context menu items in nautlius so you can right click and choose "Resize Image". (The other is "Rotate Image").
sudo apt-get install nautilus-image-converter

sudo apt-get install vim

# Installing spotify http://ubuntuhandbook.org/index.php/2014/04/install-spotify-ubuntu-14-04/

wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -

sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'

sudo apt-get update ; sudo apt-get install google-chrome-stable -y

#docker
wget -qO- https://get.docker.com/ | sh
sudo usermod -aG docker $USER

#docker compose
sudo touch /usr/local/bin/docker-compose && sudo chown $USER /usr/local/bin/docker-compose
curl -L https://github.com/docker/compose/releases/download/1.5.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose

#atom
sudo add-apt-repository ppa:webupd8team/atom
sudo apt-get update
sudo apt-get install atom -y

#atom plugins
apm install atom-beautify
apm install atom-typescript
apm install atom-visual-studio-code-ui
apm install color-picker
apm install editorconfig
apm install file-icons
apm install git-plus
apm install highlight-selected
apm install language-docker
apm install language-html-swig
apm install language-nginx
apm install linter
apm install linter-eslint
apm install linter-csslint
apm install linter-scss-lint
apm install minimap
apm install minimap-cursorline
apm install minimap-find-and-replace
apm install minimap-git-diff
apm install minimap-highlight-selected
apm install minimap-linter
apm install minimap-selection
apm install minimap-split-diff
apm install react
apm install split-diff
apm install sync-settings
apm install tabs-to-spaces
apm install terminal-panel
apm install todo-show
apm install visual-studio-dark-syntax
apm install webbox-color


#terminator
sudo add-apt-repository ppa:gnome-terminator

sudo apt-get update

sudo apt-get install terminator -y

#git
sudo apt-get install git-core -y

git config --global user.name "Mauricio Minella"
git config --global user.email "mauriciominella@gmail.com"
git config --global core.editor atom
git config --global core.autocrlf input

#ssh-keygen -t rsa -C "mauriciominella@gmail.com"

#cat ~/.ssh/id_rsa.pub

#node
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash

echo ". ~/.nvm/nvm.sh" >> ~/.zshrc

source ~/.zshrc

nvm install stable

nvm use stable

n=$(which node);n=${n%/bin/node}; sudo chmod -R 755 $n/bin/*; sudo cp -r $n/{bin,lib,share} /usr/local
