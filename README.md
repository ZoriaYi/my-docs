# 我的技术文档

本项目是基于 MkDocs 和 Material 主题构建的静态文档网站。网站内容通过 Markdown 编写，并使用 GitHub Actions 自动构建和部署到 GitHub Pages。

## 网站链接

[访问我的文档网站](https://ZoriaYi.github.io/my-docs/)

## 个人实验报告

[查看个人实验报告](report/README.md)

## 本地预览命令

如需在本地运行并预览此项目，请按照以下步骤操作：

1. 创建并激活 Python 虚拟环境（以 Windows PowerShell 为例）：
   `python -m venv .venv`
   `.\.venv\Scripts\Activate.ps1`

2. 安装项目依赖：
   `python -m pip install -r requirements.txt`

3. 启动本地预览服务器：
   `python -m mkdocs serve`

4. 在浏览器中打开 `http://127.0.0.1:8000/` 即可查看。
