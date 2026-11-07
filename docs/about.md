# 关于本项目

## 项目目标

实现从 Markdown 文档到公开网站的自动化发布。我只需要维护 `docs/` 目录里的 Markdown 文件，构建和部署交给 GitHub Actions 完成。

## 技术组成

| 工具            | 作用                     |
| --------------- | ------------------------ |
| Markdown        | 编写文档内容             |
| MkDocs Material | 将文档构建成静态网站     |
| GitHub Actions  | 自动执行安装、构建和部署 |
| GitHub Pages    | 托管并提供网站访问地址   |

## 我的理解

`docs/` 是源文件目录，`site/` 是 MkDocs 构建后生成的网站产物。`site/` 不应该手工修改，也不提交到 `main`，因为每次构建都会重新生成。真正需要版本管理的是 `docs/` 里的 Markdown 和 `mkdocs.yml` 配置。

## 页面导航

- [返回首页](index.md)
- [使用指南](guide.md)
- [API 参考](api.md)
