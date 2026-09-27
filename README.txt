# CineMind V2

一个无需构建、可直接通过 GitHub Pages 部署的个人电影审美地图 PWA。

## 文件
- index.html：主程序
- manifest.json：PWA 配置
- sw.js：离线缓存

## 部署
GitHub 仓库 → Add file → Upload files → 上传这三个文件 → Commit changes。
然后 Settings → Pages → Deploy from a branch → main / root → Save。

等待 GitHub Pages 部署完成后，用 Safari 打开生成的地址，再选择“添加到主屏幕”。

## 数据
评分目前保存在 iPhone 浏览器本机 localStorage。
可以在“已评分”页面导出 JSON。
后续可以继续加入云端同步、AI 推荐和更完整的电影数据库。
