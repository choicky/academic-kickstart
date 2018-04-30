+++
date = 2018-04-30T21:35:00+08:00 # 完整格式为：yyyy-mm-ddThh:mm:ss+08:00
title = "将网站托管到 netlify" 
slug = "hugo-netlify" #文件名为 yyyy-mm-dd-slug，所以要去掉 yyyy-mm-dd-
categories = [
    "互联网", # Web，建议附加更具体的 tags
]
tags = [
    "hugo", # tag 举例
    "netlify"
]
+++
## Hugo
[Hugo](https://gohugo.io/) 是一个将 [Markdown](https://zh.wikipedia.org/zh-hans/Markdown) 格式的文本转换成静态网页的工具。

本站目前使用 hugo 生成，选用的主题是 [academic](https://themes.gohugo.io/academic/)。

## Netlify
[Netlify](https://www.netlify.com/) 是一个托管平台。这托管平台有两个优点：

* 能够从 [github](https://github.com/) 抓取 Markdown 源码过去，然后运行并生成静态网页文件。这个功能与一台 VPS 差不多。
* 支持自定义域名，且支持 https 。例如， https://zhoucaiqi.com 就是能访问到 托管到 Netlify 的 zhoucaiqi.netlify.com
