# How to Install on Ubuntu


## install packages

    sudo apt-get install cmake libglfw-dev libglew-dev libglm-dev libbullet-dev libsoil-dev qt5-default

### ubuntu 13.10 (saucy)

    sudo add-apt-repository ppa:canonical-qt5-edgers/qt5-beta-proper
    sudo apt-get update
    sudo apt-get install qtbase5-dev qtdeclarative5-dev

## build

    cmake .
    make

