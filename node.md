#
```
sudo apt-get install curl
curl http://npmjs.org/install.sh | sudo sh
sudo wget https://nodejs.org/dist/v4.4.0/node-v4.4.0.tar.gz
sudo tar -xvf node-v4.4.0.tar.gz
sudo ./configure
sudo make install
```
#加入环境变量
```
nano /etc/profile
export NODE_HOME=/usr/local/n/versions/node/5.8.0 
export PATH=$PATH:$NODE_HOME/bin
export NODE_PATH=$NODE_HOME/lib/node_modules
source /etc/profile
```
#npm的安装
```
apt install npm
```
#n模块的安装
```
npm install n
```
#升级到稳定版
```
n stable
```

```
#生成器的安装
npm install express-generator -g
express web
cd web
npm install
```
#安装自动热启动
npm install supervisor
```
#执行
```
supervisor bin/www
```
