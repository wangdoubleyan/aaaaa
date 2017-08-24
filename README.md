# avpn

wget --no-check-certificate -O shadowsocks-libev.sh https://raw.githubusercontent.com/wangdoubleyan/avpn/master/shadowsocks-libev.sh
chmod +x shadowsocks-libev.sh
./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log




wget --no-check-certificate https://raw.githubusercontent.com/wangdoubleyan/avpn/master/shadowsocks.sh
chmod +x shadowsocks.sh
./shadowsocks.sh 2>&1 | tee shadowsocks.log
