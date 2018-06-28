# bitradio
Bitradio Wallet Ubuntu 18.04x64

For Bitradiod

add-apt-repository -yu ppa:bitcoin/bitcoin

apt-get -qqy -o=Dpkg::Use-Pty=0 -o=Acquire::ForceIPv4=true install build-essential protobuf-compiler libboost-all-dev autotools-dev automake libcurl4-openssl-dev libboost-all-dev libssl-dev make autoconf libtool git apt-utils g++ libprotobuf-dev pkg-config libcurl3-dev libudev-dev libqrencode-dev bsdmainutils pkg-config libssl-dev libgmp3-dev libevent-dev jp2a pv virtualenv libdb4.8-dev libdb4.8++-dev unzip


apt-get -qqy -o=Dpkg::Use-Pty=0 -o=Acquire::ForceIPv4=true install libssl1.0-dev

For Bitradio-qt

apt-get -qqy -o=Dpkg::Use-Pty=0 -o=Acquire::ForceIPv4=true install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler


For fast synchronization, add lines to our Bitradio.conf

addnode=node1.bitrad.io
addnode=node2.bitrad.io
addnode=node3.bitrad.io
addnode=104.12.54.125
addnode=106.69.65.47
addnode=108.90.48.246
addnode=109.174.26.114
addnode=109.201.181.148
addnode=109.230.130.143
addnode=109.230.195.124
addnode=113.22.148.188
addnode=119.81.230.139
addnode=121.157.223.83
addnode=124.6.227.100
addnode=128.75.86.19
addnode=13.59.227.76
addnode=131.255.115.168
addnode=134.249.166.11
addnode=134.3.254.122
addnode=138.59.10.252
addnode=14.54.109.49
addnode=141.101.142.122
addnode=149.202.157.228
addnode=149.56.110.227
addnode=149.6.194.174
addnode=150.101.218.41
addnode=163.158.73.8
addnode=168.228.84.54
addnode=168.232.230.235
addnode=170.231.17.86
addnode=170.83.120.201
addnode=176.251.237.73
addnode=177.18.187.248
addnode=177.73.107.123
