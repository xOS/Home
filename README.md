# Home

保留 Identity 旧版视觉的个人主页，页面样式和 70 个 SVG 图标均内置在 `index.html` 中，不依赖 Google Fonts、Font Awesome 字体或第三方脚本。

## 项目目录

- 根目录：当前维护的旧版视觉
- `redesign/`：已归档的新设计版本，可独立作为静态站点运行

## 使用内置图标

旧版圆形链接按钮保持原来的 `3.75em` 尺寸。新增链接时可复用内置图标：

```html
<a href="..." class="icon" title="链接名称">
  <svg class="icon-svg" aria-hidden="true">
    <use href="#icon-github" />
  </svg>
  <span class="label">链接名称</span>
</a>
```

图标 ID 与 `redesign/README.md` 中的清单一致，统一使用 `icon-*` 前缀。
