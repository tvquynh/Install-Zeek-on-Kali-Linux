# Install-Zeek-on-Kali-Linux <br/>
About Zeek: https://docs.zeek.org/en/current/about.html#what-is-zeek
## 1. Install the required dependencies <br />
sudo apt-get install cmake make gcc g++ flex bison libpcap-dev libssl-dev python3 python3-dev swig zlib1g-dev <br />
## 2. Install zeek
git clone --recursive https://github.com/zeek/zeek <br />
cd zeek <br /> 
./configure && make && sudo make install <br />
export PATH="$PATH:/usr/local/zeek/bin" 
## 2. Test <br/>
zeek-cut < conn.log

