---
title: Hexo-theme-pure主题books默认选择想读
date: 2013/7/13 20:46:25
categories: 技术
tags: 工具/插件
---


Hexo-theme-pure主题books默认是选择在读的，现在我们需要将想读移动到前面
## 步骤

### Step 1.修改样式
   在主题的layout->_partial的 archive-book.ejs调换想读和在读的顺序

### Step 2.修改js
   在主题的layout->_script的 douban.ejs 将show(reading)改成show('wish')，然后刷新就有效果了


