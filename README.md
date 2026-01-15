# personal guide page
个人引导页，适用于个人网站首页

![](show-off/Xnip2021-12-29_14-33-20.jpg)

## ✨ 特性

- **极简设计**: 采用左右分栏布局，左侧为大图背景，右侧为个人信息与导航链接。
- **响应式布局**: 适配不同尺寸的屏幕设备。
- **易于定制**: 代码结构清晰，只需简单修改 HTML 即可替换为自己的信息。
- **动效支持**: 内置基础的 jQuery 脚本和交互效果。

## 📂 项目结构

```text
├── index.html          # 网站主入口文件
├── css/
│   └── style.css       # 样式文件
├── js/
│   ├── js.js           # 页面逻辑与特效脚本
│   └── jquery.min.js   # jQuery 库
├── images/             # 图标与静态资源
└── show-off/           # 演示截图
```

## 🚀 快速开始

1.  **下载或克隆**此仓库到本地。
2.  直接在浏览器中打开 `index.html` 即可预览效果。

## 🛠 如何定制

你可以通过编辑 `index.html` 文件来修改页面内容：

1.  **修改导航链接**:
    找到 `<ul id="menu-primary" class="index_nav">` 部分，修改 `<a>` 标签的 `href` 属性和文本内容，将其替换为你自己的链接（如 GitHub、博客、微博等）。

2.  **更换背景图片**:
    找到 `<section class="left" ...>` 标签，修改 `style="background-image: url('...')"` 中的 URL 为你喜欢的图片地址。

3.  **修改个人信息**:
    - **头像**: 修改 `.index_txt img` 的 `src` 属性。
    - **昵称与签名**: 修改 `<h1>` 和 `<p>` 标签的内容。
    - **位置**: 修改 `.zuobiao` 标签的内容。

4.  **底部版权**:
    在 `<footer>` 标签中更新版权年份和备案号信息。

## 📦 技术栈

- HTML5
- CSS3
- JavaScript (jQuery)
