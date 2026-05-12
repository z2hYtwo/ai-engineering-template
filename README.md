# AI Engineering Template

这是一个集成了 AI 开发体系的项目模板。它包含了预定义的 `.agent` 技能（skills），旨在帮助开发者在不同的 AI 项目中快速复用开发规范和工具。

## 项目结构

- `.agent/`: AI 代理的核心配置和技能库
  - `skills/`: 包含 AI、后端、前端和 DevOps 等领域的开发技能
  - `agent.md`: AI 代理的主控配置
- `ai-service/`: AI 服务相关代码
- `backend/`: 后端服务代码
- `frontend/`: 前端应用代码
- `infra/`: 基础设施配置（如 Docker, K8s）
- `docs/`: 项目文档

## 如何自动使用这套体系

为了保证每次新项目 clone 后都能自动使用这套开发体系，建议采取以下方式：

### 1. 使用 GitHub Template Repository (推荐)
1. 将此仓库上传到 GitHub。
2. 在仓库设置（Settings）中勾选 **"Template repository"**。
3. 以后创建新项目时，直接点击 **"Use this template"**，新仓库将自动包含所有技能和结构。

### 2. 作为一个 Git Submodule
如果你想在现有项目中引用这套技能库，可以将其添加为子模块：
```bash
git submodule add <your-github-url> .agent
```

### 3. 克隆并初始化
```bash
git clone <your-github-url> my-new-project
cd my-new-project
# 开始你的 AI 开发之旅
```

## 核心技能分类

- **AI**: Embedding, Memory, Prompt, RAG, Workflow
- **Backend**: API, MySQL, Redis, Security, Spring Boot
- **Frontend**: Chat UI, React, Tailwind
- **DevOps**: Deploy, Docker

## 贡献

欢迎通过提交 PR 的方式增加更多的 AI 技能！
