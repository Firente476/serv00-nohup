
## Github Actions保活
变量名称:ACCOUNTS_JSON
```json
[
  {"username": "***", "password": "****", "panel": "pane*.serv00.com", "ssh": "s*.serv00.com"},
  {"username": "***", "password": "****", "panel": "pane*.serv00.com", "ssh": "s*.serv00.com"},
  {"username": "***", "password": "****", "panel": "panel*.ct8.pl", "ssh": "s*.ct8.pl"}
]
```
## Hysteria2-Socks5安装脚本
```js
bash <(curl -s https://raw.githubusercontent.com/gshtwy/socks5-for-serv00/main/install-socks5-hysteria.sh)
```

## 重置服务器
### 停止进程
```js
pkill -kill -u 
```
### 删除文件及其文件夹
```js
chmod -R 755 ~/* 
```
```js
chmod -R 755 ~/.* 
```
```js
rm -rf ~/* 
```
```js
rm -rf ~/.* 
```
