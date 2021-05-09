#!/bin/bash
#Sysupdate
sudo apt-get update 
#Python
sudo apt-get install python
#gmail
git clone https://github.com/Ha3MrX/Gemail-Hack.git
#facebook
if [ -d facebook ]; then
        echo "Directory facebook exists.[✔]"
else
	mkdir facebook
	cd facebook
	
cd ..
fi
#Instagram
git clone https://github.com/thelinuxchoice/instainsane.git
cd instainsane
chmod +x instainsane.sh
chmod +x install.sh
sudo ./install.sh
cd ..
#Twitter
git clone https://github.com/thelinuxchoice/tweetshell.git
cd tweetshell
chmod +x tweetshell.sh
chmod +x install.sh
sudo ./install.sh
cd ..
