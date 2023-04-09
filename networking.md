## Firewall
```
ufw enable
```
```
ufw disable
```
```
ufw status
```
- deny all connections from port 22/tcp
```
ufw deny 22/tcp
```
- deny a particular IP from port 22tcp
```
sudo ufw denyb proto tcp from 17.0.209.38
```
- deny a particular IP from all ports
```
sudo ufw reject 17.0.209.38
```



