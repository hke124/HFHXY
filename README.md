## 风花雪月移动版
#### 琉璃神社修改版
## 首先感谢yueeng大佬，他的代码非常酷炫，质量超高
## 大佬地址：[点击查看](https://github.com/yueeng/hacg)
![screenshot01](https://raw.githubusercontent.com/hke124/HFHXY/refs/heads/main/Screenshot_2025-06-12-02-44-57-221_io.github.yueeng.hacg.jpg)
- 原版的只是不太适合本人体验，不代表大众想法
- 改版1：禁用了所有左右滑动事件。本人低端机上特别容易误触
- 改版2：增加了跳转翻页功能，屏幕右下角可以打开。主要是如果想翻遍整个网站的情况下，没有翻页确实不行。
[点击查看](https://github.com/hke124/HFHXY/blob/main/Hacg.apk)

## 风花雪月移动版
- 增加风花雪月跟点点资源等ACG网站
- 风花雪月需要代理，点点可以直连。但网络加载速度相当感人，这个app可以提高加载速度，提高阅读体验，网络差的时候加载速度可以提高两倍，注意零的两倍还是零。
- 风花雪月利用viewpage加载图片，浏览的时候只会加载第一张图片，并不会全部加载，以此提升加载速度。其他图片需要通过左右滑动去加载。
- 点点资源对图片加载地址进行优化，打开原版会发现，它的图片是有多层跳转的，我这里直接加载最终地址，取消中间跳转。
- 图片加载运用了glide框架，增加了内存缓存以及磁盘缓存，最大缓存2G,下次读取图片直接从磁盘读取而不需要再通过网络
- 图片加载失败需要手动点击图片从新加载，当图片过大会禁止加载，从新加载无效
- 增加跳转翻页功能，以及保存当前页码功能。
# 计划功能
- 增加南+支持
- 牺牲加载速度，从内容页提取图片，在首页展示。增加标题以及图片的索引，并保存进本地。
- 增加F95zone支持

#### publish: https://github.com/hke124/HFHXY/releases

#### screenshot
风花雪月 | 点点资源
------------ | ------------- |
![screenshot01](https://raw.githubusercontent.com/hke124/HFHXY/refs/heads/main/Screenshot_2025-06-12-02-31-07-701_com.hke.hfhxy.jpg)|![screenshot02](https://raw.githubusercontent.com/hke124/HFHXY/refs/heads/main/Screenshot_2025-06-12-02-33-42-457_com.hke.hfhxy.jpg)
