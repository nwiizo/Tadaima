# Tadaima
Using Login server.

```
見たい
w
uptime
ps
ip
df
```
```
負荷状況確認
top
iostat
netstat / ss
```
```
ログ調査 ファイルがあれば 一気に取得してみる。
/var/log/messages or /var/log/syslog
/var/log/secure
/var/log/cron
/var/log/nginx, /var/log/httpd, /var/log/mysql
/etc
lsof
```

```
Linuxパフォーマンス分析
uptime
dmesg | tail
vmstat 1
mpstat -P ALL 1
pidstat 1
iostat -xz 1
free -m
sar -n DEV 1
sar -n TCP,ETCP 1
top
```
### Acknowledgments
[Linux Performance Analysis in 60,000 Milliseconds](https://medium.com/netflix-techblog/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)  
[Systems Performance: Enterprise and the Cloud](http://www.pearson.com.au/9780133390094)
