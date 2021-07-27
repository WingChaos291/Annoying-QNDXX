

`**WARNING  
在学习本方法前你应当清楚，此行为违背了青年大学习网上主题团课的最初目的，可能造成不好的后果！**`


### 原理

​	**利用微信自带的腾讯`X5内核`，在网页视频播放时进行调试，达到更改视频播放时长的目的。**  



# 方法

#### 	#适用于Android，如果你是ios用户，请直接在任务栏中拖动视频进度条



### 一、确认内核

​	将以下网址发送到任意微信联系人（建议发给自己，避免对他人造成困扰）  



```
debugmm.qq.com/?forcex5=true
```

​	点开查看结果是否为"force use x5 switch is on"  



<img alt="" src="/img/annoying-QNDXX/ensurex5.jpg" width=30%><img alt="" src="/img/annoying-QNDXX/x5ison.jpg" width=30%>



### 二、开启x5内核调试

​	将以下网址发送......  



```
http://debugx5.qq.com
```


1. 单击网址进入`调试页面`
2. 单击页面上方`信息`
3. 勾选"打开`vConsole`调试功能"
4. 刷新页面即可看到浮动的`vConsole`调试按钮



<img alt="" src="/img/annoying-QNDXX/openVconsole1.jpg" width=30%><img alt="" src="/img/annoying-QNDXX/openVconsole2.jpg" width=30%><img alt="" src="/img/annoying-QNDXX/openVconsole3.jpg" width=30%>



### 三、开始 ~~学习~~

​	复制以下指令至剪切板



```
document.getElementById('Bvideo').currentTime=3600;
```

​	#获取并更改当前页面视频播放时间



```
__vconsole.style.display="none";
```

​	#隐藏`vConsole调试按钮`（用于截图，刷新页面后恢复显示）



1. 转至开始学习页面

2. 点击`开始学习`

3. 打开`调试窗口`

4. 粘贴`修改指令`执行

5. 答完所有题目



**答完所有题目后，大概率出现视频仍在播放的情况，只需重新执行指令即可跳过**

**执行隐藏指令后截图，完成本次青年大学习**



<img alt="" src="/img/annoying-QNDXX/begin1.jpg" width=30%><img alt="" src="/img/annoying-QNDXX/begin2.jpg" width=30%><img alt="" src="/img/annoying-QNDXX/end.jpg" width=30%>



### 四、补充内容

1. 本方法来源于网络，本人仅将代码合并整理，并提供截图时调试按钮的隐藏思路。
2. 使用本方法造成学校处分后果的，由使用者自行承担责任。
3. 理论上：本方法完整的看（刷）完了视频。
4. 图片排版太扯了，由于受各种不确定因素影响，不是我的锅🙄
