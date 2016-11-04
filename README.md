# debian-8-sentora-installer

I needed a arm ver of sentora on debian so this what come out



nano /etc/apt/sources.list

and delete all that is in there and replace it with this:

deb http://ftp.us.debian.org/debian/ jessie main contrib non-free
deb-src http://ftp.us.debian.org/debian/ jessie main contrib non-free

deb http://security.debian.org/ jessie/updates main contrib non-free
deb-src http://security.debian.org/ jessie/updates main contrib non-free


Get the installer


wget https://raw.githubusercontent.com/blynch555/debian-8-sentora-installer/master/sentora_install.sh

then run 

chmod +x sentora_install.sh

then run the installer

sudo ./sentora_install.sh

