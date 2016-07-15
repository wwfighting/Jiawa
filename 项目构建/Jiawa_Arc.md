---
title:  "项目技术的整体实现"
---

# UI

* 参照原app的UI风格，以及UI设计师的设计图；
* 整体偏向Material Design的设计风格；
* 主色调方面偏暖色调

# 网络通信

* 与服务器通信，采用Square公司OkHttp实现；
* 加载图片，采用Google推荐的Glide实现；
* json数据转换，采用Google推荐Gson实现

# 数据缓存

* File；
* SQLite；
* SharedPreference

# 支付功能

* BeeCloud(一个集成了支付宝，微信钱包，百度钱包等支付手段的SDK)
