Some necessary installations to setup ubuntu

install unity-tweak-tool: 

sudo apt-get install unity-tweak-tool   

For Ubuntu 22.04
https://ubuntuhandbook.org/index.php/2022/05/install-themes-ubuntu-22-04/

install theme flatabulous-theme:  

sudo add-apt-repository ppa:noobslab/themes  
sudo apt-get update  
sudo apt-get install flatabulous-theme  

disable terminal bell 
open preferences in termial, and choose unnamed option, under text tab uncheck terminal bell

install icon ultra-flat-icons:  

sudo add-apt-repository ppa:noobslab/icons  
sudo apt-get update  
sudo apt-get install ultra-flat-icons    

download ultra icons here https://www.gnome-look.org/p/1171748 
And then create a .icons folder under /home, and then copy and paste the downloaded icons to /home/.icons

install mouse macbuntu-os-ithemes-lts-v7:  

sudo add-apt-repository ppa:noobslab/macbuntu  
sudo apt-get update  
sudo apt-get install macbuntu-os-icons-lts-v7  
sudo apt-get install macbuntu-os-ithemes-lts-v7  

install font:
sudo apt-get install fonts-wqy-microhei

After install fonts-wqy-microhei, open tweaks to change the fonts 

install on-my-zsh:

sudo apt-get install zsh  
sudo apt-get install git  
sudo wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh  
chsh -s /bin/zsh  


other details refer to https://www.jianshu.com/p/4bd2d9b1af41  

To configure VIM, needs to down the vim folder into /home and rename it as .vim

