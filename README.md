#install_v2ray_xray_on_openwrt
Target Platform	: ramips/mt7621 : [Supported Devices List](https://downloads.openwrt.org/releases/22.03.3/targets/ramips/mt7621/)


# requirement : 38MB free "Temp Space"
# Warning : Not compatible with version openwrt22.03.5 ! Try [22.03.4](https://downloads.openwrt.org/releases/22.03.4/targets/ramips/mt7621/) or less
[![visitor badge](https://img.shields.io/badge/Chat%20on-Telegram-blue.svg)](https://t.me/AmirHosseinTSL) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)



install v2ray , xray-core , i'm trying to install on mi 4a gigabit :

Hi Guys if you want to run v2ray shadowsocks on your router , First You should install openwrtOS and then install passwall Package 
but there is a problem !!! your router disk space is just 8mb so not enough space to install xray ...
but Don't Worry i have a solution ... :)

(How to install Passwall on Openwrt : https://www.youtube.com/watch?v=f4-GUnCK2Wo&t=520s&ab_channel=AmirHosseinChoghaei)

# Install Xray in one Step + IRAN IP BYPASS:

1- xray version : 1.8.3 latest update !
```
wget https://raw.githubusercontent.com/SafaSafari/Install-Xray-V2ray-On-Passwall-Openwrt/main/amirhossein.sh && chmod 777 amirhossein.sh && sh amirhossein.sh
```

Done !

- *Automatic Xray Update After each reboot*


![This is an image](https://pars-space.ir/wp-content/uploads/2023/03/Sp.jpg)



![This is an image](https://pars-space.ir/wp-content/uploads/2023/03/Passwall.jpg)

>>> when your router rebooted , it's takes about 3 min to start passwall with xray-core ...




# Update :

```
sh /root/up.sh
```


# Uninstall :

```
wget -q https://raw.githubusercontent.com/amirhosseinchoghaei/Install-Xray-V2ray-On-Passwall-Openwrt/main/unis.sh && chmod 777 unis.sh && sh unis.sh
```
