# Su (素) - Hugo Theme

A minimalist, text-only Hugo theme with dark mode.

[中文文档](README_CN.md)

---

## Features

- Minimalist design
- Dark theme
- Responsive
- Code highlighting
- Friends links

## Demo

https://xeron2000.github.io/hugo-theme-su/

## Installation

```bash
cd your-hugo-site
git submodule add https://github.com/Xeron2000/hugo-theme-su.git themes/Su
```

## Configuration

`hugo.yaml`:

```yaml
baseURL: "https://yourdomain.com"
languageCode: "en-US"
title: "Your Site Title"
theme: "Su"

params:
  about:
    title: "About Me"
    content: "Your introduction"
```

## Content Structure

```
content/
├── about.md          # About page
└── posts/            # Posts directory
    └── post-1.md
```

## Friends Links

Create `data/friends.yaml`:

```yaml
- name: "Friend Name"
  url: "https://friend-site.com"
  desc: "Description"
```

## Preview

```bash
cd exampleSite
hugo server -D
```

Visit `http://localhost:1313`

## License

[MIT License](LICENSE)
