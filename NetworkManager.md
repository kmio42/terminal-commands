# Network Manager
To disable random MAC-Adresses for WiFi (which leads to new IP-Adresses)
edit /etc/NetworkManager/NetworkManager.conf as follows:

```
[device]
wifi.scan-rand-mac-address=no
```
