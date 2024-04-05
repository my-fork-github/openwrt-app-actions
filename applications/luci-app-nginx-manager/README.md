使用前先删除 uhttp的https

```
uci delete uhttpd.main.listen_https && uci commit && /etc/init.d/uhttpd restart
```