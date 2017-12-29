

##### update package
    sudo apt-get update

##### install git
    sudo apt-get install git

##### clone bitcoin
    git clone https://github.com/bitcoin/bitcoin.git

##### install gcc
    sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils

##### install openssl
    sudo apt-get install libtool autotools-dev autoconf
    sudo apt-get install libssl-dev

##### install boost
    sudo apt-get install libboost-all-dev

##### install libdb4.8
    sudo add-apt-repository ppa:bitcoin/bitcoin
    sudo apt-get update
    sudo apt-get install libdb4.8-dev
    sudo apt-get install libdb4.8++-dev

##### install other library
    sudo apt-get install libminiupnpc-dev
    sudo apt-get install libqrencode-dev

##### install gui library
    sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler

##### build bitcoin
    cd bitcoin
    ./autogen.sh
    ./configure
    make

##### install
    sudo make install
