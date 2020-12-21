## AutoScript Install SSH & OpenVPN For Debian VPS By DitoBaskaran   <img src="https://img.shields.io/badge/Version-1.0-yellowgreen.svg">


## Supported Linux Distribution
<img src="https://www.debian.org/logos/openlogo.svg">
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%208&message=Jessie&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=red">


## Services :
<p align="center"><img src="https://img.shields.io/badge/Service-OpenSSH-success.svg">  <img src="https://img.shields.io/badge/Service-Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-BadVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Squid3-success.svg">  <img src="https://img.shields.io/badge/Service-Privoxy-success.svg">  <img src="https://img.shields.io/badge/Service-Webmin-success.svg">


## Installation :

```
wget https://raw.githubusercontent.com/DitoBaskaran/AutoScript_Debian/master/DebianVPS && chmod +x DebianVPS && ./DebianVPS
```


## Description :

### Port :
* OpenSSH Port : 22, 143. SSL : 444
* Dropbear Port : 109, 110. SSL : 443
* OpenVPN Port : 1194. SSL : 551
* Stunnel Port (See SSL Port Above)
* Squid Port 6666, 8888 (Privoxy)
* Badvpn Port 7300

### Feature : 
* Webmin http(s)://[ip]:10000/
* OpenVPN Download http://[ip]:86
* Timezone : Asia/Jakarta
* Fail2Ban : [on]
* Torrent Block : [on]
* IPv6     : [off]
