# 豆绘 · Bead Studio

纯静态的图片转拼豆图纸工具。图片在浏览器本地处理，不会上传服务器。

## 本地运行

```bash
npm run dev
```

打开 http://localhost:4173。也可以直接双击 `index.html` 使用。

## GitHub Pages

仓库内的 `.github/workflows/deploy.yml` 会在推送到 `main` 或 `master` 后自动发布到 GitHub Pages。首次使用时，在仓库 Settings → Pages → Source 中选择 **GitHub Actions**。

## 功能

- 上传 PNG、JPG、WebP 或使用内置示例
- 画布尺寸、拼豆规格、颜色数量和配色方式配置
- 去白底、网格、色号、豆粒视图
- 画笔、橡皮擦、撤销与重做
- 导出 PNG 图纸和 CSV 用量清单
