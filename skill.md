# Compliance Doc - Documentation Repository

## Project Overview
这是一个基于 Doom 框架的 MDX 文档仓库，用于 Alauda Compliance 产品文档。

## Project Structure
```
/Users/mac/product-doc/compliance-doc/
├── docs/
│   ├── en/
│   │   ├── fuctions/       # 功能文档
│   │   │   ├── scan-management.mdx
│   │   │   ├── email-notification.mdx
│   │   │   ├── export-reports.mdx
│   │   │   ├── quick-start.mdx
│   │   │   └── index.mdx
│   │   ├── overview/       # 概述文档
│   │   │   ├── architecture.mdx
│   │   │   ├── intro.mdx
│   │   │   ├── release_notes.mdx
│   │   │   └── index.mdx
│   │   ├── install.mdx     # 安装文档
│   │   └── index.mdx
│   ├── shared/             # 共享资源
│   └── i18n.json
├── package.json
├── sites.yaml
└── README.md
```

## Commands
- `yarn dev`: 启动本地开发服务器，文件修改会实时更新
- `yarn build`: 构建生产环境代码，生成静态文件到 `dist` 目录
- `yarn serve`: 本地预览构建后的静态文件
- `yarn lint`: 检查文档语法和格式

## Notes
- 文档使用 MDX 格式，支持 Markdown 语法和 React 组件
- 导航栏相关修改需要重启开发服务器才能生效
