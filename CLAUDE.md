# Travel Project

这是一个静态旅行攻略网站，托管在 GitHub Pages（coffeedomilk.github.io/travel/）。

## 项目结构

```
travel/
├── qhd_travel.html   # 清明节秦皇岛自驾游攻略（主文件）
└── README.md
```

## 当前行程概览

**清明节 北京→秦皇岛 3天2晚自驾游（2026年4月4日–6日）**

- **Day 1**（4/4）：北京出发 → 天下第一关 → 老龙头景区 → 北戴河入住丽枫酒店
- **Day 2**（4/5）：鸽子窝日出（可选）→ 北戴河湿地公园 → 午餐 → 阿那亚全天游 → 19:30 活动
- **Day 3**（4/6）：板厂峪长城 → 农家午餐 → 返京

## 已确认事项

- **住宿**：丽枫酒店，北戴河区安一路 8 号，2晚已预订
- **阿那亚**：4月5日 19:30 活动票已购，可提前 8 小时（11:30）入场；停车在民宿访客停车场

## 部署

直接 push 到 `main` 分支，GitHub Pages 自动发布，几分钟内生效。

```bash
git add <file>
git commit -m "描述改动"
git push
```

## HTML 文件结构

`qhd_travel.html` 是自包含的单页文件，CSS 内嵌在 `<style>` 标签中，无外部依赖（除 Google Fonts）。

主要 CSS 类：
- `.hero` — 顶部封面区
- `.overview-grid` / `.overview-card` — 行前须知卡片
- `.timetable` / `.tt-col` — 三天时间总览表
- `.day-block` / `.timeline` / `.tl-item` — 每日详细行程时间轴
- `.callout` — 提示/注意事项框
- `.tips-section` / `.checklist` — 实用备忘与出发清单
