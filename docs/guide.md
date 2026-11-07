# 使用指南

1. 修改 `docs` 目录中的 Markdown 文件。
2. 在本地预览并检查页面及链接。
3. 提交修改并推送到 `main` 分支。
4. 在 Actions 页面查看构建与部署状态。
5. 打开网站检查内容是否更新。

## 常用命令

- `python -m mkdocs serve`：本地预览。
- `python -m mkdocs build --strict`：构建网站并严格检查警告。

## 本地预览体会

在本地执行 `python -m mkdocs serve` 后，浏览器打开 `http://127.0.0.1:8000/` 就能看到网站。修改 Markdown 并保存后，页面会自动刷新，适合检查导航、表格和代码块是否正常。检查完成后按 `Ctrl+C` 停止预览。

## 自动部署流程

| 步骤     | 发生位置       | 说明                                   |
| -------- | -------------- | -------------------------------------- |
| 推送文档 | 本地 Git       | 把修改推送到 `main`                    |
| 构建     | GitHub Actions | 安装依赖并执行 `mkdocs build --strict` |
| 部署     | GitHub Actions | 上传 `site/` 并发布到 GitHub Pages     |
| 访问     | 浏览器         | 打开 Pages 地址查看更新                |

## 相关页面

- [返回首页](index.md)
- [关于本项目](about.md)
- [API 参考](api.md)
