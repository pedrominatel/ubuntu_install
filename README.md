# Ubuntu Install

```
sudo apt update && \
sudo apt -y upgrade  && \
sudo apt install htop kicad inkscape gimp freecad build-essential zsh kdenlive audacity screen vim git wget flex bison gperf python3 python3-pip python3-setuptools cmake ninja-build ccache libffi-dev libssl-dev dfu-util libusb-1.0-0 meld cheese && \
sudo usermod -a -G dialout $USER && \
mkdir ~/esp && cd ~/esp && \
git clone --recursive https://github.com/espressif/esp-idf.git && \
cd ~/esp/esp-idf && ./install.sh && \
. $HOME/esp/esp-idf/export.sh

```
