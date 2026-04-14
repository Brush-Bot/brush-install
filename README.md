# brush-install

目前只提供 windows10 以及mac intel和 arm64 安装包，如果有其它系统需求请联系我们

# Mac Os 安装
签名过期，无法对ios打包引用进行签名和公证所以装备会出现被拦截的情况！

```
sudo spctl  --master-disable
sudo xattr -r -d com.apple.quarantine /Applications/Brush.app

```

出现损坏弹窗请执行下这个两条命令，然后去设置里面允许所有来源。 还不会的就谷歌下~
