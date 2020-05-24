# websocket-proxy-netty
A  implementation of Websocket-proxy in Java base on netty4 framework.

# Features

- [x] TCP support
- [x] CDN support


# Environment
* JRE8

# Install
1. download netty-websocket-proxy-x.x.x-bin.zip
2. unzip netty-websocket-proxy-x.x.x-bin.zip
3. run
#### as swserver
```
java -jar netty-websocket-proxy-x.x.x.jar -s -conf="conf/config-example-server.json"
```
#### as swclient
```
java -jar netty-websocket-proxy-x.x.x.jar -c -conf="conf/config-example-client.json"
```
  Note: After the client service starts, you can use Google Chrome and install the SwitchyOmega plug-in to surf the Internet

# Build
1. import as maven project
2. maven package

## TODO
* [ ] performance optimization
* [ ] android client
## Data flow
![image](https://img-blog.csdnimg.cn/2020051017110683.png)
