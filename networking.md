# Networking notes

edit /etc/network/interfaces
to contain
```auto eth0
iface eth0 inet dhcp
```
to connect to an Ethernet network.

Refresh with
```sudo /etc/init.d/networking restart```

