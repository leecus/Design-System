# Design System

一个轻量级、纯 CSS 的企业级前端组件库，基于统一的设计语言构建。

## 快速开始

在 HTML 中引入完整的样式文件：

```html
<link rel="stylesheet" href="dist/design-system.css">
```

或按需引入单个组件模块（位于 `components/` 目录）：

```html
<link rel="stylesheet" href="components/tokens.css">
<link rel="stylesheet" href="components/button.css">
```

## 组件列表

| 模块 | 文件 | 说明 |
|------|------|------|
| Design Tokens | `tokens.css` | 色彩、阴影、圆角、字体、动效 |
| Base | `base.css` | CSS 重置、排版、工具类 |
| Topbar | `topbar.css` | 顶栏、品牌标识、用户芯片 |
| Navigation | `navigation.css` | Nav Tab、Sub Nav、Breadcrumb |
| Button | `button.css` | 6 种颜色变体、3 种尺寸、禁用状态 |
| Form | `form.css` | Input、Select、Textarea、Checkbox、Radio、Switch、Filter Bar |
| Badge | `badge.css` | Badge、Status 状态指示、Data Tag 数据标签 |
| Card | `card.css` | Module Card、Stat Cards 统计卡片 |
| Table | `table.css` | Data Table、Sortable Header、Pagination |
| Feedback | `feedback.css` | Modal 模态框、Drawer 抽屉、Toast 提示、Alert 警示框 |
| Data Display | `data-display.css` | Log/Result Panel、Diff Viewer、Empty State、Config Layout |
| Avatar | `avatar.css` | 4 种尺寸、5 种配色、在线状态指示 |
| Progress | `progress.css` | 4 种状态色的进度条 |
| Skeleton | `skeleton.css` | 骨架屏加载占位 |
| Tooltip | `tooltip.css` | 上/下/左/右 4 方向工具提示 |
| Animation | `animation.css` | 页面入场、卡片入场、脉冲、淡入动画 |

## 设计令牌

- **色彩**: 5 组品牌色（ink/coral/teal/amber/slate），每组含主色 + 柔和色 + 光环色
- **阴影**: 4 级（sm/md/lg/xl）
- **圆角**: 5 级（sm/md/lg/xl/pill）
- **字体**: Noto Sans SC（正文）/ Playfair Display（标题）/ DM Mono（代码）
- **动效**: ease 缓动 + spring 弹性曲线，3 档时长（fast/base/slow）

## 浏览器支持

Chrome、Firefox、Safari、Edge 等现代浏览器。

## License

MIT
