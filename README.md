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
```


#### 按键


可以在 `config.h` 中 `shortcuts` 中配置按键。

| 按键 | 描述 |
| -- | -- |
| <A-l> | 下一个 `url` |




