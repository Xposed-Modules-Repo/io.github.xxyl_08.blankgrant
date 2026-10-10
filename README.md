# 空镜 BlankGrant

基于 LSPosed / libxposed API 102 的敏感数据屏蔽模块，对指定应用屏蔽或伪造其读取的敏感数据。

只挂 framework 公共基类与系统服务，不碰任何 App 私有类，因此对所有 App 通用。

## 敏感数据与模式

12 类：通讯录、通话记录、短信、日历、相册/媒体、通话状态与 SIM、定位、麦克风、摄像头、账户、已安装应用、剪贴板。

每类 4 种模式：OFF / EMPTY / FAKE / DENY。

## 发布

APK 请见 Releases。
