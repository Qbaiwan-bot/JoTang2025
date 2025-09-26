# 因为想要偷懒所以搞了wsl和虚拟机这件事
## 一.WSL与我
### 序幕
事情要从哪里讲起呢  
我看到焦糖的一刻起我就被其深深吸引（？  
于是说做就做，开启了我的焦糖马拉松
### 1#图轻松引发的惨案
我听说，**我们编程最好就是要Ubuntu**  
为了以后的轻松，我直接跳过了markdown决定先去看Ubuntu怎么搞  
我看到了
![我看到了](WSL&虚拟机尝试pic\image.png)  
*“啥？！windows可以配置linux？！”*   
我去B站搜了教程，打开Windows功能  
![这个](WSL&虚拟机尝试pic\image2.png)
然后``` wsl --set-default-version 2 ```  
试图在powershell下载Ubuntu
所以我网上一查攻略猛如虎，<kbd>Win</kbd>+<kbd>R</kbd> 一口气下了Ubuntu20.04(教程是这么操作的)  
然后出现了：**使用旧分发注册。请考虑改用基于 tar 的分发**  
*“这啥？”*  
我一查CSDN，把20.04删掉，在微软商店下了Ubuntu24.04，重返Powershell下载Ubuntu，问题解决！ 
没有为上一个问题的解决而开心，接下来到场的是：**检测到 localhost 代理配置，但未镜像到 WSL。NAT 模式下的 WSL 不支持 localhost 代理。**  
*“这又是啥啊”*  
于是上知乎查询后，进入wsl settings，在网络选项改NAT为Mirrored，完事儿。
### 好消息：wsl疑似配置好了
### 坏消息：这个页面我看不懂，我想要GUI
### 更坏的消息出现了，我在这个时候才发现：
## **要写markdown**
最终：  
我开始了我的md之旅  
![我此刻才开始学md](WSL&虚拟机尝试pic\image3.png)  
所以我以上的wsl都是 ~~我的回忆~~ 浏览器的回忆