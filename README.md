#必装软件
```shell
yum install -y vim net-tools wget gcc gcc-c++ autoconf automake readline-devel pcre-devel openssl-devel lrzsz tcl unzip bc mariadb-server mariadb-client MySQL-python python-setuptools python-devel git zlib-devel freetype freetype-devel libpng libpng-devel zlib zlib-devel libjpeg libjpeg-devel
```

#可选软件
```shell
yum install -y subversion openssh-clients ImageMagick net-snmp-devel.x86_64 kernel-headers net-snmp-devel net-snmp net-snmp-utils procmail telnet iotop iftop
```

#源码包安装
```shell
wget http://openresty.org/download/ngx_openresty-1.7.10.1.tar.gz
wget http://download.redis.io/releases/redis-3.0.1.tar.gz
wget https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-3.0.3.tgz
wget http://alioth.debian.org/frs/download.php/3015/axel-2.4.tar.gz
wget https://github.com/pypa/pip/archive/6.1.1.tar.gz
```

#Python库
```shell
pip install mysql-python tornado torndb redis httplib2 requests chardet evernote beautifulsoup4  html5lib  lxml  pycurl  pymongo rsa poster
```

#启动服务
```shell
systemctl start mariadb
systemctl start nginx
```

#开机启动服务
```shell
systemctl enable mariadb
```