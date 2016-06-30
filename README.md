需要安装的模块：

pip install netaddr

MySQLdb http://download.csdn.net/detail/weibin0320/6663763

支持ip段爆破和单ip爆破

python fuzz.py -a 192.168.1.1/24 -t 30

python fuzz.py -a 192.168.1.23 -t 30

python fuzz.py -a 192.168.1.1-192.168.1.255 -t 30
