# motd

On systems that include `/etc/update-motd.d/`: copy the contents of `update-motd.d/` to that directory.

On other systems:

```
# cp ./update-motd.sh /usr/local/bin/
# cp -r ./update-motd.d /usr/local/share/
# echo "/usr/local/bin/update-motd.sh" >> /etc/rc.local
```

