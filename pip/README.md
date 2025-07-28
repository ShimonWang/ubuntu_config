## 文件路径

~/.config/pip/pip.conf

## 使用须知

**查看pip配置**

```
pip config list
```

## 修改配置

1. 设置代理和镜像源
```
[global]
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
proxy = http://127.0.0.1:7897

[install]
trusted-host = pypi.tuna.tsinghua.edu.cn

```

## 参考资料

1. [https://blog.csdn.net/m0_57567093/article/details/127455214
](https://blog.csdn.net/hu_jianyue/article/details/135743384)