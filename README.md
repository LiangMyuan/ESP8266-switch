# ESP8266-switch
基于micropython可以触控和MQTT控制的按钮开关

1.下载http://www.micropython.org/download#esp8266
刷入ESP8266
建议刷入http://www.micropython.org/resources/firmware/esp8266-20180511-v1.9.4.bin
高版本好像链接软件链接不了

2.使用http://fweb.cc/soft/PC/ESP8266.zip把每个文件上传。

3.修改Settings.json中的"ESSID": "自己无线账号"，"PASSWORD": "自己无线密码"， "MQTT_Topic": "需要链接的主题"。MQTT服务器MQTT用户名密码等！

4.触控安装为点控高频输入接口为GPI14 开关控制按钮GPI12

5.MQTT支持断网自动链接，无网络触控按钮也可以使用！

6.MQTT接受端主题 '自己设置的主题/I' 接受信息 上传信息 '自己设置的主题/C' 开关命令 on off 不区分大小写

7.测试版本有诸多不完善，请大家多修改。

