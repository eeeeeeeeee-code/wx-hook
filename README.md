# wx-hook

### 介绍

用于记录老版本的小程序的基址和文件，用于绕过使用



### bug处理

> 注意当前方法可能导致一些神奇的bug，提前声明这类bug，我不怎么会解决，可以反馈大家一起解决
>
> 90%的bug，可以采用将RadiumWMPF里面的所有小程序删除完，然后重启wx，重新替换，替换文件修改只读解决



## 优化使用

**介绍**

这里是 https://github.com/eeeeeeeeee-code/e0e1-wx 的hook优化扩展使用

> 新版的devtools十分难受，界面垃圾，功能稀少，感觉就是微信防止hook的一种限制手段
>
> 这里找到一种绕过的方法



**使用方法**

1.在 Releases，下载老版本的小程序文件，这里我下载的是8447.zip文件

![image](https://github.com/eeeeeeeeee-code/wx-hook/assets/115862499/6f8f8faf-b8d2-462d-9b76-f0ebc25d50ed)

2.退出微信，来到 %appdata%\Tencent\WeChat\XPlugin\Plugins\RadiumWMPF\ 文件夹，将新版小程序里面的文件清空，列如我这里是9129，将里面的文件清空

![image](https://github.com/eeeeeeeeee-code/wx-hook/assets/115862499/cab74171-4348-4506-bc8c-e315f10e89e1)

3.解压老版本的小程序文件，将里面的**extracted文件夹**所有内容复制到**9129下面** (我是9129，你们是什么自己看)

![image](https://github.com/eeeeeeeeee-code/wx-hook/assets/115862499/d18757fd-32bf-44bf-9d07-35a8d37c7a5a)

4.将文件夹设置成只读，然后打开微信

![image](https://github.com/eeeeeeeeee-code/wx-hook/assets/115862499/f19055e3-2bfb-4c3e-afcd-b847f5c28181)

5.然后来到addres，找到对应的基址替换上去，列如我替换的文件是8447的，就使用8447的基址

![image](https://github.com/eeeeeeeeee-code/wx-hook/assets/115862499/c6b0e492-36fc-4233-ab7c-f19836e121d7)

6.启动e0e1-wx脚本，发现成功hook以前的devtools了

![image](https://github.com/eeeeeeeeee-code/wx-hook/assets/115862499/4ee986a4-9eca-4d5b-b91c-e0460fae09de)
