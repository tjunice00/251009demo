# 251009demo

孙岱丰个人简介网页的静态站点代码与设计资料，包含最终上线版本以及对应的设计规范。

## 目录结构

- `index.html`：单页简历的 HTML 结构。
- `styles.css`：页面的核心样式。
- `assets/`：图片等静态资源。
- `design/`：设计说明、组件规范等参考文档。
- `README.md`：项目使用说明（当前文件）。

## 本地查看

```bash
git clone https://github.com/tjunice00/251009demo.git
cd 251009demo
open index.html           # macOS
# 或者
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000
```

## 部署到 GitHub Pages

仓库已在 `Settings → Pages` 中配置使用 `main` 分支根目录。每次将最新代码推送到 `main` 分支后，GitHub Pages 会自动构建，你可以在以下地址访问页面：

<https://tjunice00.github.io/251009demo/>

若需要自定义域名，请在同一设置页添加域名并在 DNS 中配置 `CNAME` 记录指向该地址。
