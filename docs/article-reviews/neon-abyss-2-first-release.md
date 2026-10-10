# Neon Abyss 2 首版 6 篇增补编辑记录

编辑日期：2026-10-10（Asia/Shanghai）。此文件只供编辑追溯，不作为攻略正文渲染。选题与逐篇检查安排见 [首版排期](../content-plan/first-release.md)。

## 写作范围与独立价值

由现有 4 篇总览增补至 10 篇。本次新增的武器、Faith、Elise、R-7、Noxmare 和 Dark Aphrodite 六篇各自解决一个明确问题，未重复总览首段或统一替换角色名称。每篇 6 个问题式 H2、40–60 词直答首段和 6 条 FAQ；表格列头按问题组织。复用现有空标签词汇 `tags: []`。

原始字幕的处理规则与去重记录沿用 [三个栏目编辑记录](./neon-abyss-2-category-guides.md)。字幕只提供问题线索，本批新增数字来自下列条目或明确的算术示例，未把口播当作唯一数值依据。公开页面不介绍视频提取和核验过程，也没有编造实机经验。

## 依据

2026-10-10 直接读取的 CapyDB 新页面声明 PC 构建 `2026.10.8.72af32744d5`。CapyDB 是非官方游戏数据提取站，本次工作是资料比对，并非运行游戏进行实机测试。既有同构建的角色、道具、Codex 和任务快照继续作为证据。

| 文章 | 采用的机制 | 对照来源 |
| --- | --- | --- |
| 武器升级 | 基础等级 1–8、升级所需 shards、提取返还、经验结余和资源词缀 | [当前武器升级数据](https://capydb.com/neon-abyss-2/guides/weapon-levels/)、[武器条目](https://capydb.com/neon-abyss-2/weapons/)、[官方 Weapon Reforge](https://steamcommunity.com/games/2235200/announcements/detail/527621618556469420) |
| 武器升级 | Philosopher's Stone 改变提取结果，Player Zero Ready 减少 20% 升级需求 | [当前道具](https://capydb.com/neon-abyss-2/items/)，没有推荐不存在于普通池的 Moon Magatama 作为通用掉落 |
| Faith | 8 个选项、Evolution/Task 解锁、100 meter、神殿访问和切换成本 | [当前 Faith 条目](https://capydb.com/neon-abyss-2/faiths/)、[Temple 规则](https://capydb.com/neon-abyss-2/guides/faith-temples/)、既有 Evolution/Codex 快照 |
| Elise | 8 次累计成功孵化任务、4 心/1 钥匙、Warming、Kiddy 的 10 秒唤醒冷却 | [Elise](https://capydb.com/neon-abyss-2/agents/elise/)、[Kiddy](https://capydb.com/neon-abyss-2/hatchmon/#kiddy)、任务与当前道具 |
| R-7 | 7 护盾同时持有、初始 4 护盾、Death's Door 心转护盾、每次拾取 0.5% 增伤/上限 100% | [R-7](https://capydb.com/neon-abyss-2/agents/r-7/)、Abnormal Chip、Iron Bastion；官方 Rule Changer 确认 R-7 为本作角色 |
| R-7 | 当前可识别的护盾道具与普通受伤成本 | [道具数据](https://capydb.com/neon-abyss-2/items/)、[health 规则](https://capydb.com/neon-abyss-2/guides/health/)；未把 Moldy Heart 写成安全的固定护盾 |
| Noxmare | 9 标记毒爆、伙伴命中加标记、按 Hatchmon 的词缀各稀有度值与 cap | [当前 Noxmare](https://capydb.com/neon-abyss-2/weapons/#noxmare)、Hatchmon/Kiddy/Chirpie 与 Shark Grenade/Snake Hairpin 等条目 |
| Dark Aphrodite | 普通 Aphrodite 前置、击败 Hermes 时至少 10 Hatchmon | [官方 Wonder Flow](https://steamcommunity.com/games/2235200/announcements/detail/716781767925695624)与[当前路线](https://capydb.com/neon-abyss-2/guides/boss-route/)一致 |

保留的算术示例均写明范围：1,430 是基础等级消耗的求和；42 + 20 = 62 是无修改的 solo 经验例子；R-7 10/20/50/100/200 拾取量对应增伤是 0.5% 乘法，并非保证可达；Noxmare 的 5/10 伙伴例子只计算 Normal 词缀，不替代最终伤害公式。

## 未写入的内容

- 未确定的 Dark Eris 旧 Acid Token 条件、Hermes 解锁细节和部分 DLC 阻挡条件。
- Faith 切换命中具体扣血数值、旧 Faith 进度是否保留、部分 Umbrism 兑换比率和 Dualism 神殿内部挑战细则。
- 基础孵化成功率及“清理房间永远不孵化”的排他性判断；此前已发现说明冲突。
- R-7 技术导弹数量阈值、不同护盾包是否按多次拾取结算、未确认的实际触发计算。
- Boss 血量、固定弱点、攻击时序或每一阶段的精确参数。
- 并无核实码清单或可复现排序标准的 Codes/Tier List 页面。

Snake Hairpin 与 Lightbulb 搭配注明有资源条件和触发冷却，没有写成无限、零成本或必胜循环。Noxmare 的毒爆阈值和资源词缀分别解释，没有把任何 Poison 道具都写成同一种标记效果。

## 格式

| 新文章 | title 字符 | description 字符 | summary 词数 / 字符 | H2 / FAQ | 表格 |
| --- | --- | --- | --- | --- | --- |
| weapon-upgrades | 66 | 133 | 51 / 327 | 6 / 6 | 5 |
| faith-and-temples | 57 | 125 | 52 / 302 | 6 / 6 | 5 |
| elise-guide | 61 | 137 | 53 / 350 | 6 / 6 | 4 |
| r-7-guide | 59 | 138 | 56 / 360 | 6 / 6 | 5 |
| noxmare-poison-build | 61 | 140 | 53 / 340 | 6 / 6 | 5 |
| dark-aphrodite-route | 60 | 138 | 51 / 328 | 6 / 6 | 5 |

使用 Callout 与 Accordion，并在有合适数值时使用 StatBar：20% 升级需求降低、100% 填满的 Faith meter（注明 100 Faith）、R-7 每次拾取 0.5%、Normal Noxmare 每伙伴 3%。没有把秒数或伙伴数量硬写成掉落概率。

新增 6 张 1200 × 675 品牌文字封面；Dark Aphrodite 加 2 张原创路线图并登记 gallery、caption 与 alt。图示说明路线与准备，未伪造实机截图或 Boss 招式。

## 验证证据

证据目录：`H:\NeonAbyss2wiki\.local-cache\launch-content-20261010`。

- `scaffold-dry-run.log` 与 `scaffold-created.log`：CSV 计划创建 6 篇、跳过 0 篇，随后真实创建并逐篇填充。
- `check-content.log`：10 篇通过，退出码 0，无内容警告。
- `build.log`：Astro、Pagefind、IndexNow 步骤通过，退出码 0。
- `check-links.log`：生产构建 14 页中 273 条链接均可解析，退出码 0。
- `content-graph.json`：10 篇开发文章之间的 48 条 Markdown 内链均指向真实页面；额外检查已缓存数据页的引用锚点，修正 Philosopher's Stone 锚点为 `philosophers-stone`。
- `page-checks.json` 与逐页 HTML：10 页 HTTP 200，唯一 H1，正文无过程叙述或占位字段；草稿正文通过真实开发请求编译，不能只用排除草稿的生产 build 作为正文验证。
- `browser-review.json`：真实 Chrome 中 375 像素 iframe（内容视口 360），6 篇新增页面文档无横向溢出；每张表格横向可滚动，正常图片全部加载。

所有 10 篇保留 `draft: true` 与 `noindex: true`。构建中的 14 个页面是站点结构页面，草稿不进入生产输出、RSS 或 sitemap。尚未记录人工实机核实、用户逐篇确认、转正或生产部署。
