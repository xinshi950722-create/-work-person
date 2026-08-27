# 📚 Obsidian 知识库 · 使用说明

这是一个用 [Obsidian](https://obsidian.md) 搭建的**个人第二大脑**。所有内容都是本地 Markdown 文件，数据完全归你所有，可随意备份、同步、迁移。

---

## 1. 怎么打开这个知识库

1. 启动 Obsidian（`D:\OBSDIAN\Obsidian\Obsidian.exe`）。
2. 左下角 **「打开其他仓库 / Open another vault」** → **「打开文件夹作为仓库 / Open folder as vault」**。
3. 选择 `D:\Obsidian Vault` 这个文件夹即可。
   - 首次打开会提示「安全模式」，点「关闭安全模式 / Turn off Safe Mode」以便使用插件（见第 4 节）。
4. 打开后建议把 [[🏠 首页 Home]] 设为启动页（设置 → 外观/文件 → 默认新标签页）。

> 小提示：打开后 Obsidian 会自动把它加入仓库列表，下次启动直接出现在仓库选择界面。

---

## 2. 文件夹结构（PARA 思路）

| 文件夹 | 用途 |
| --- | --- |
| `00 索引` | MOC 内容地图（首页、总索引、标签地图都在这里） |
| `10 Inbox` | 随手捕获，事后整理 |
| `20 项目` | 有截止日期、能完成的事 |
| `30 领域` | 长期负责的主题（健康、财务、工作…） |
| `40 资源` | 参考资料、素材、有趣的文章 |
| `50 归档` | 已完成 / 不再活跃的内容 |
| `60 每日笔记` | 日记与 daily log |
| `90 模板` | 笔记 / MOC / 每日笔记模板 |
| `附件` | 图片等附件自动存放处 |

---

## 3. 日常用法

- **新建笔记**：`Ctrl/Cmd + N`，写完用 `[[另一篇笔记]]` 建立双向链接。
- **插入模板**：`Ctrl/Cmd + P` → 搜「模板：插入模板 / Templates: Insert template」，选 `90 模板` 下的模板。
- **每日笔记**：`Ctrl/Cmd + P` → 搜「每日笔记 / Daily notes: Open today」，会用 `90 模板/每日笔记模板` 自动生成当天日记。
- **看知识网络**：左侧 **图谱（Graph）** 图标。
- **搜索**：左侧 **放大镜** 或 `Ctrl/Cmd + P`（命令面板）/ `Ctrl/Cmd + Shift + F`（全局搜索）。

### 推荐的笔记习惯
1. **先捕获，后整理**：灵感先丢 `10 Inbox`，有空再 `[[链接]]` 到对应主题并移动文件。
2. **用 MOC 做导航**：每个大主题建一张 MOC（`90 模板/MOC 模板`），把相关笔记列成链接，而不是深翻文件夹。
3. **打标签**：用 `#领域` 等标签做跨文件夹的横向归类。

---

## 4. 推荐安装的社区插件（开箱即用全家桶）

> 本环境无法联网下载插件二进制，所以下面这些需要你**在 Obsidian 内一键安装**（全程约 2 分钟，且只需要做一次）。

**安装步骤**：设置 → 第三方插件 → 关闭安全模式 → **浏览** → 搜索名字 → 安装 → 启用。

### ⭐ 强烈推荐（先装这 4 个）
| 插件 | 搜索名 | 作用 |
| --- | --- | --- |
| Dataview | `dataview` | 用查询把笔记当数据库（`00 索引` 里的自动列表依赖它） |
| Templater | `templater-obsidian` | 高级模板（支持 JS，比自带模板更强） |
| QuickAdd | `quickadd` | 一键快速捕获到 Inbox / 模板 |
| Calendar | `obsidian-calendar-plugin` | 左侧日历面板，配合每日笔记 |

### 🔧 也很实用（按需）
| 插件 | 搜索名 | 作用 |
| --- | --- | --- |
| Obsidian Git | `obsidian-git` | 用 Git 自动备份（需先安装 Git） |
| Outliner | `obsidian-outliner` | 更顺手的大纲（缩进/折叠）编辑 |
| CM Editor Syntax Highlight | `cm-editor-syntax-highlight-obsidian` | 代码块语法高亮 |
| Front Matter Tag Suggest | `obsidian-front-matter-tag-suggest` | 写 frontmatter 时标签自动补全 |
| Hover Editor | `obsidian-hover-editor` | 悬停预览笔记 |
| Spaced Repetition | `obsidian-spaced-repetition` | 间隔复习 / 卡片记忆 |

> 装好 **Dataview** 后，`🏷️ 标签地图 Tags` 和 `📥 收件箱 Inbox` 里的自动列表就会生效。

---

## 5. 备份与同步建议
- **最简单**：把整个 `D:\Obsidian Vault` 文件夹放进 OneDrive / 百度网盘 / 群晖等同步盘。
- **最专业**：安装 `Obsidian Git`，每次关闭或定时自动提交到私有 Git 仓库。
- 笔记是纯文本，永远不怕被锁死在某个软件里。

---

祝你用得顺手 🚀 有任何想调整的（配色、结构、插件），随时告诉我。
