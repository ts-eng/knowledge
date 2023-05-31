# linux

* 搜索同一网段下的所有IP
```bash
sudo apt-get install arp-scan
sudo arp-scan -I wlo1 --localnet
```
其中wlo1为用ifconfig查出来的网卡名
