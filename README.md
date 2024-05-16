# shadowsocks

# install
wget --no-check-certificate -O shadowsocks-all.sh https://install.sh
chmod +x install.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

# uninstall
./shadowsocks-all.sh uninstall

# commands
/etc/init.d/shadowsocks-python start | stop | restart | status
