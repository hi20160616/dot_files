```
cd ~/Git && git clone https://github.com/hi20160616/dot_files.git
ln -s ~/Git/dot_files/dot_zshrc ~/.zshrc
mkdir -p ~/.config/i3
cp ~/.config/i3/config ~/.config/i3/config_original
ln -s ~/Git/dot_files/dot_config/i3/config ~/.config/i3/config
mkdir -p ~/.config/alacritty
cp ~/.config/alacritty/alacritty.yml ~/.config/alacritty/alacritty_original.yml
ln -s ~/Git/dot_files/dot_config/alacritty/alacritty.yml ~/.config/alacritty/alacritty.yml
```
