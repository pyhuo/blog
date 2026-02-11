+++
date = '2026-02-11T19:32:16+08:00'
draft = true
title = 'My First Post'
+++



```text
层级	文件位置	用途
基础模板	layouts/_default/baseof.html	页面骨架、全局结构
列表模板	layouts/_default/list.html	分类、标签、首页列表
单页模板	layouts/_default/single.html	文章详情页
类型模板	layouts/posts/single.html	特定内容类型模板
部分模板	layouts/partials/	可复用组件
```

# [内容管理基础](https://jimmysong.io/zh/book/hugo-handbook/content-organization/content-management/)

```
my-site/
├── archetypes/     # 内容模板
├── assets/         # 资源文件（需要处理的）
├── content/        # 内容源文件
├── data/          # 数据文件
├── layouts/       # 布局模板
├── static/        # 静态文件（直接复制）
├── themes/        # 主题
└── hugo.toml      # 配置文件
```


# content 目录结构

```
content/
├── _index.md              # 网站首页内容
├── about.md               # 关于页面
├── posts/                 # 文章目录
│   ├── _index.md         # 文章列表页
│   ├── first-post.md     # 单个文章
│   └── second-post.md    
├── projects/              # 项目目录
│   ├── _index.md         # 项目列表页
│   └── project-one/      # 页面包
│       ├── index.md      # 项目详情
│       ├── image1.jpg    # 项目资源
│       └── image2.jpg    
└── docs/                 # 文档目录
    ├── _index.md         # 文档首页
    ├── getting-started.md
    └── advanced/
        ├── _index.md
        └── configuration.md
```
