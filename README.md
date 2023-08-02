# ShellClash rules

[![](https://img.shields.io/github/release/Dreamacro/Clash.svg?style=flat-square&label=Clash)](https://github.com/Dreamacro/clash/releases)
[![](https://img.shields.io/github/release/juewuy/ShellClash.svg?style=flat-square&label=ShellClash&colorB=green)](https://github.com/juewuy/ShellClash/releases)

## 简介：

- 本存储库是 ShellClash `rules` 个人修改版
- 目前仅修改了 `/rules/ShellClash.ini` 一个文件
  - 也就是[这个](https://github.com/UlinoyaPed/ShellClash/raw/master/rules/ShellClash.ini) `https://github.com/UlinoyaPed/ShellClash/raw/master/rules/ShellClash.ini`

- 所有修改都是按照我自己的胃口来的，不一定适合每个人

## 有何不同：

- 添加：
  - 阿根廷、土耳其节点分组
  - 普通节点
    - 匹配标注 **`1`倍** 和 **未标注倍数**的节点
- 修改
  - 省流节点
    - 匹配 **`0.1~0.9`倍** 和 **`0.01~0.99`倍**的节点
  - 高级节点
    - 匹配 **`1.1~9.9`倍** 和 **`>=2`倍** 的整数倍节点
  - 其他分组的**顺序**
  - 个别分组的`emoji`**图标**

不保证完全无`Bug`，有问题发[**issue**](https://github.com/UlinoyaPed/ShellClash/issues)

## 使用方法：

补全`&url=`（注意`target=clash`参数填自己的软件类型）

```
https://api.tsutsu.one/sub?target=clash&insert=true&new_name=true&scv=true&udp=true&exclude=&include=&url=在此处填写您的订阅地址&config=https://github.com/UlinoyaPed/ShellClash/raw/master/rules/ShellClash.ini
```

如果你想获得最新功能（和最新Bug），可以使用`dev`分支

```
https://api.tsutsu.one/sub?target=clash&insert=true&new_name=true&scv=true&udp=true&exclude=&include=&url=在此处填写您的订阅地址&config=https://github.com/UlinoyaPed/ShellClash/raw/dev/rules/ShellClash.ini
```

**不用为节点倍率填写排除，内部已经将各类型节点分类好**

## ShellClash 功能：

- 通过管理脚本在Shell环境下便捷使用[Clash](https://github.com/Dreamacro/clash)
- 支持在Shell环境下管理[Clash各种功能](https://lancellc.gitbook.io/clash)
- 支持在线导入[Clash](https://github.com/Dreamacro/clash)支持的分享、订阅及配置链接
- 支持配置定时任务，支持配置文件定时更新
- 支持在线安装及使用本地网页面板管理内置规则
- 支持路由模式、本机模式等多种模式切换
- 支持在线更新

## 机场推荐：

#### [**夜煞云**，流媒体解锁>99.16%，ChatGPT 100%解锁，月付推荐](https://www.night-furyx.com/index.php#/register?code=jcNB7Vp2)
#### [**COO NETWORK**，年付11.88每月50G](https://web.coo.wiki/#/register?code=Ucjvsgka)
