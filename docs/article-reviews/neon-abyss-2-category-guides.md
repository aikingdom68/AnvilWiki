# Neon Abyss 2 三个栏目攻略编辑记录

编辑日期：2026-10-10（Asia/Shanghai）。本记录供编辑追溯，位于 `docs/`，不作为攻略正文渲染。

后续已经由 4 篇增补至 10 篇；本文保留前三个栏目专项写作时的记录，最新检查和排期见 [首版增补记录](./neon-abyss-2-first-release.md)。

## 交付范围

新增三篇英文攻略，沿用现有新手攻略的写法和站点栏目：

| 栏目 | 文件 | 内容 |
| --- | --- | --- |
| Agents | `src/content/wiki/en/agents/agent-guide.mdx` | 10 位角色的能力、解锁任务、累计与单局条件、配装和战前准备 |
| Hatchmon | `src/content/wiki/en/hatchmon/hatchmon-guide.mdx` | 孵化辅助道具、唤醒、4 种融合配方、Elise 与 Noxmare 搭配 |
| Bosses | `src/content/wiki/en/bosses/boss-guide.mdx` | 前期 Boss 名称与强化对应、Void 武器应对、准备清单和后期路线 |

新手攻略的三个分类链接改为直达这三篇文章。四篇 `getting-started.mdx` 是原始脚手架，确认其占位标题和正文后移出内容集合；备份位于下述证据目录的 `scaffolds-before/`。新手攻略修改内链前也已备份。每篇新增 1200 × 675 的站点配色文字封面，未改写原封面生成脚本。

公开正文和 FAQ 不介绍字幕、视频作者、资料提取或核验流程，不包含 `[待补充]`、未确定的机制、假设数值或虚构的第一人称实机经历。正文使用玩家能采取的行动说明建议，具体机制通过自然链接连接对应条目。

## 素材与去重

用户提供的本地字幕仅作为选题与观察线索，未直接复制成文章：

- `C:\Users\zxs\.codex\attachments\94a2bb43-981a-4640-89b8-8df06fdb93d0\已粘贴的文本.txt`：Sen Pineapple，早期尝试、移动、伴随物、毒与爆炸搭配。
- `C:\Users\zxs\.codex\attachments\059b9722-c68b-429b-a566-ad49399ad7d8\已粘贴的文本.txt`：Top Hat Toast，基础操作、资源、孵化和角色选择。
- `C:\Users\zxs\.codex\attachments\040dca61-750a-4273-9cdd-1788b523d5e7\已粘贴的文本.txt`：与上一份文件完全相同，不计为独立交叉证据。两份 SHA256 均为 `3BA1D501D7798EEE3CABB1E81FFE5B8B205DBB3E30CFFE80D4069209453C96F7`。
- `C:\Users\zxs\.codex\attachments\04270454-b73e-4fed-bac7-5da96c8b1e08\已粘贴的文本.txt`：新增 721 行素材；使用角色切换、联机沟通和资源准备方面的观察线索。未采用其不清楚的角色音译、商店与发行描述、随机能力说法和背景歌词。

## 版本与来源判断

直接读取的 CapyDB 页面声明从 PC 构建 `2026.10.8.72af32744d5` 提取，更新日期 2026-10-10。保留实时 HTML 与攻略正文快照，避免把搜索引擎旧缓存当作当前版本。CapyDB 是非官方游戏数据提取站；本次资料核对不是亲自进入游戏测试。

优先使用游戏文件条目、游戏 Codex 和开发商公告。检索攻略站及旧 Steam 社区攻略后，仅采用与当前数据一致的部分；未将不同版本的路线拼接成同一套规则。

| 内容 | 当前依据与处理 |
| --- | --- |
| 角色能力、角色任务数值及奖励领取 | [角色目录](https://capydb.com/neon-abyss-2/agents/)的 10 个详情页与[解锁说明](https://capydb.com/neon-abyss-2/guides/agents-unlocks/)；逐项读取 Nik、Elise、Xuan、Saya、James、Lúcia、R-7、Mira、Cassie、Tino |
| Tino 复制 Wonder Jar 的伤害代价 | 当前角色条目与[官方 Wonder Flow 公告](https://steamcommunity.com/games/2235200/announcements/detail/716781767925695624)一致 |
| R-7 护盾拾取增伤 | 当前能力条目：每次 0.5%，该效果上限 100%；StatBar 标示每次拾取增量 |
| 孵化辅助道具与资源 | [当前道具数据](https://capydb.com/neon-abyss-2/items/)：Godfather Disc、Replica Circlet、Dinosaur Fossil、Lightbulb、Eternal Stone |
| Replica Circlet 的数值 | 当前数据标注合格触发为 100%，冷却 3 秒；StatBar 仅表示该道具的合格进度触发，不表示基础孵化成功率 |
| 唤醒与融合 | [游戏 Codex](https://capydb.com/neon-abyss-2/guides/in-game-tips/)与[Hatchmon 数据](https://capydb.com/neon-abyss-2/hatchmon/)；触碰唤醒、Kiddy/Chirpie 支援、Cloudie/Chirpie/Boxie/Torchie 配方 |
| Noxmare 的伴随物互动与 9 层毒标记 | [当前武器数据](https://capydb.com/neon-abyss-2/weapons/#noxmare)，沿用新手攻略已核对的机制 |
| 早期 Boss 对应与第二阶段武器 | [早期 Boss 数据说明](https://capydb.com/neon-abyss-2/guides/early-bosses/)与 Codex 的 Void Power 条目；没有推测某个 Boss 的伤害、血量或招式循环 |
| 路线与解锁 | [当前路线数据说明](https://capydb.com/neon-abyss-2/guides/boss-route/)；仅写已有依据的 Trojan/Talos、Apollo/Eris/Hyperion、Hermes/Aphrodite/Theia 条件 |
| Dark Aphrodite | 当前路线与官方 Wonder Flow 公告一致：先打败普通 Aphrodite 解锁，在打败 Hermes 时至少持有 10 个 Hatchmon |
| 伴随物搭配与四人联机 | [开发商 Steam 页面](https://store.steampowered.com/app/2235200/Neon_Abyss_2/)与素材中的实际观察方向一致；没有推测人数与 Boss 血量的缩放关系 |

## 未采用的说法

- 旧攻略里特定道具触发 Dark Eris 的路线条件，与当前版本说明不一致。
- CapyDB 孵化攻略的“只靠进度道具孵化”与游戏数据/Codex 中的房间推进描述存在冲突。正文只写已明确的辅助道具、触发和成本，没有断言房间清理永远不影响孵化。
- 未写基础孵化概率、每个房间的概率、伙伴死亡次数、融合消耗后的路线计数推断。
- 未采用 50% 复活猜测、未经确认的女角色身份、Kiddy 不能融合等缺乏完整依据的结论。
- 未写 Boss 血量、固定弱点、精确阶段触发血量、攻击时序、全 Boss 通用招式或必胜阵容。
- 未将所有爆炸免疫归于 Tin Daddy；其说明仅覆盖自己造成的爆炸。

## 格式和验收

| 文章 | title 字符 | description 字符 | summary 词数 / 字符 | 问题式 H2 | 表格 | Callout / Accordion / StatBar | FAQ |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Agents | 62 | 123 | 54 / 323 | 5 | 3 | 2 / 2 / 1 | 6 |
| Hatchmon | 59 | 139 | 54 / 346 | 6 | 3 | 2 / 2 / 1 | 6 |
| Bosses | 59 | 134 | 53 / 362 | 6 | 5 | 2 / 2 / 1 | 6 |

各 H2 首段直接回答问题，50–55 词左右；正文没有 H1。现有标签为空数组，沿用 `tags: []`。三篇均有至少 3 条 Markdown 站内文章链接，使用尾斜杠。日期与 lastModified 为 2026-10-10，适用范围为 `1.0 (PC)`。

`draft: true` 与 `noindex: true` 保留，与既有新手攻略一致；开发模式可以预览，生产构建不包含这四篇草稿文章。本次没有转正、部署或生成站外发布内容。

证据目录：`H:\NeonAbyss2wiki\.local-cache\three-category-articles-20261010`。包含来源快照、脚手架备份、检查日志与页面预览快照。

最终验证结果：

- `pnpm check-content` 退出码 0：4 篇 MDX 全部通过，无内容警告。
- `pnpm build` 退出码 0：Astro 构建与 Pagefind/IndexNow 后续步骤通过。由于四篇文章仍是草稿，生产构建生成 14 个站点页面，不包含草稿文章路径。
- 四篇文章与四个栏目首页均 HTTP 200；栏目页不再有 `Getting Started with ...` 占位卡片，正文没有视频提取叙述或待补充字段。
- 三张新增封面均为 1200 × 675；浏览器检查所有已渲染图片正常加载。
- 使用真实 Chrome 中同源 375 像素宽 iframe 检查三篇文章（滚动条占用后内容视口 360 像素），文档无横向溢出，长表格使用现有横向滚动样式；浏览器结果保存在 `mobile-review.json`。
- `git diff --check` 无空白错误。未修改应用组件、样式或构建逻辑。
