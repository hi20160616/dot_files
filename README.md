```
cd ~/Git && git clone https://github.com/hi20160616/dot_files.git
mv ~/.zshrc ~/.zshrc_original
ln -s ~/Git/dot_files/dot_zshrc ~/.zshrc
mkdir -p ~/.config/i3
mv ~/.config/i3/config ~/.config/i3/config_original
ln -s ~/Git/dot_files/dot_config/i3/config ~/.config/i3/config
mkdir -p ~/.config/alacritty
mv ~/.config/alacritty/alacritty.yml ~/.config/alacritty/alacritty_original.yml
ln -s ~/Git/dot_files/dot_config/alacritty/alacritty.yml ~/.config/alacritty/alacritty.yml
```
