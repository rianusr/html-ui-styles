# 20 种 HTML UI 风格模板

> 🚀 **[在线预览 →](https://rianusr.github.io/html-ui-styles/)**

同一套页面内容，20 种截然不同的 UI 设计语言。纯 HTML + CSS + JS，零依赖，开箱即用。

## 预览

- **在线体验**：[https://rianusr.github.io/html-ui-styles/](https://rianusr.github.io/html-ui-styles/)
- **本地预览**：浏览器直接打开 `index.html`

## 风格列表

| 风格 | 文件 |
|---|---|
| 技术文档 | `techdocs-yolo.html` |
| 数据看板 | `dashboard-yolo.html` |
| 极简主义 | `minimal-yolo.html` |
| 玻璃拟态 | `glass-yolo.html` |
| 新拟物 | `neu-yolo.html` |
| 野兽派 | `brutal-yolo.html` |
| 赛博朋克 | `cyber-yolo.html` |
| 材质设计 | `material-yolo.html` |
| 像素复古 | `retro-yolo.html` |
| 国际排版 | `swiss-yolo.html` |
| 拟真风格 | `skeu-yolo.html` |
| 极光渐变 | `aurora-yolo.html` |
| 孟菲斯 | `memphis-yolo.html` |
| 蒸汽波 | `vaporwave-yolo.html` |
| 流畅设计 | `fluent-yolo.html` |
| 酸性设计 | `acid-yolo.html` |
| 波普艺术 | `popart-yolo.html` |
| 侘寂 | `wabi-yolo.html` |
| 便当盒 | `bento-yolo.html` |
| 粘土风 | `clay-yolo.html` |

## 技术栈

- 纯 HTML + CSS + Vanilla JS，无框架依赖
- 无需构建，浏览器直接打开
- CSS 变量驱动主题系统，换色换字体一行搞定
- SVG 内联图表，无外部图片资源
- 响应式布局，适配桌面到移动端
- Google Fonts（Playfair Display、Inter、Space Mono）

## 使用方式

```bash
# 克隆
git clone https://github.com/your-username/html-ui-styles.git

# 直接打开
open index.html
```

## 每个模板包含的组件

以 YOLO 目标检测为示例内容，每个模板均包含完整的 UI 组件集：

**布局与导航**：侧边栏、顶部导航栏、面包屑、分页  
**信息展示**：英雄区（Hero）、统计卡片、数据表格、徽章、提示通知  
**图表与可视化**：架构流程图、SVG 柱状图、SVG 散点图、进度条  
**交互控件**：按钮组、表单（输入框/下拉框/滑块/开关/颜色选择器）、筛选标签  
**内容区块**：模型卡片、折叠面板、嵌套标签页、代码块、时间轴、头像组  
**浮层组件**：弹窗（Modal）、Toast 消息提示、悬浮工具提示

## 二次开发

每个模板为独立 HTML 文件，CSS 变量定义在文件头部，替换为自己的内容即可：

```css
:root {
  --bg: #f8f7f4;        /* 背景色 */
  --surface: #ffffff;   /* 卡片/面板色 */
  --text: #1a1a1a;      /* 正文色 */
  --primary: #1a1a1a;   /* 主色调 */
  /* ... 更多变量 */
}
```

## License

MIT
