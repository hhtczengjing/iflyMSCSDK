# iflyMSCSDK

[iflyMSC SDK集成文档](http://www.xfyun.cn/doccenter/iOS)

### 安装

在 `Podfile` 文件下添加

``` 
	pod 'iflyMSCSDK', :git => 'https://github.com/hhtczengjing/iflyMSCSDK.git'
```

###更新记录

#### 1.133（2016-05-25）

- 1.ipv6 only支持；=,支持连接macbook产生的NET64无线网络热点；
- 2.修复uri合成和next_text混合运行时的bug；  

#### 1.132 (2016-05-23)

- 1.增加音频队列初始化参数配置,PLAYER_INIT,RECORDER_INIT,可以控制是否需要初始化音频队列，具体使用请参照IFlySpeechConstant注释；
- 2.支持预合成功能,具体请参照IFlySpeechConstant的NEXT_TEXT参数；
- 3.合成播放进度回调增加参数,onSpeakProgress增加beginPos和endPos参数。
- 4.语记合成SDK支持设置默认离线发音人（此选项需要到开放平台指定入口下载对应SDK方可支持）,支持设置默认的离线发音人，使用默认离线发音人可以不用跳转到语记。
- 5.修复部分App Store审核障碍,修改使用apple内部私有api的问题；

#### 1.119 (2015-07-23)

- 1.修改评测模块出现的编译错误；

#### 1.117 (2015-07-21)

- 1.支持在线评测功能；
- 2.支持识别类net_timeout参数设置；

#### 1.109 (2015-06-01)

- 1.支持合成，识别连续start启动机制；
- 2.支持合成预加载机制；
- 3.修复部分内存泄露；
- 4.demo界面进行改版，支持各种参数设置。


