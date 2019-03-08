## 接口 & 后台声明
本项目为小程序商城纯前端项目，由于人力和精力所限，本项目并未有开发配套的后台系统，而是直接使用了 [api工厂](https://www.it120.cc/) 提供的免费接口和云后台，可以完全满足本项目的所有功能需求。

## 使用说明

1、[申请后台账号/获取专属域名](https://www.it120.cc/info/wxapp/115)

2、开通商城模块

<img src="https://cdn.it120.cc/apifactory/2018/11/14/b61fe6ffb2460f7e4554758b394814f5.png">

3、修改源码中  app.js 文件

```javascript
globalData:{
 userInfo:null,
 subDomain:"mall" // subDomain 中的 mall 为上面您注册开通的域名
}
```

4、[设置小程序合法服务器域名](https://www.it120.cc/info/wxapp/116)

5、重启您的小程序开发工具，完成
