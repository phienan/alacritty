## Installation for Linux distribution only
    tar zxvf alacritty-bin.tar.gz
    sudo cp Alacritty.svg /usr/share/pixmaps/Alacritty.svg
    sudo cp alacritty /usr/local/bin
    sudo cp Alacritty.desktop /usr/share/applications/
    cp alacritty.bash ~/.bash_alacritty
    mkdir -p ~/.config/alacritty/ && cp alacritty.toml ~/.config/alacritty/

<p>Add the line below to ~/.bash_profile.</p>
    [[ -f ~/.bash_alacritty ]] && source ~/.bash_alacritty