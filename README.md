# feed-netkeeper(适用于LUCI2)

## 注意事项
本分支支持在OpenWrt主线上使用，适用于JS版本的LUCI2，如使用LUCI（Lua版本）的请切换分支到Lua版

## 本软件源包含四个软件
```
netkeeper（闪讯插件）
luci-proto-netkeeper（闪讯拨号界面）
netkeeper-interception（闪讯拦截服务）
luci-app-netkeeper-interception（闪讯拦截服务界面）
```

# 使用方法

## 普通插件

在 _网络 -> 接口 -> 编辑WAN -> 选择闪讯拨号 -> 确认切换_ 后

然后输入 _用户名_ 和 _密码_ 选择对应的 _闪讯插件_ 保存应用即可拨号

## 拦截插件

在 _网络 -> 接口 -> 编辑WAN -> 选择闪讯拨号 -> 确认切换_ 后

选择 _闪讯拦截_ 插件并开启闪讯拦截服务后，在PC端使用闪讯客户端拨号，会自动获取用户名与密码并拨号

**可以不用填写 _用户名_ 和 _密码_**

### 特别鸣谢
netkeeper的核心源码来自于miao1007的[Openwrt-NetKeeper](https://github.com/miao1007/Openwrt-NetKeeper)
