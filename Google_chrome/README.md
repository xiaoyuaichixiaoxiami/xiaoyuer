# 内置浏览器一键安装指南
---

![微信截图_20250514114425](https://github.com/user-attachments/assets/660b2f6a-6ebb-4bf9-8cab-74dd473ab66c)
该指令用于在VPS或服务器上安装google浏览器，但是并不能挂机，只是应对一些项目需要在浏览器上进行绑定什么社交软件或者其他
在社区指令的技术分享中就可以找到啦！
![微信截图_20250515115144](https://github.com/user-attachments/assets/25f31e6a-dd07-45fb-9bfa-86a103b0071e)

---
配置需要根据在浏览器上的进程多少计算，进程越多则占用内存和cpu越多

下载的文件大小决定占用磁盘大小。下载文件存储在Download文件夹下。

下面是具体的安装指南：

第一步是需要在NODEHUB上连接服务器，连接成功后再点击执行指令，选择服务器后选择安装指令设置自己的浏览器的用户名及密码，点击执行即可。
![微信截图_20250514122116](https://github.com/user-attachments/assets/aab37f2a-9c5b-4ae7-be3e-0973a465826e)
执行成功后，在节点管理中查看节点状态，若节点状态为健康且在线
![微信截图_20250515121945](https://github.com/user-attachments/assets/25789785-0f6c-435e-a64f-b14d17f54250)
使用服务器IP及6081端口访问部署的浏览器(http://<VPS_IP>:6081/vnc.html)，输入设置的用户名和密码

![微信图片_20250429122326](https://github.com/user-attachments/assets/5650350b-549b-403b-80ff-9a0aeed9c190)

登录后点击连接，成功后进入浏览器后就不用我在这里赘述了。

## 异常情况处理：
---
若出现点击连接，但是连接不上，就执行一下重启指令。
![微信截图_20250515120958](https://github.com/user-attachments/assets/d4a1f43b-1d72-45c8-a13e-c8a952c913d6)

若是忘记了设置的用户名和密码且历史数据也已经清空，则需要执行卸载后再安装。

---

希望这篇指南能帮到你！！！
