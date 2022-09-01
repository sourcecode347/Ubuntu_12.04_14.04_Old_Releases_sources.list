# Ubuntu_12.04_14.04_Old_Releases_sources.list
Ubuntu 12.04 14.04 Old Releases sources.list

# Last Working Test : 01/09/22

Working /etc/apt/sources.list for Ubuntu 12.04 & 14.04
Test & Working on 01/09/22 in a old dev board(PCduino3 Nano)

# Installation on Ubuntu 14.04 Nand image for PCDuino3 Nano

    sudo leafpad /etc/apt/sources.list

# How To Fix PPA Add

    sudo apt-get install software-properties-common python-software-properties
    
# How To Install Python3.6

    wget https://www.python.org/ftp/python/3.6.3/Python-3.6.3.tgz
    tar -xvf Python-3.6.3.tgz
    cd Python-3.6.3
    sudo ./configure --enable-optimizations
    
    sudo make -j8
    sudo make install

    sudo apt-get update
    sudo apt-get install python3.6

    python3 -V
    
    
