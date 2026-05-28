# XG-Resume

基于 [Start Bootstrap - Resume](https://github.com/StartBootstrap/startbootstrap-resume) 模板改造的个人简历网站，采用简洁优雅的单页式布局设计，适合作为求职或项目积累展示用途。

查看网址：[www.xinge.cc.cd](https://www.xinge.cc.cd)（需国内网络访问）

## 页面结构

| 板块                 | 说明                         |
| -------------------- | ---------------------------- |
| **About**      | 基本信息、联系方式、社交链接 |
| **Skills**     | 专业技能与核心能力           |
| **Experience** | 实习经历与项目经历           |
| **Campus**     | 在校经历                     |
| **Awards**     | 奖项与证书                   |
| **Interests**  | 个人兴趣                     |

## 使用方式

### 开发构建

```bash
cd startbootstrap-resume
npm install
npm start
```

#### npm 脚本

- `npm start` — 启动开发预览，监听文件变化并自动刷新浏览器
- `npm run build` — 构建项目，将资源输出到 `dist` 目录
- `npm run clean` — 清除 `dist` 目录

## 文件结构

```
startbootstrap-resume/
├── dist/                  # 最终输出目录（直接使用即可）
│   ├── index.html         # 简历主页面
│   ├── css/styles.css     # 样式文件
│   ├── js/scripts.js      # 脚本文件
│   └── assets/img/        # 图片资源（头像、favicon 等）
├── src/                   # 源码目录（开发用）
│   ├── pug/               # Pug 模板
│   ├── scss/              # SCSS 样式源码
│   ├── js/                # JS 源码
│   └── assets/            # 源图片资源
├── scripts/               # 构建脚本
└── package.json
```

## 致谢

- 模板来源：[Start Bootstrap - Resume](https://github.com/StartBootstrap/startbootstrap-resume)
- 基于 [Bootstrap 5](https://getbootstrap.com/) 构建
- 图标来自 [Font Awesome](https://fontawesome.com/)
- 字体来自 [Google Fonts](https://fonts.google.com/)

## License

原模板基于 [MIT License](startbootstrap-resume/LICENSE) 开源。
