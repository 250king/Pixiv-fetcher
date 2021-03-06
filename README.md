# P站图片批量获取程序
##### 针对P站的反爬措施的升级——在登录过程新增reCAPTCHA人机验证组件，所以先暂时通过伪造Cookie来模拟登录。
##### 当然也考虑到这个方法的缺点，在CLI界面就玩不了了，所以全自动模拟登录现在还在努力研究。
## 前提条件
##### 计算机已安装
##### 1. Python v3+编译器
##### 2. 迅雷 v9+下载器
## 使用
##### 通过Git克隆项目到本地
```
git clone https://github.com/250king/Pixiv-fetcher.git
```
##### 也可以可以直接下载ZIP压缩包，然后在本地解压。
##### 然后在项目的根目录里就可以用Python直接运行
```
python fetcher.py
```
## 注意事项
##### 1. **请尊重画师的劳动成果**，该程序以及获取到的相关资源**仅用于个人用途**！
##### 2. 由于功能有限，目前只有**有梯子**的计算机或者**可以跑GUI界面**的国外服务器可以使用，全自动模拟登录正在努力研究，敬请谅解！
## 开源许可证
##### Apache License v2.0
###### Copyright 2020 250king. All rights reserved.