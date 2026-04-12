# Corpus Layer

这层不是宣传文案，也不是 research note。
这层只负责两件事：收集原始公开语料，和把原始语料标准化。

## 目录结构

- `source-index.csv`
- `youtube/`
- `newsletters/`
- `podcasts/`
- `courses/`
- `social/x/`
- `social/linkedin/`
- `social/instagram/`
- `normalized/`

## 使用规则

1. 每条来源都要先登记到 `source-index.csv`。
2. 每条来源都必须保留原始链接、发布时间、平台、标题。
3. 原始层尽量少解释，多保留原文。
4. 标准化层只做清洗、拆段、标签化，不提前下结论。
5. research 结论只能建立在 corpus 里已经存在的材料之上。

## 命名建议

- 长文：`YYYY-MM-DD-slug.md`
- 视频：`YYYY-MM-DD-video-title.md`
- 播客：`YYYY-MM-DD-episode-title.md`
- 社媒：`YYYY-MM-DD-platform-slug.md`
- 标准化文本：沿用原始 `id`

## 推荐工作流

1. 把来源登记进 `source-index.csv`
2. 按平台用模板建原始文件
3. 把高价值内容清洗到 `normalized/`
4. 在 `references/research/07-13` 里做二次蒸馏
5. 最后再更新 `SKILL.md`、`README.md` 和元数据
