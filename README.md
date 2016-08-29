
# TencentSDK

### 官方腾讯开放平台 iOS SDK。

##### 最新为2.9.5版： http://open.qq.com/

---

###如何使用？
pod 'TencentSDK', :git => 'https://github.com/Guicai-Li/TencentSDK.git'



---

###历史

V3.1.0完整包更新了以下内容：
新增功能：
一键加群功能

修正以下功能：
1. 修正 log 文件从 document 目录移到Caches目录；
2. 修正通过h5 登录，分享到手Q提示账号不符合；
3. 修正分享到群部落；
4. 修正sdk添加游戏好友获取好友设置失败；
5. 修复登录webview界面，放大镜穿透的问题；
6. 支持cpu指令集版本由arm7、arm7s、arm64、i386 、x86_64 变更到 armv7、x86_64、arm64

v2.9.5

1、关闭以下功能
第三方APP直接上传图片和视频到空间，分享的图片支持在动态直接展示，视频支持动态里直接播放。
