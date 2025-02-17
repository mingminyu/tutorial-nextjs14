# NextJS 14 教程

启动文档服务请执行以下操作。

## 1. 启动文档服务

### 1.1 安装依赖

首先通过 Python 安装依赖：

```bash
pip install mkdocs-material mkdocs-redirects mkdocs-minify-plugin mkdocs-awesome-pages-plugin  mkdocs-glightbox
```

### 1.2 启动文档服务

项目根目录下执行如下命令：

```bash
mkdocs serve -a localhost:8000
```

访问 http://localhost:8000/ 即可查看文档。


## 2. 启动服务

### 2.1 安装依赖

```bash
npm install
```

### 2.2 启动服务

```bash
npm run dev

# 构建 & 生产
npm run build
npm run start
```
