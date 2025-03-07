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




