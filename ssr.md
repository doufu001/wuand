# ShadowsocksR Config Guide

* Sercer: Ubuntu 14.04

    apt-get update
    
    apt-get install git -y
    
    git clone -b manyuser https://github.com/shadowsocksr/shadowsocksr.git
    
    cd shadowsocksr
    
    bash initcfg.sh
    
    cd shadowsocks
    
    python server.py -d start
