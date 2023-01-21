# luci-theme-neobird

基于原作者修改: <https://github.com/thinktip/luci-theme-neobird>

- 修复安装package提示信息背景泛白
- 优化菜单缩放
- 优化显示网口down状态显示图标
- 优化logo显示
- 优化设备状态图标显示
- 更换logo显示为字体"OpenWrt"
- 修复部分插件显示bug
- 修复vssr状态bar
- 修复诸多bug
  
> 适用于lede
For Lean's OpenWRT Only
<https://github.com/coolsnowwolf/lede>

## 主要特点

- 针对移动端优化，特别适合手机端做为webapp使用
- 修改很多细节，全新的定制的icon图标，尽量视觉统一
- 简洁的登录界面，底部导航栏，类App的沉浸式体验；
- 适配深色模式，适配系统自动切换；
- 矢量图片适配。

## 体验Webapp方法

- 在移动端(iOS/iPadOS)浏览器打开管理界面，添加到主屏幕即可。
- 想要实现完全的沉浸式（无浏览器导航、无地址栏等）体验，需要使用SSL证书，请自行申请域名、证书、安装并启用。
- 如果不使用SSL证书，基于安全原因，iOS/iPadOS 在打开新的页面后，将会显示浏览器顶部菜单栏。

## 目前存在的问题

- 资源接口icon未完善，如果有能力画图的欢迎pr，但请确保跟现有icon颜色风格一致
- 有bug欢迎提issue

## 自行编译

```
git clone https://github.com/gngpp/luci-theme-neobird.git  package/luci-theme-neobird
make menuconfig # choose LUCI->Theme->Luci-theme-neobird  
make V=s
```

## 预览

<img src="./preview/login.png"/>
<img src="./preview/home.png"/>
<img src="./preview/home1.png"/>
<img src="./preview/mini.png"/>
<img src="./preview/sidebar.png"/>
<img src="./preview/vssr.png"/>
<img src="./preview/iface.png"/>
<img src="./preview/iface1.png"/>
<img src="./preview/IMG_8790.PNG"/>
<img src="./preview/IMG_8791.PNG"/>
