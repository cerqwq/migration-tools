# 🔄 Migration Tools

AI迁移工具，支持数据库迁移、代码迁移、架构迁移。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🗄️ 数据库迁移生成
- 📋 迁移计划制定
- 🔄 框架迁移代码
- 📦 数据迁移脚本
- ⚠️ 风险分析
- 🔧 Alembic迁移生成

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from migration_tools import create_tools

tools = create_tools()

# 数据库迁移
migration = tools.generate_db_migration(old_schema, new_schema)

# 迁移计划
plan = tools.plan_migration("单体架构", "微服务架构")

# 框架迁移
code = tools.generate_framework_migration("Flask", "FastAPI", flask_code)

# 数据迁移
script = tools.generate_data_migration("MySQL", "PostgreSQL", "用户数据")

# 风险分析
risk = tools.analyze_migration_risk(migration_plan)

# Alembic迁移
alembic = tools.generate_alembic_migration(model_changes)
```

## 📁 项目结构

```
migration-tools/
├── tools.py       # 迁移工具核心
└── README.md
```

## 📄 许可证

MIT License
