# van-travel

土耳其跨年旅行规划页面，线上地址：https://travel.vancats.me

修改 `index.html` 后提交并推送到 `main`，Netlify 自动发布。

```sh
git add .
git commit -m "更新旅行页面"
git push origin main
```

目前是单文件 HTML。后续迁移 React + Vite 时，将 netlify.toml 的构建命令设为 `npm run build`，发布目录设为 `dist`。
