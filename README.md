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

### 打补丁

```shell
patch < [patch file]
```

1. copyurl

[copyurl](https://st.suckless.org/patches/copyurl/) 选择并复制 URL

2. scrollback

[scrollback](https://st.suckless.org/patches/scrollback/) 滚动查看终端输出

3. hidecursor

[hidecursor](https://st.suckless.org/patches/hidecursor/) 输入时隐藏鼠标光标，移动鼠标时显示鼠标光标

4. anysize

[anysize](https://st.suckless.org/patches/anysize/) 终端输出填满整个 st

5. alpha

[alpha](https://st.suckless.org/patches/alpha/) 更改终端背景不透明

+ 要求
 compton|xcompmgr|picom 需要安装其中一个才生效

## 快捷键

| 键位    | 说明                    |
| ------- | ----------------------- |
| <A-S-l> | 选择复制 URL 并高亮显示 |
| <A-S-k> | 向上翻 1 页终端输出     |
| <A-S-j> | 向下翻 1 页终端输出     |
| <C-S-k> | 向上翻 10 行终端输出    |
| <C-S-j> | 向下翻 10 行终端输出    |
| <C-A-k> | 向上翻 1 行终端输出     |
| <C-A-j> | 向下翻 1 行终端输出     |

## 运行 st

```shell
st

```
