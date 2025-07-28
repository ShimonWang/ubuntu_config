## 文件路径

~/.condarc

## 使用须知

**conda查看配置config命令**

```
conda config --show
```

**查看conda配置文件的位置**

```
conda config --show-sources
```

## 修改配置

1. 镜像源
```
channels:
  - defaults
show_channel_urls: true
default_channels:
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
custom_channels:
  conda-forge: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  msys2: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  bioconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  menpo: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch-lts: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  simpleitk: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
```

2. 打开终端默认激活base环境
```
auto_activate: false
```

## 参考资料

1. https://blog.csdn.net/Zero_Muzi/article/details/120575959
2. https://blog.csdn.net/qq_34848334/article/details/129397912
3. https://blog.csdn.net/leviopku/article/details/98766822