
# Fuck 学习强国

一款帮助成年人（或许未来包括小朋友）自动学刁的软件

## 下载

[Windows](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/raw/master/Fuck学习强国-win32.zip) &nbsp;|&nbsp; [镜像1](https://raw.githack.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-win32.zip) &nbsp;|&nbsp; [镜像2](https://cdn.staticaly.com/gh/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-win32.zip)

[Mac](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/raw/master/Fuck学习强国-darwin.zip) &nbsp;|&nbsp; [镜像1](https://raw.githack.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-darwin.zip) &nbsp;|&nbsp; [镜像2](https://cdn.staticaly.com/gh/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-darwin.zip)

[Linux x86_64](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/raw/master/Fuck学习强国-linux.zip) &nbsp;|&nbsp; [镜像1](https://raw.githack.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-linux.zip) &nbsp;|&nbsp; [镜像2](https://cdn.staticaly.com/gh/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-linux.zip)

[树莓派 (Linux armv7l)](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/raw/master/Fuck学习强国-raspberrypi.zip) &nbsp;|&nbsp; [镜像1](https://raw.githack.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-raspberrypi.zip) &nbsp;|&nbsp; [镜像2](https://cdn.staticaly.com/gh/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/Fuck学习强国-raspberrypi.zip)

[app.asar](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/raw/master/app.asar) 更新包 &nbsp;|&nbsp; [镜像1](https://raw.githack.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/app.asar) &nbsp;|&nbsp; [镜像2](https://cdn.staticaly.com/gh/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/master/app.asar)  
(记得校验[sha256](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/blob/master/version.json))

### 在 IPFS 上的镜像

ipns://QmXBUF7nWwQeQfdiewCFUtQvb5YDPdMZ81J1EyfXpbeLVw

[IPFS镜像1](https://cloudflare-ipfs.com/ipns/QmXBUF7nWwQeQfdiewCFUtQvb5YDPdMZ81J1EyfXpbeLVw) &nbsp;|&nbsp; [IPFS镜像2](https://ipfs.io/ipns/QmXBUF7nWwQeQfdiewCFUtQvb5YDPdMZ81J1EyfXpbeLVw) &nbsp;|&nbsp; [IPFS镜像3](https://siderus.io/ipns/QmXBUF7nWwQeQfdiewCFUtQvb5YDPdMZ81J1EyfXpbeLVw)

## 使用方法

* 请解压后点击 `Fuck学习强国.exe` 来启动程序。
* 对于Linux用户，请在使用前为程序添加可执行权限: `chmod +x Fuck学习强国`
* 如果你没有登录账号，请在打开的页面中扫描二维码登录。
* 等待打开的窗口中的程序自动完成“学刁”，你可以用这台电脑做其他事情，但不要 最小化 或 关闭 那个窗口。

## 直接在命令行界面运行

以 Ubuntu 系统 (Linux x86_64) 为例

```sh
# 安装依赖
sudo apt update
sudo apt upgrade
sudo apt-get install -y \
    wget \
    unzip \
    libgtk-3-0 \
    xvfb \
    libxss1 \
    libnss3 \
    libasound2

Xvfb -ac -screen scrn 1280x2000x24 :9.0 &
export DISPLAY=:9.0

# 下载并解压程序
wget -O fuck-xuexiqiangguo.zip https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/raw/master/Fuck学习强国-linux.zip
unzip -q -d ./fuck-xuexiqiangguo/ fuck-xuexiqiangguo.zip

cd fuck-xuexiqiangguo
chmod +x ./Fuck学习强国

# 运行程序
./Fuck学习强国 --headless

# 等待片刻，使用学习强国APP扫描屏幕上的二维码登录
```

## 命令行选项

使用 `./Fuck学习强国 --help` 查看命令行选项帮助

## 更新方法

使用最新的[app.asar](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/raw/master/app.asar)替换resources/app.asar

对于Mac用户，请替换Contents/Resources/app.asar

[version.json](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/blob/master/version.json)文件中有app.asar的sha256校验值，可自行核对。

## Changelog

[CHANGELOG.md](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/blob/master/CHANGELOG.md)

## License

Fuck XueXiQiangGuo is licensed under MIT License

[源代码](https://github.com/fuck-xuexiqiangguo/source-code)

---

本软件为公益性质，永久免费使用

如果你为本软件支付过费用，请立即退款

不接受捐款
