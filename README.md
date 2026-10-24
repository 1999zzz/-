
> 使用该脚本有一定风险（如黑号、封号、权重降低等），维护者不承担任何责任。
# 整个活干（zdmqyl）
# 整个活干
由 **zzz** 维护的 Boss 直聘求职助手**衍生版**。
Boss 直聘求职助手衍生版。按条件筛岗位，先收藏待确认，勾选后再打招呼。
基于开源项目 [Ocyss/boss-helper](https://github.com/Ocyss/boss-helper)（MIT License）。上游版权仍归原作者所有；本仓库在其基础上增加了待确认流程、通勤与统计等改动。
- **筛选**：公司、岗位、内容、地址、活跃度；同一公司或同一 HR 去重
- **待确认**：搜索、排序；按通勤远近和岗位名分类后再投
- **通勤**：需自备高德 Key。不用 Key 时，关键词筛选和职业分类仍可用
## 本仓库相对上游的主要增强
基于 [Ocyss/boss-helper](https://github.com/Ocyss/boss-helper)（MIT）
- 筛选通过后先收藏进入**待确认**，确认后再打招呼
- 待确认支持展开详情、打开原帖、不投、排序、搜索、复制给外部 AI、导入 Boss 收藏
- 通勤筛选优先使用职位详情经纬度；起点可浏览器定位
- 统计口径改为扫描 / 筛掉 / 待确认 / 今日投递；显示主要筛掉原因
- 相同公司 / HR 按品牌 id、HR id 去重
建议与反馈：小红书「春去冬来」18110896472
## 和上游的差别
1. 安装依赖并构建：
| | [Ocyss/boss-helper](https://github.com/Ocyss/boss-helper) | 整个活干 |
| --- | --- | --- |
| 安装 | Chrome / Edge / Firefox 商店、GitHub Release | 本地构建后加载 |
| 投递 | 筛选通过即可自动打招呼 | 先收藏，进入待确认，勾选后再打招呼 |
| 待确认 | 无 | 搜索、排序、通勤档、岗位名分类、打开原帖、不投、导入 Boss 收藏 |
| AI | 筛选、招呼、模型配置 | 已去掉 |
| 反馈 | 飞书问卷、Telegram | 小红书 |
上游版权归原作者。本仓库在其基础上改了求职流程，不提供商店安装包。

## 上游
## 许可证
MIT。见 [LICENSE](./LICENSE)。
- 原项目：<https://github.com/Ocyss/boss-helper>
- 许可证：MIT（见 [LICENSE](./LICENSE)）
- 鸣谢原作者 Ocyss，以及原贡献者 yangfeng20、engvuchen
