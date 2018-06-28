# bitradio
Bitradio Wallet Ubuntu 18.04x64

For Bitradiod

add-apt-repository -yu ppa:bitcoin/bitcoin

apt-get -qqy -o=Dpkg::Use-Pty=0 -o=Acquire::ForceIPv4=true install build-essential protobuf-compiler libboost-all-dev autotools-dev automake libcurl4-openssl-dev libboost-all-dev libssl-dev make autoconf libtool git apt-utils g++ libprotobuf-dev pkg-config libcurl3-dev libudev-dev libqrencode-dev bsdmainutils pkg-config libssl-dev libgmp3-dev libevent-dev jp2a pv virtualenv libdb4.8-dev libdb4.8++-dev unzip


apt-get -qqy -o=Dpkg::Use-Pty=0 -o=Acquire::ForceIPv4=true install libssl1.0-dev

For Bitradio-qt

apt-get -qqy -o=Dpkg::Use-Pty=0 -o=Acquire::ForceIPv4=true install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler


