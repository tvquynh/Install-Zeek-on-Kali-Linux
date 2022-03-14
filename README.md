# Install-Zeek-on-Kali-Linux
1. Install the required dependencies
sudo apt-get install cmake make gcc g++ flex bison libpcap-dev libssl-dev python3 python3-dev swig zlib1g-dev
2. Install zeek
git clone --recursive https://github.com/zeek/zeek
cd zeek
./configure && make && sudo make install
