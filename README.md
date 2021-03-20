### 1 安装
#### 1.1 安装MQTT Broker
可以参考[EMQ X Broker](https://github.com/emqx/emqx)
```
docker run -d --name emqx -p 1883:1883 -p 8081:8081 -p 8083:8083 -p 8883:8883 -p 8084:8084 -p 18083:18083 emqx/emqx
```
#### 1.2 安装Python MQTT客户端
```
pip install  paho-mqtt
```
### 2 运行Publisher
```
python publisher.py
```
### 3 运行Subscriber
```
python subscriber.py
```