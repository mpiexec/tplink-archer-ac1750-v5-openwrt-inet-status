```sh
$ opkg update
$ opkg install curl
$ opkg install coreutils-sleep

$ curl -k https://.../led-wan-trigger -o /usr/bin/led-wan-trigger
$ chmod +x /usr/bin/led-wan-trigger

$ curl -k https://.../led-wan-status -o /etc/init.d/led-wan-status
$ chmod +x /etc/init.d/led-wan-status
$ /etc/init.d/led-wan-status enable
```
