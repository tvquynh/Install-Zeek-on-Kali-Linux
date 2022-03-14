# Install-Zeek-on-Kali-Linux
1. Install the required dependencies <br />
sudo apt-get install cmake make gcc g++ flex bison libpcap-dev libssl-dev python3 python3-dev swig zlib1g-dev <br />
2. Install zeek<br />
git clone --recursive https://github.com/zeek/zeek <br />
cd zeek <br /> 
./configure && make && sudo make install <br />
