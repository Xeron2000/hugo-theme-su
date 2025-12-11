# Su (素) - Hugo 主题

极简主义深色 Hugo 主题

[English](README.md)

---

## 特性

- 极简设计 - 纯文字布局
- 深色主题
- 响应式
- 代码高亮
- 友情链接

## 演示

https://xeron2000.github.io/hugo-theme-su/

## 安装

```bash
cd your-hugo-site
git submodule add https://github.com/Xeron2000/hugo-theme-su.git themes/Su
```

## 配置

`hugo.yaml`:

```yaml
baseURL: "https://yourdomain.com"
languageCode: "zh-CN"
title: "站点标题"
theme: "Su"

params:
  about:
    title: "关于我"
    content: "你的介绍"
```

## 内容结构

```
content/
├── about.md          # 关于页面
└── posts/            # 文章目录
    └── post-1.md
```

## 友情链接

创建 `data/friends.yaml`:

```yaml
- name: "朋友名称"
  url: "https://friend-site.com"
  desc: "描述"
```

## 预览

```bash
cd exampleSite
hugo server -D
```

访问 `http://localhost:1313`

## 许可证

[MIT License](LICENSE)
