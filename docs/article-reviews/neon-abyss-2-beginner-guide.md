# Neon Abyss 2 新手攻略编辑记录

最近修订：2026-10-10（Asia/Shanghai）。文章：`src/content/wiki/en/guides/beginner-guide.mdx`。

后续首版增补时已增加武器与 Faith 专项入口；当前全站共 10 篇草稿，最新验证与排期见 [首版增补记录](./neon-abyss-2-first-release.md)。

## 本次修改

按用户要求整篇重写为面向玩家的攻略。正文及 FAQ 不再出现视频作者、字幕、录制过程、资料核验过程、待补充字段和编辑用的免责声明；也没有添加“我实测过”“我的通关经历”等未经发生的第一人称叙述。本记录位于 `docs/`，不作为攻略正文渲染。

文章围绕开局、操作、资源、武器选择、飞行/毒/爆炸搭配、Hatchmon、Boss 准备和复盘展开。操作建议与具体道具机制分开写，未将一次通关结果描述成固定奖励或必胜配置。

## 采用的具体机制

2026-10-10 重新直接读取以下资料，并保存实时 HTML。CapyDB 声明数据提取自 PC 构建 `2026.10.8.72af32744d5`，本次导入日期为 2026-10-10；它是非官方数据提取站，资料核对不等于亲自进游戏测试。

| 正文内容 | 依据 |
| --- | --- |
| Diagnosis Certificate 提供飞行与 10% 暴击率提升 | [道具条目](https://capydb.com/neon-abyss-2/items/#diagnosis-certificate)；StatBar 使用该已查到的 10% 数值 |
| Noxmare 命中叠加毒标记，9 层触发毒爆，Hatchmon 命中也可叠加 | [武器条目](https://capydb.com/neon-abyss-2/weapons/#noxmare) |
| Popcorn 使武器弹体产生爆炸 | [道具条目](https://capydb.com/neon-abyss-2/items/#popcorn)；没有仅凭字幕推断它的自伤规则 |
| Tin Daddy 免疫自己造成的爆炸 | [道具条目](https://capydb.com/neon-abyss-2/items/#tin-daddy)；未写成所有爆炸或敌人攻击都免疫 |
| 武器有不同词缀与升级选项 | [官方 Weapon Reforge 公告](https://steamcommunity.com/games/2235200/announcements/detail/527621618556469420) |
| Hatchmon 与道具、武器可形成搭配 | [开发商 Steam 介绍](https://store.steampowered.com/app/2235200/Neon_Abyss_2/) |

[数据来源说明](https://capydb.com/neon-abyss-2/sources/)与实时页面证据：`H:\NeonAbyss2wiki\.local-cache\beginner-guide-rewrite-20261010`。

## 已从文章删除的内容

- 50% 复活概率及 Schrodinger Clip 身份猜测；移除原来的 50% StatBar。
- 孵化概率、进度阈值和没有完整依据的进化规则。
- 不确定的机关解法、商人贷款与贿赂条款。
- 所有 `[待补充]`、原视频链接/版本缺失说明和来源确认清单。
- 拿作者的控制故障当作游戏问题、把某次奖励或每级伤害提升当成通用机制的叙述。

前一版文章和核验记录保存在上述证据目录，供编辑追溯，不进入网站内容。

## 格式与验证

- 标题 60 字符、description 135 字符、summary 53 词 / 351 字符。
- 8 个问题式 H2，首段均为 48–53 词；正文不含 H1。
- 5 张表格、3 个 Callout、3 个 Accordion、1 个 10% StatBar、6 条 FAQ。
- 5 条站内链接直达 Agents、Hatchmon、Bosses、武器升级和 Faith 专项，均带尾斜杠；站点现有标签均为空数组，继续使用 `tags: []`。
- `pnpm check-content` 退出码 0；本篇及三个新增攻略均无内容警告。原有 4 篇栏目脚手架已移出内容集合并备份。
- `pnpm build` 退出码 0；没有构建错误。
- 开发预览 HTTP 200，新正文已渲染；旧版视频叙述、待补充内容和复活概率猜测均未出现。
- 初次重写的检查日志保留在原证据目录；新增三篇攻略后的最终检查日志和本篇预览快照位于 `H:\NeonAbyss2wiki\.local-cache\three-category-articles-20261010`。详情见 [三个栏目攻略编辑记录](./neon-abyss-2-category-guides.md)。

`lastModified` 更新为 2026-10-10，适用范围标注为 `1.0 (PC)`。原有 `draft: true`、`noindex: true` 保留，正文没有草稿提示框。尚未执行转正或部署操作。
