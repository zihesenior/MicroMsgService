# MicroMsgService
一个小型的MQTT消息服务，用于小型应用部署，开发调试等场景。是一个Windows服务，没有界面，用命令启动后可以使用Windows服务管理器管理。

部署时根据需要改一下配置文件
```xml
<config>
  <server port="1024"></server>
  <clients>
    <client id="imsuperman" username="user" password="123456"></client>
    <client id="screens" username="user" password="123456"></client>
  </clients>
</config>
```
