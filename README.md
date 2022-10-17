# janus 客户端

仅提供videoroom

纯静态页面，直接用浏览器打开index.html即可

可以从页面上设置janus服务端地址和iceServer地址

---
可以给chrome浏览器添加参数，模拟音视频，用于没有摄像头和麦克风的情况下测试。

方法:  为chrome创建快捷方式，然后修改属性，在 目标 内，chrome的路径后边，添加参数  
```
--use-fake-device-for-media-stream --use-fake-ui-for-media-stream --test-type --ignore-certificate-errors --allow-running-insecure-content
```

然后打开这个chrome快捷方式，将index.html拖入，进行测试。

上述参数也可以用于自动化测试。
