# 从0开始的nodeJs

## 0开始

​	很久很久前好奇心驱使下冲了20买了个华为云弹性云服务器

​	装了个Ubuntu系统，其他全空



起初想在里边大展拳脚，但之后一直搁置，什么都没做

## 想法

不知道拿来做什么，正后悔不应继理发店买卡、烤鸭店储蓄、喜茶优惠券之后，又打了个价值20块的水漂时，想起来可以尝试实践一下express，还可以把工作之余写的一些小程序运行上去，嘿嘿



## day-0环境

首先安装npm和nodejs，直接不挑版本一顿瞎装

```
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -`
sudo apt install -y nodejs`
```

没有报错，验证下

```
npm -v
node -v
```

提示当前版本，分别是10.9和22.11

再来安装express：

```
npm install express
```

不出意外报错ETIMEOUT，用npm官方镜像好像经常会超时，在网上搜了个镜像试了下：

`npm install express --registry=https://registry.npmmirror.com`

之后到项目node_module下可以找到express，package.json的依赖名里也有。

今天已经很努力啦，就到这里吧
