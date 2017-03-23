## IPv6科研指南  

#### 一、将IPv6的DNS更改为如下地址：  
```
2001:4860:4860::8888
2001:4860:4860::8844
```  

1. Step 1. 依次打开控制面板 -> 网络和Internet -> 网络和共享中心 ，点击左侧“更改适配器设置”  
![](IPv6_ChangeAdapter.png)  
2. Step 2. 选中你的本地连接，右击，在右键菜单中点击“属性”  
![](IPv6_LocalConnection.png)  
3. Step 3. 选中“Internet 协议版本 6 (TCP/IPv6)”，点击属性  
![](IPv6_Property.png)  
4. Step 4. 选中“使用下面的DNS服务器地址”，填入如图所示的DNS地址
![](IPv6_DNS.png)  
5. Step 5. 关闭所有浏览器，打开CMD，输入如下命令：  
```ipconfig /flushdns```  
6. 好了，重新打开浏览器，输入https://www.google.com/ ，你应该能happy的科研了  


当然，请确保你有IPv6连接。做完上面这些工作，你应该能自由使用Google学术、Gmail了。如果出现连接被重置，请确保你输入的网址最开头是https，一定要有那个“s”。  
还有一些内容没写完，心情好再写~  
