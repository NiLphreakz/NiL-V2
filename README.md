<h2 align="center">

♦️AUTOSCRIPT OPENVPN/XRAY/TROJAN V2 BY NILPHREAKZ♦️

♦️SUPPORT CUSTOM PATH/BLANK PATH XRAY VMESS/VLESS♦️

 Xray Core V1.7.5.1


## ♦️INSTALLATION SCRIPT ( Recommended Debian 10 )♦️

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/NiLphreakz/NiL-V2/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh

```

## Description :

  Service & Port :
  
  [SSH & OpenVPN]
  - OpenSSH                 : 22
  - OpenVPN                 : TCP 1194, UDP 2200
  - OpenVPN SSL             : 110
  - Stunnel4                : 222, 777
  - Dropbear                : 442, 109
  - Websocket SSH(HTTP)     : 2081
  - Websocket SSL(HTTPS)    : 222
  - Websocket OpenVPN       : 2084
  
  [Sqd, Bdvp, Ngnx]
  - Squid Proxy             : 3128, 8000 (limit to IP Server)
  - Badvpn                  : 7100, 7200, 7300
  - Nginx                   : 81
  
  [XRAY]
  - Xray Vmess Ws Tls       : 443
  - Xray Vless Ws Tls       : 443
  - Xray Vless Tcp Xtls     : 443
  - Xray Vmess Ws None Tls  : 8443
  - Xray Vless Ws None Tls  : 8442
  
  [TROJAN]
  - Xray Trojan Tcp Tls     : 443
  - Trojan Go               : 2083

  {Server Information & Other Features}
  - Timezone                : Asia/Kuala_Lumpur (GMT +8)
  - Fail2Ban                : [ON]
  - Dflate                  : [ON]
  - IPtables                : [ON]
  - Auto-Reboot             : [ON]
  - IPv6                    : [OFF]
  - Autoreboot On 05.00 GMT +8
  - Autobackup Data
  - Restore Data
  - Auto Delete Expired Account
