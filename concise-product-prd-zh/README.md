# concise-product-prd-zh

用于编写、重构、评审和精简中文产品需求文档的 Codex Skill。输出固定包含简介、产品概述、产品需求详解和数据兼容问题，并始终从产品角度描述用户行为和产品结果。

## 安装

将整个目录复制或克隆到以下任一位置：

- Codex：`~/.codex/skills/concise-product-prd-zh`
- 跨运行时目录：`~/.agents/skills/concise-product-prd-zh`

GitHub 仓库可以直接以本目录作为仓库根目录，也可以将本目录放入统一的 `skills/` 目录。

## 使用

显式调用：

```text
$concise-product-prd-zh 根据需求材料和原型编写PRD。
```

Skill 默认支持自动发现，也可在编写、精简或评审中文PRD时由运行时自动选择。

## 文件

- `SKILL.md`：触发条件、核心原则和生成流程。
- `references/prd-writing-guide.md`：四大模块写法、职责边界和审查规则。
- `agents/openai.yaml`：Skill 的界面元数据。
- `tests/behavior-scenarios.md`：提交前的人工行为验证场景。
