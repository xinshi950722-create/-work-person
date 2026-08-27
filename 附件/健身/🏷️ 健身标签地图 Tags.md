---
tags: [moc, fitness]
created: 2026-07-13
---

# 🏷️ 健身标签地图 Tags

> [!info] 需要 Dataview 插件
> 下面列表依赖 Dataview，未装时显示代码块原文。

```dataview
TABLE length(rows) AS 笔记数
FROM "健身"
FLATTEN file.tags AS t
WHERE t != "#moc" AND t != "#fitness" AND t != "#daily"
GROUP BY t
SORT 笔记数 DESC
```

## 常用标签
- `#fitness` 总标签
- `#动作` `#计划` `#训练日志` `#食谱` `#营养`
- 部位 `#胸` `#背` `#腿` `#肩` `#臂` `#核心` `#有氧`
- 目标 `#增肌` `#减脂` `#力量` `#耐力`
