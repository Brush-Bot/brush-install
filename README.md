# brush-install

目前只提供 windows10 以及mac intel和 arm64 安装包，如果有其它系统需求请联系我们

# Mac Os 安装
签名过期，无法对ios打包引用进行签名和公证所以装备会出现被拦截的情况！

#### app 客户端
```
sudo spctl  --master-disable
sudo xattr -r -d com.apple.quarantine /Applications/Brush.app

```
出现损坏弹窗请执行下这个两条命令，然后去设置里面允许所有来源。 还不会的就谷歌下~


#### wormhole 代理

让其变成可执行文件，这个代理客户端是指·请求代理· windows和mac都执行如下指令。

输入sudo chmod +x 后把文件拖到终端 就形成下面的指令了

```
sudo chmod +x xxx/brush-wormhole-mac-arm64.dmg
```
