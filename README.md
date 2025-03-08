# st

[st](https://st.suckless.org/)


## 源码构建

```bash
git clone https://git.suckless.org/st
sudo make clean install
```


## 补丁


补丁命令

```bash
patch < [patch]
```

打补丁后的文件

> `*.orig` 补丁后的备份文件
> `*.rej` 补丁失败被拒绝的更改
> `*.o` 编译后的中间文件

### copyurl

[copyurl](https://st.suckless.org/patches/copyurl/)

```bash
wget https://st.suckless.org/patches/copyurl/st-copyurl-multiline-20230406-211964d.diff
patch < st-copyurl-multiline-20230406-211964d.diff
make clean install
```


#### 按键


可以在 `config.h` 中 `shortcuts` 中配置按键。

| 按键 | 描述 |
| -- | -- |
| <A-l> | 下一个 `url` |



### scrollback

[scrollback](https://st.suckless.org/patches/scrollback/)


```bash
wget https://st.suckless.org/patches/scrollback/st-scrollback-0.9.2.diff
patch < st-scrollback-0.9.2.diff
make clean install
```

#### 按键

| 按键 | 描述 |
| --   |  --  |
| \<S-PageUp> | 上一页 |
| \<S-PageDown> | 下一页 |



### hidecursor


[hidecursor](https://st.suckless.org/patches/hidecursor/)


```bash
wget https://st.suckless.org/patches/hidecursor/st-hidecursor-0.8.3.diff
patch < st-hidecursor-0.8.3.diff
make clean install
```



### anysize

[anysize](https://st.suckless.org/patches/anysize/)

```bash
wget https://st.suckless.org/patches/anysize/st-anysize-20220718-baa9357.diff
patch < st-anysize-20220718-baa9357.diff
make clean install
```


### alpha focus highlight

[alpha focus highlight](https://st.suckless.org/patches/alpha_focus_highlight/)

```bash
wget https://github.com/juliusHuelsmann/st/releases/download/alpha_09/st-focus-20230610-68d1ad9.diff
patch < st-focus-20230610-68d1ad9.diff
make clean install
```





