---
title: "做好时刻开写的一些准备"
description: "更多时候是给太久没写博客的我的复健第一步"
date: 2025-03-27T21:21:58+08:00
image: 
math: 
license: 
hidden: false
comments: true
draft: false
---

## Hugo 命令行

进入到博客的目录后，打开一个终端输入以下内容：

```Cmdlet
# 创建一篇文章
hugo new content\post\[你的文章名称]\index.md
```

就会看到生成了一个`content\post\文章名称`文件夹，其中还有一个index.md，内容大致如下：

```Markdown
---
title: "[你的文章名称]"
description:
date: 2011-01-07T02:10:00+09:00
image:
math:
license:
hidden: false
comments: true
draft: true
---
```

当你完成编写后，可以在终端运行以下命令查看即时效果：

```Cmdlet
# 运行本地服务器查看带草稿文章状态的博客
hugo server -D
```

如果不需要这一篇文章了，直接在`content\post`中删除文章名称的文件夹即可。

然后就可以通过Git更新发布了，是不是非常简单？

暂时就这些。