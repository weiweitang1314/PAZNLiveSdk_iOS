# PAZNLiveSDK
## 调试账号
18800000001、18800000002 主播  
18800000003、18800000004 观众  
18800000005 管理员  
18800000006-18800000010  
密码:Aa123456

## 目录说明
DOC:开发文档 
PALiveLib:SDK库目录
PALiveSDKDemo:demo源码

# 更新记录
## PAZNLiveSdk_iOS_V1.0.6(2017-04-28 18:00)

### 1. 完整包地址(demo、lib、doc)   

***<font color=#ff0000>*由于文件限制 完整包地址请下载1.0.5完整包后,使用1.0.6补丁包替换相关文件</font>***

地址链接:[http://okxmfgy32.bkt.clouddn.com/PALiveSDKFull_V1.0.5.zip](http://okxmfgy32.bkt.clouddn.com/PALiveSDKFull_V1.0.5.zip)

### 2. 更新包地址(在SDK_V1.0.5基础上)
在SDK_V1.0.5基础上更新的库:PaLiveSdk.framework   
地址链接:[http://okxmfgy32.bkt.clouddn.com/PALiveSDKUpdate_V1.0.6.zip](http://okxmfgy32.bkt.clouddn.com/PALiveSDKUpdate_V1.0.6.zip)

### 3. 解决
1.解决1.0.5产生的后台删除直播间，观众崩溃的问题

## PAZNLiveSdk_iOS_V1.0.5(2017-04-26 15:00)

### 1. 完整包地址(demo、lib、doc) 
地址链接:[http://okxmfgy32.bkt.clouddn.com/PALiveSDKFull_V1.0.5.zip](http://okxmfgy32.bkt.clouddn.com/PALiveSDKFull_V1.0.5.zip)

### 2. 更新包地址(在SDK_V1.0.4基础上)
在SDK_V1.0.4基础上更新的包:PaCoreSdk.framework、PaLiveSdk.framework、PaliveSdkBundle.bundle。   
地址链接:[http://okxmfgy32.bkt.clouddn.com/PALiveSDKUpdate_V1.0.5.zip](http://okxmfgy32.bkt.clouddn.com/PALiveSDKUpdate_V1.0.5.zip)

### 3. 解决
1. 增加一些事件通知接口，便于app埋点
2. 解决同时设置后台地址和进入直播间，导致直播加没反应的问题
3. 解决打开麦克风失败，没有声音的问题

## PAZNLiveSdk_iOS_V1.0.4(2017-04-21 18:20)

### 1. 完整包地址(demo、lib、doc) 
地址链接:[http://okxmfgy32.bkt.clouddn.com/PALiveSDKFull_V1.0.4.zip](http://okxmfgy32.bkt.clouddn.com/PALiveSDKFull_V1.0.4.zip)

### 2. 更新包地址(在SDK_V1.0.3基础上)
在SDK_V1.0.3基础上更新的包:PaCoreSdk.framework、PaLiveSdk.framework。   
地址链接:[http://okxmfgy32.bkt.clouddn.com/PALiveSDKUpdate_V1.0.4.zip](http://okxmfgy32.bkt.clouddn.com/PALiveSDKUpdate_V1.0.4.zip)

### 3. 解决
1. 调用enterLiveRoom后和直播间显示之间的Loading界面采用模态方式(sdk内部显示，app不用再添加Loading)
2. 解决一些类名冲突的问题
3. 增加直播间内，知鸟后台http请求tokern失效的处理
