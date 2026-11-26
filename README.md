# 研究成果总览 (Research Overview)

本仓库用于统一整理、归档和展示已有的科研成果与学术发表记录，方便后续补充论文资料、维护引用信息以及与团队成员共享。

## 论文与发表总览 (Publications Overview)

| 编号 | 年份 | 标题 | 作者 | 期刊 / 会议 | 状态 | 资料与链接 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |

> [!NOTE]
> 表格条目将在上传具体论文资料后陆续补充完善。

## 目录结构

- `papers/`：存放各篇论文的正文 PDF、稿件、补充材料与单篇笔记（建议按 `YYYY-关键词/` 子目录存放）
- `docs/publications.bib`：汇总所有论文的 BibTeX 引用条目

## 更新方式

1. 在 `papers/` 下新建以 `YYYY-关键词/` 命名的子目录，放入论文 PDF、补充材料及 `notes.md`。
2. 在本文件上方的总览表格中新增一行记录，并附上对应目录或外部链接。
3. 将对应论文的 BibTeX 引用条目追加到 `docs/publications.bib`。
4. 提交并推送到 GitHub：
   ```bash
   git add .
   git commit -m "Add paper: <paper-short-name>"
   git push
   ```
