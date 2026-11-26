# AI 研究项目总览 (AI Research Projects Overview)

本仓库用于统一收纳、管理和追踪多个尚未发表的 AI 研究项目，涵盖实验代码、配置文件、论文草稿、研究笔记与阶段性结果汇总。

## 研究项目总览 (Projects Overview)

| 编号 | 项目名称 | 研究方向 | 当前阶段 | 核心简介 | 目录 |
| :--- | :--- | :--- | :--- | :--- | :--- |

> [!NOTE]
> 常见阶段标识：`构思中` / `实验中` / `撰写中` / `投稿准备中` / `归档`。导入本地项目后将陆续补充至上表。

## 目录结构

```text
research-overview/
├── README.md                  # 仓库总览与项目索引表
├── .gitignore                 # 排除权重、数据集、缓存、虚拟环境与密钥文件
└── projects/
    ├── README.md              # 多项目收纳规范与导入说明
    ├── _template/
    │   └── README.md          # 单个 AI 研究项目说明模板
    └── <project-slug>/        # 各独立 AI 研究项目目录
```

## 同步与大文件说明

- **自动忽略内容**：`.gitignore` 已默认排除模型权重与检查点（`.pt`、`.pth`、`.ckpt`、`.safetensors`、`.onnx`、`.bin` 等）、原始/处理后数据集、训练日志与缓存（`wandb/`、`mlruns/`、`runs/`、`.cache/` 等）、Python 虚拟环境以及 `.env` 等密钥配置文件。
- **公开仓库安全提示**：由于本仓库为 **Public（公开）**，请勿提交包含 API Key、私钥、服务器密码或受限隐私数据的文件。
