# 新窗口打开链接

```yaml
open_in_new:
  ## `global` 0: 分开设置, 1: 全部在新标签打开, 2: 全部在"当前"标签打开
  global: 0 # 0-2
  title: false # 主页文章标题
  post: false # 正文中的链接
  tags: false # 标签
  categories: false # 分类
  article_nav: false # 导航
  archives: true # 归档
  mini_archives: true # 迷你归档
  menu: false # 边栏菜单
  friends: true  # 友情链接
  socail: true # 社交图标
```

<blockquote class="note">当设置<code>global: 0, post: false</code>时，受站点配置影响，正文区内的站外链接默认依旧在新标签中打开</blockquote>

```yaml
external_link: true # 在新标签中打开站外链接
```