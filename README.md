# BACKLASh
Bro elAstiCsearch Kibana LogstAsh Suricata Stack for NSM opertations. 

#This is a work in progress. 
We will be installing the above products. 
The system will have two parts. 

The sensor will consist of:
https://www.bro.org
https://suricata-ids.org/

Viewer: 
https://www.elastic.co/

The viewer will also be front ended by ngix for reverse proxy login. 

##Install the required dependancies

Bro and suricata in one go: 
sudo apt-get install cmake make gcc g++ flex bison libpcap-dev libssl-dev python-dev swig zlib1g-dev libpcre3 libpcre3-dbg libpcre3-dev build-essential autoconf automake libtool libpcap-dev libnet1-dev libyaml-0-2 libyaml-dev zlib1g zlib1g-dev libcap-ng-dev libcap-ng0  libmagic-dev libjansson-dev libjansson4 pkg-config curl libgeoip-dev



