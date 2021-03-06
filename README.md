# visitopia-dl

## 关于

一个用于下载 `看理想` 网站免费栏目音频/视频文件的脚本.

## 功能实现

- 单线程下载音频/视频文件 (5min预览版)
- 检索新内容并下载
- 使用命令行运行脚本
- 下载单个视频/音频文件

## 使用方法

### 使用

    python visitopia-dl.py [options]

### 参数

    -h | --help 获取帮助
    -u | --url=<节目链接>

### 举例

短参数:

```
$ python3 visitopia-dl.py -u https://shop.vistopia.com.cn/detail?id=TwTtq
$ python3 visitopia-dl.py -u https://shop.vistopia.com.cn/article?article_id=426144&source=article
```

长参数:

```
$ python3 visitopia-dl.py --url=https://shop.vistopia.com.cn/detail?id=TwTtq
$ python3 visitopia-dl.py --url=https://shop.vistopia.com.cn/article?article_id=426144&source=article
```

## Todo

- [x] 单线程下载对应免费栏目音频文件
- [x] 下载新内容
- [x] 命令行参数
- [x] 免费视频栏目预览版下载
- [ ] 免费视频栏目完整版下载
- [x] 单篇节目下载
- [ ] 多线程下载
- [ ] 断点继续下载

## 声明

本项目用于满足个人收听需求, 下载内容为看理想免费收听栏目, 仅供个人学习使用, 请勿用于他途.
