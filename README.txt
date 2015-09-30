

Flasm : Flasm disassembles SWF including all the timelines and events.

Linux Installation steps : 

rpm -ivh ftp://rpmfind.net/linux/centos/6.7/os/x86_64/Packages/zlib-1.2.3-29.el6.i686.rpm  

mkdir /opt/flasm 

cd /opt/flasm 

wget http://www.nowrap.de/download/flasm16linux.tgz -O flasm_tool 

tar -xvf ./flasm_tool ; rm -rf ./flasm_tool ; ln -s /opt/flasm/flasm /usr/bin/flasm


Flasm is now installed. To run type < flasm > in the terminal.