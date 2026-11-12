# van-travel

土耳其跨年旅行规划页面，线上地址：https://travel.vancats.me

修改 `index.html` 后提交并推送到 `main`，Netlify 自动发布。

```sh
git add .
git commit -m "更新旅行页面"
git push origin main
```

目前是单文件 HTML。后续迁移 React + Vite 时，将 netlify.toml 的构建命令设为 `npm run build`，发布目录设为 `dist`。

## 自动部署

- GitHub 仓库：https://github.com/vancats/van-travel
- 生产分支：`main`
- Netlify 站点：`chic-paprenjak-538478`
- 当前无需构建命令，发布目录为 `.`（由 `netlify.toml` 管理）。
- 推送到 `main` 后可在 Netlify 的 Deploys 页面查看进度；发布成功后域名自动更新。
- 该仓库已连接现有旅行站点，不要继续拖拽上传旧 HTML，以免覆盖 Git 版本。
