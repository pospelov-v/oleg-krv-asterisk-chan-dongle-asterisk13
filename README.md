# oleg-krv-asterisk-chan-dongle-asterisk13
Готовый собраный мною модуль chan-dongle для asterisk13 с репозитория https://github.com/oleg-krv/asterisk-chan-dongle/
```
wget https://github.com/pospelov-v/oleg-krv-asterisk-chan-dongle-asterisk13/blob/master/chan_dongle.so?raw=true -O /usr/lib64/asterisk/modules/chan_dongle.so
```

https://github.com/oleg-krv/asterisk-chan-dongle/blob/master/etc/dongle.conf
```
wget https://raw.githubusercontent.com/oleg-krv/asterisk-chan-dongle/master/etc/dongle.conf -O /etc/asterisk/dongle.conf
```

```
chown asterisk:asterisk /usr/lib64/asterisk/modules/chan_dongle.so
chown asterisk:asterisk /etc/asterisk/dongle.conf
chmod u=rwX,g=rX,o= /etc/asterisk/dongle.conf
```
