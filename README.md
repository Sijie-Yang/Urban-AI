# My Jupyter Book

这是一个使用 Jupyter Book 创建的项目，用于展示和分享 Jupyter notebook 内容。

## 快速开始

### 安装依赖

```bash
pip install -r requirements.txt
```

### 构建书籍

```bash
jupyter-book build .
```

构建完成后，你可以在 `_build/html/index.html` 查看生成的网站。

### 添加新的 Notebook

1. 将你的 `.ipynb` 文件添加到 `notebooks/` 目录
2. 在 `_toc.yml` 文件中添加新文件的引用
3. 重新构建书籍

### 项目结构

```
JupyterBook/
├── _config.yml          # 主配置文件
├── _toc.yml            # 目录结构配置
├── intro.md            # 首页内容
├── notebooks/          # 存放 Jupyter notebook 文件
│   ├── example-notebook.ipynb
│   └── analysis.ipynb
├── requirements.txt    # Python 依赖
├── references.bib      # 参考文献
└── README.md          # 项目说明
```

## 自定义配置

- 编辑 `_config.yml` 来修改书籍标题、作者等基本信息
- 编辑 `_toc.yml` 来调整章节结构
- 在 `notebooks/` 目录添加你自己的 notebook 文件

## 部署

你可以将生成的网站部署到：
- GitHub Pages
- Netlify
- 或其他静态网站托管服务

更多信息请参考 [Jupyter Book 官方文档](https://jupyterbook.org/)。