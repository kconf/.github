## Application Configurations 👋

Manage application configurations using [vcsh](https://github.com/RichiH/vcsh) and [myrepos](https://myrepos.branchable.com/).

### [Install](https://github.com/RichiH/vcsh/blob/main/doc/INSTALL.md)

~~~ bash
brew install vcsh mr         # macOS
sudo pacman -S vcsh myrepos  # ArchLinux 
~~~

### Add a new config

~~~ bash
vcsh init vim
vcsh vim add ~/.vimrc ~/.vim
vcsh vim commit -m 'Initial commit of my Vim configuration'
# optionally push your files to a remote
vcsh vim remote add origin <remote>
vcsh vim push -u origin master
# from now on you can push additional commits like this
vcsh vim push
~~~
