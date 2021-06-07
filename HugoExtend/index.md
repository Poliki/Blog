---
title: "Hugo拓展版本"
description: Hugo Extend
date: 2021-6-6
slug:  "Hugo Extend"
image: "cover.jpg"
tags:

   - BLOG

---

##### 解决困扰已久的Hugo拓展版本问题

```
error: failed to transform resource: TOCSS: failed to transform "scss/main.scss" (text/x-scss): this feature is not available in your current Hugo version
```

![报错图片](D:\Blog\HugoExtend\报错.png)

由于这个问题，上一次的博客更新也延期了，这次尝试解决一下

---

###### 1.前往下载Extend版本

[官方链接]: https://github.com/gohugoio/hugo/releases

![拓展版本](D:\Blog\HugoExtend\拓展版本.png)

之前是直接使用一般版本的，现选择拓展版本

---

###### 2.安装Extend版本

拓展版本使用方法同基础版本，更新版本需要做几件事情

- 新建目录解压文件

【默认已安装Git，已绑定GitHub仓库】

右键git bash查看当前版本(上个版本也要已绑定到环境变量中，图为已版本迭代)

![](D:\Blog\HugoExtend\查看版本.png)



- 配置环境变量 

  [参考]: https://blog.csdn.net/weixin_41263449/article/details/107584336?utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~aggregatepage~first_rank_v2~rank_aggregation-1-107584336.pc_agg_rank_aggregation&amp;utm_term=%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8Fhugo&amp;spm=1000.2123.3001.4430

- 再次确认是否完成环境配置

- 此时相当于重新配置Hugo，可参考另一篇文章



