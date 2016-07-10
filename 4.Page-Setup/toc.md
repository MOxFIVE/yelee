# 文章目录

配置中启用目录
```yaml
toc:
  on: true
```

指定文章中关闭目录 `toc: false`
```yaml
title: Hello World
date: 2015-08-19 00:00:00
toc: false
---
```

![目录](/src/feat.toc.gif)

## 1. 目录序号
是否显示目录标题前的序号

```yaml
toc:
  list_number: true
```

指定文章中隐藏目录序号 `toc_list_number: false`
```yaml
title: Hello World
toc_list_number: false
---
```

<blockquote class="note">
    文章内目录设置的优先级高于主题默认设置
</blockquote>

## 2. 目录最大级数

可选值：1 - 6，默认 3 （表示目录中只显示到三级标题 `### H3`，再次级的标题会被隐藏）

```
toc:
  max_depth: 3
```

## 3. 标题不换行

目录区的标题保持单行显示，有截断则在行末显示 `...`，鼠标悬停时显示完整标题

```yaml
toc:
  nowrap: false
```

![单行标题](/src/toc-nowrap.gif)
