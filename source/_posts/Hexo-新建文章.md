---
title: Hexo 新建文章
date: 2025-08-30 22:36:29
categories: 
- Hexo
tags:
- Hexo
---

## 准备工作
### 创建“分类”选项
``` bash
hexo new page categories
```
打开文件，并修改
``` markdown
---
title: 文章分类
date: 2017-05-27 13:47:40
---

<修改为>

---
title: 文章分类
date: 2017-05-27 13:47:40
type: "categories"
---
```

### 创建“标签”选项
``` bash
hexo new page tags
```
打开文件，并修改
``` markdown
---
title: tags
date: 2025-08-30 22:39:50
---

<修改为>

---
title: tags
date: 2025-08-30 22:39:50
type: "tags"
---
```


## 开始 Hero 的第一篇文章
### 新建文章
``` bash
hexo new "标题"
```
打开文件后可以先看到如下内容
> title: 标题
> date: 2025-08-30 22:06:13
> tags: 

### 添加分类
``` markdown
categories: 
- aaaa
```

### 添加标签
``` markdown
tags: 
- aaaa
- bbbb
```

