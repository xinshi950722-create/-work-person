---
tags: [moc]
created: 2026-07-13
---

# 🏷️ 标签地图 Tags

> [!info] 需要 Dataview 插件
> 下面的自动列表依赖 Dataview。装好后会列出所有标签及数量；未装则显示代码块原文。

```dataview
TABLE length(rows) AS 笔记数
FROM "" 
FLATTEN file.tags AS t
WHERE t != "#moc" AND t != "#daily"
GROUP BY t
SORT 笔记数 DESC
```

## 常用标签约定
- `#moc` —— 内容地图（索引页）
- `#daily` —— 每日笔记
- `#inbox` —— 待整理
- `#project` / `#area` / `#resource` —— PARA 分类
- 领域标签如 `#健康` `#财务` `#阅读` 自由添加
