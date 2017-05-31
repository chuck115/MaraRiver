

# 使用RPM安装

## 1. Downloading Lastest Java Archive

cd ~
wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x64.rpm"


## 2. Install the RPM with this yum command

yum localinstall jdk-8u131-linux-x64.rpm


Now Java should be installed at /usr/java/jdk1.8.0_60/jre/bin/java, and linked from /usr/bin/java.


## 3. Delete the archive file

rm ~/jdk-8u131-linux-x64.rpm