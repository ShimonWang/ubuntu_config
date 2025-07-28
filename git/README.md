## 文件路径

~/.gitconfg

## 使用须知

尚未配置用户名和邮箱

**查看全局代理**

```
git config -l --global
```

**查看当前代理**

```
git config -l
```

## 修改配置

1. 设置git代理端口
```
[http]
	proxy = http://127.0.0.1:7897
	postBuffer = 524288000
	maxRequestBuffer = 100M
[https]
	proxy = https://127.0.0.1:7897
```

2. 默认主分支
```
[init]
	defaultBranch = main
```
