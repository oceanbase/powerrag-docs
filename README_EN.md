# PowerRAG Community Edition Documentation

Welcome to the PowerRAG Community Edition documentation repository. This repository maintains and publishes product documentation related to PowerRAG Community Edition, including documentation for PowerRAG Community Edition and its derivative project Langfuse.

## Repository Overview

This repository contains documentation for two main components:

### 1. PowerRAG Community Edition

PowerRAG Community Edition is an open-source project based on [RAGFlow](https://github.com/infiniflow/ragflow), licensed under the **Apache 2.0** license. Built on top of RAGFlow, it extends capabilities including document services, structured information extraction, multimodal search, and evaluation with feedback, providing comprehensive data services for Large Language Model (LLM) applications.

The PowerRAG Community Edition documentation focuses exclusively on the new and independent capabilities introduced by PowerRAG Community Edition. For features and usage shared with RAGFlow, please refer to the [RAGFlow official documentation](https://ragflow.io/docs/v0.22.0/).

### 2. Langfuse

Langfuse is an independent sub-project within the PowerRAG Community Edition ecosystem, implementing the evaluation and feedback module. It has its own [GitHub repository](https://github.com/oceanbase/langfuse), but documentation is consolidated in this repository for centralized developer reference.

Langfuse provides model observability, prompt management, and evaluation capabilities, helping users build monitorable and tunable LLM application systems.

## Documentation Structure

```plain
en-US/
├── 00.PowerRAG Community Edition User Guide/
│   ├── 00.PowerRAG community edition overview.md
│   ├── 10.New chunking methods.md
│   └── 20.Structured information extraction.md
└── 10.Langfuse User Guide/
    ├── 00.Langfuse overview.md
    ├── 10.Deployment and Initialization/
    │   ├── 00.Overview.md
    │   ├── 10.Deploy Langfuse service.md
    │   ├── 20.Access Langfuse and create API key.md
    │   └── 30.Deploy Bridge service.md
    ├── 20.Application Observability/
    │   ├── 00.Overview.md
    │   ├── 10.Quick start.md
    │   ├── 20.Observability data model.md
    │   └── 30.Core Features/
    │       ├── 00.Sessions.md
    │       ├── 10.User tracking.md
    │       ├── 20.Environments.md
    │       ├── 30.Tags.md
    │       ├── 40.Metadata.md
    │       └── 50.Trace ID and distributed tracing.md
    ├── 30.Prompt Management/
    │   ├── 00.Overview.md
    │   ├── 10.Quick start.md
    │   ├── 20.Prompt data model.md
    │   └── 30.Core features/
    │       ├── 00.Version control.md
    │       ├── 10.Composability.md
    │       ├── 20.Message placeholders.md
    │       └── 30.Playground.md
    └── 40.Application Evaluation/
        ├── 00.Overview.md
        ├── 10.Evaluation Methods/
        │   ├── 00.LLM-as-a-Judge.md
        │   └── 10.Scoring data model.md
        ├── 20.Benchmarking/
        │   ├── 00.Benchmarking overview.md
        │   ├── 10.Dataset.md
        │   ├── 20.Benchmarking via SDK.md
        │   ├── 30.Benchmarking via console.md
        │   └── 40.Benchmarking data model.md
        └── 30.Configure LLM connection.md
```


## How to Use the Documentation

You can browse the documentation directly on GitHub, or clone this repository to your local machine:

```bash
git clone https://github.com/<your-org>/powerrag-docs.git
cd powerrag-docs
```

## Contributing

We welcome contributions through Pull Requests or Issues for documentation updates, corrections, or new sections.

* For PowerRAG Community Edition related content, please update files under `00.PowerRAG Community Edition User Guide/（00.PowerRAG 社区版用户指南）`
* For Langfuse related content, please update files under `10.Langfuse User Guide/（10.Langfuse 用户指南）`

## License

The documentation content in this repository is licensed under the **Apache License 2.0**.

