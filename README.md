# 星露谷洒水器规划器 (Stardew Valley Sprinkler Planner)

一个基于 Canvas 的网页工具，用于规划星露谷物语中农场的洒水器和稻草人布局。

## 在线体验

👉 **[https://hathwallace.github.io/farm-sprinkler-plan/](https://hathwallace.github.io/farm-sprinkler-plan/)**

## 功能

- 自定义网格尺寸（1×1 ~ 64×64）
- 放置稻草人（保护半径 8 格，欧氏距离）
- 放置洒水器：
  - 💧 普通：十字 4 格
  - ⭐ 优质：周围 8 格（3×3 环）
  - ✨ 铱金：24 格（5×5 环）
- 实时统计覆盖格数（去重）
- 鼠标滚轮 / 移动端双指 pinch 缩放
- 拖动平移视图
- 一键导出 PNG 截图
- 纯前端实现，无需后端

## 使用

直接在浏览器打开 `index.html` 即可。也可以用任意静态服务器：

```bash
python -m http.server 8080
```

## GitHub Pages 部署

1. 将仓库推送到 GitHub
2. 在 Settings → Pages 中选择 `main` 分支根目录
3. 访问 `https://<用户名>.github.io/<仓库名>/`
