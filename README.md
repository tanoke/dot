# dot

# Install vim
```
sudo apt-get install vim
mkdir ~/.vim
mkdir ~/.vim/colors
```
Clone this repo and copy .vimrc
```
git clone https://github.com/tanoke/dot.git
cd dot

#copy file .vimrc
cp .vimrc ~

#copy theme quantum material
cp quantum.vim ~/.vim/colors

```

# Install Pathogen
```
mkdir -p ~/.vim/autoload ~/.vim/bundle &&
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

# Install Vundle Vim
read and install
```
https://github.com/VundleVim/Vundle.vim
OR
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

```

## Install exuberant-ctags
```
sudo apt-get install exuberant-ctags
```

## Install plugin with vundle
```
vim .vimrc
:PluginInstall
```



