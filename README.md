# shadowsocks

# install
wget --no-check-certificate -O install.sh https://raw.githubusercontent.com/111nfinity/shadowsocks/master/install.sh  
chmod +x install.sh  
./install.sh 2>&1 | tee install.log  

# uninstall
./install.sh uninstall  

# commands
/etc/init.d/shadowsocks-python start | stop | restart | status  
