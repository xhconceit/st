# 我的 st 构建

st 是一个简单的终端仿真器

## 要求

构建 st 前, 需要有 Xlib 头文件

## 安装

编辑 config.mk 来匹配你的本地设置 (st 将默认安装在 /usr/local)
之后通过以下命令安装 st (必须使用 root 用户):


```shell
make clean install
```

## 字体

Source Code Pro

+ 安装

arch :

```shell
sudo pacman -S adobe-source-code-pro-fonts
```

## 自定义补丁


## 运行 st

```shell
st

```
