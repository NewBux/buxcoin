
Bux Coin

Bux Coin is a POW\PoS -based cryptocurrency.

Development process
===========================

SPECIFICATIONS

Scrypt

PoW/PoS

POW Time blocks: 180 sec

POW Block reward: 10


Max supply: 500 million


Min.Coin age: 8 hours

Max age: unlimited

RPC 8878

P2P 8868


Setup Bux Node

--Dependency--


apt-get install  libboost-program-options-dev libboost-thread-dev  libssl-dev libdb++-dev

apt-get install   libboost-filesystem-dev

apt-get -y install  git wget libqrencode-dev libminiupnpc-dev

sudo apt-get install build-essential make

sudo apt-get update

sudo apt-get install build-essential libssl-dev libboost-all-dev libminiupnpc-dev git zip

sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev



--Compile--


cd src
make -f makefile.unix


