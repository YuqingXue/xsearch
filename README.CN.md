[English](./README.md) | 简体中文

# xsearch

利用Python实现搜索引擎中大批量关键词的搜索、导出与分析。

## 启动

### 安装要求

***Python*** Python 3

***Chrome*** 下载浏览器，并根据帮助(E) > 关于Google Chrome(G) 查看Chrome浏览器版本号

***ChromeDriver*** 下载与Chrome浏览器版本一致的驱动 [链接1](https://sites.google.com/a/chromium.org/chromedriver/downloads) [链接2](http://npm.taobao.org/mirrors/chromedriver/) [链接3](https://chromedriver.storage.googleapis.com/index.html)


### 安装步骤

**pip安装** 

`pip install search`

**或者[PypI](https://pypi.org/project/xsearch/#files)search-0.0.1tar.gz) 网站下载xsearch-0.0.8.tar.gz文件并键入以下命令安装**

`python setup.py install`

## 使用

### 支持搜索引擎

- google.com 或 google.com.hk

- baidu.com

- bing.com 或 cn.bing.com

- sogou.com
  
- weixin.sogou.com

### 代码

```
import xsearch
xsearch.search()
```

## 版权说明

该项目签署了[MIT](./LICENSE.txt)授权许可。