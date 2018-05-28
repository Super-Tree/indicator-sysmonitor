## declaration
This repository was forked form [fossfreedom/indicator-sysmonitor](https://github.com/fossfreedom/indicator-sysmonitor) and I personally added some new functions  with adding gpu memory usage rate.

On Ubuntu and derivatives - manual installation

    sudo apt-get install curl git gir1.2-appindicator3-0.1
    sudo apt-get install python3-psutil # or sudo pip3 install -U psutil
    git clone https://github.com/Super-Tree/indicator-sysmonitor.git
    cd indicator-sysmonitor
    sudo make install
    nohup indicator-sysmonitor &
    
To remove:

    cd indicator-sysmonitor
    sudo make uninstall
    
Runing  

![](https://github.com/Super-Tree/indicator-sysmonitor/raw/master/running_pic.png)    