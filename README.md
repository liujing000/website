# LJ · 个人主页

一个简洁的个人主页网站，使用纯 HTML/CSS/JS 构建，无任何依赖。

## 预览

直接用浏览器打开 `index.html` 即可查看，或使用任意静态服务器：

```bash
python3 -m http.server 8000
```

然后访问 http://localhost:8000

## 结构

```
website/
├── index.html   # 页面主体（含内联 CSS/JS）
├── README.md
└── .gitignore
```

## 特性

- 响应式设计，适配桌面与移动端
- 纯静态，零依赖，加载快速
- 语义化 HTML + 无障碍支持
