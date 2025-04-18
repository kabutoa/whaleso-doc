# Whaleso Documentation

基于VitePress构建的文档示例网站

## 环境要求

- Node.js 版本 18 或更高
- pnpm 包管理器

## 安装

1. 克隆仓库：

```bash
git clone https://github.com/yourusername/whaleso-doc.git
cd whaleso-doc
```

2. 安装依赖：

```bash
pnpm install
```

## 本地开发

启动开发服务器：

```bash
pnpm docs:dev
```

访问 `http://localhost:5173` 查看文档站点。

## 构建

构建生产版本：

```bash
pnpm docs:build
```

预览构建结果：

```bash
pnpm docs:preview
```

#+ 项目结构

```
whaleso-doc/
├── .vitepress/     # VitePress 配置目录
├── src/            # 文档源文件
│   ├── index.md    # 首页
│   └── ...         # 其他文档页面
└── package.json    # 项目配置文件
```
