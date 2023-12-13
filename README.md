# sshd-geo-filter
filtering script for sshd to filter public remote access by geolocation to reduce attack vector

Requires MaxMind GeoIP (geoip) libraries - can use _free_ subscription for Country level blocking.

##Prerequisites:

for debian and ubuntu:  
`sudo apt install -y geoip-bin geoipupdate` 

`cp sshfilter.sh /usr/local/bin/` 

`chmod +x /usr/local/bin/sshfilter.sh` 

`cp example_etc_hosts.allow /etc/hosts.allow`
