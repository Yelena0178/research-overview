# 数学与物理研究项目目录说明 (`projects/`)

本目录用于集中收纳各个独立开展的未发表数学与物理研究项目（AI 辅助研究），每个项目存放在单独的子目录 `projects/<project-slug>/` 下。

## 推荐项目结构

导入本地项目时，**可保留原有文件夹与文件组织方式**；若希望统一规范，可参考以下可选子目录：

```text
projects/<project-slug>/
├── README.md        # 项目简介、研究问题、主要定理/结论与验证状态（可参考 _template/README.md）
├── paper/           # 论文手稿、LaTeX 源码、PDF 草稿（或 manuscript/）
├── derivations/     # 公式推导、证明过程与 AI 协作研究笔记（或 notes/）
├── code/            # 数值模拟或符号计算验证脚本，如 Python/SymPy、Mathematica、MATLAB（或 scripts/）
└── figures/         # 数值结果与可视化图表
```

## 导入本地项目注意事项

1. **清理嵌套 `.git` 目录**：如果待导入的本地项目本身已是一个 Git 仓库，请先删除其内部的 `.git/` 文件夹再放入 `projects/`，这样所有文件会由本总览仓库直接跟踪，而不会变成无法打开的空子模块（broken submodule）。
2. **避免超大文件与敏感信息**：GitHub 单文件大小限制为 100MB，提交前请确认未包含超大数值结果或压缩包，也不要提交 `.env` 或 API 密钥。
3. **同步更新总览表**：新增项目后，请在仓库根目录 [README.md](../README.md) 的总览表中补充对应条目。
