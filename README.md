# PowerRAG 社区版文档仓库
欢迎访问 PowerRAG 社区版文档仓库。本仓库用于维护和发布与 PowerRAG 社区版相关的产品文档，包括** **PowerRAG 社区版与其衍生项目 Langfuse 的文档内容。

## 仓库说明

本仓库包含以下两部分文档：

### 1. PowerRAG 社区版
PowerRAG 社区版是基于 [RAGFlow](https://github.com/infiniflow/ragflow) 二次开发的开源项目，采用 **Apache 2.0** 协议。该项目在 RAGFlow 的基础上，扩展了文档服务、结构化信息提取、多模检索及效果评估与反馈等功能，为大模型（LLM）应用提供一体化的数据服务能力。  

PowerRAG 社区版的文档涵盖产品介绍、部署指南、功能使用说明等内容。

### 2. Langfuse
Langfuse 是 PowerRAG 社区版生态下的独立子项目，用于实现效果评估与反馈模块。该项目拥有独立的 [GitHub 仓库](https://github.com/oceanbase/langfuse)，但文档统一收录在本仓库中，以便开发者集中查阅。  

Langfuse 提供模型可观测性、提示词管理与评估能力，帮助用户构建可监控、可调优的 LLM 应用体系。

## 文档结构

```plain
docs/
├── powerrag/         # PowerRAG 社区版文档
│   ├── overview.md
│   ├── deployment.md
│   ├── ...
│   └── ...
└── langfuse/         # Langfuse 项目文档
    ├── overview.md
    ├── usage.md
    └── api/
```

## 如何使用文档

您可以直接在 GitHub 上浏览文档，或将本仓库克隆到本地后查看：

```bash
git clone https://github.com/<your-org>/powerrag-docs.git
cd powerrag-docs/docs
```

## 贡献指南

欢迎通过 Pull Request 或 Issue 提交文档修改、勘误或新增章节。

* 对于 PowerRAG 相关内容，请在 `docs/powerrag/` 下更新
* 对于 Langfuse 相关内容，请在 `docs/langfuse/` 下更新

## 开源许可

本仓库的文档内容遵循 **Apache License 2.0** 协议。
