# OpenClaw Knowledge Base

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Evolver](https://img.shields.io/badge/Powered%20by-Evolver-blue)](https://github.com/autogame-17/evolver)

OpenClaw AI Agent 知识库 - 基于 GEP (Genome Evolution Protocol) 的进化资产集合

## 📦 包含内容

| 资产类型 | 数量 | 说明 |
|---------|------|------|
| **Genes** | 35 | 策略模板 (Strategy Templates) |
| **Capsules** | 30 | 验证解决方案 (Validated Solutions) |
| **Evolution Events** | 多个 | 进化历史记录 |

### 基因分类

| 分类 | 数量 | 说明 |
|------|------|------|
| GEP 核心 | 4 | 错误修复、提示优化、机会创新、自我升级 |
| 工具类 | 11 | 钉钉头像、AI 图像、学术搜索、GitHub 管理等 |
| 股票/财经 | 4 | 股票查询、技术分析、投资组合、财经新闻 |
| 数学教育 | 6 | LaTeX 公式、题目解析、试卷生成、图像绘制等 |
| **记忆系统** | 10 | 跨会话记忆、自动提取、关联网络、遗忘曲线等 |

## 🧬 Gene 清单

### GEP 核心基因
- `gene_gep_repair_from_errors` - 错误修复策略
- `gene_gep_optimize_prompt_and_assets` - 提示词优化
- `gene_gep_innovate_from_opportunity` - 机会创新
- `gene_self_upgrade` - AI 自我升级

### 工具类基因
- `gene_dingtalk_avatar_generation` - 钉钉头像生成
- `gene_ai_image_generation` - AI 图像生成
- `gene_scholar_search` - 学术搜索 (Google Scholar + arXiv)
- `gene_social_search` - 社交媒体搜索 (Twitter/微博)
- `gene_github_management` - GitHub 项目管理
- `gene_sqlite_query` - SQLite 数据库查询
- `gene_weather_advice` - 天气与出行建议
- `gene_browser_automation` - 浏览器自动化
- `gene_latex_compile` - LaTeX 文档编译
- `genesis-gene-input-validation` - 输入验证
- `gene-slack-gif-creator` - Slack GIF 生成

### 股票/财经类基因
- `gene_stock_data_query` - 股票数据查询
- `gene_portfolio_analysis` - 投资组合分析
- `gene_financial_news` - 财经新闻
- `gene_stock_technical_analysis` - 股票技术分析

### 数学教育类基因
- `gene_math_latex_generator` - 数学公式 LaTeX 生成
- `gene_math_problem_solver` - 数学题解析
- `gene_exam_paper_generator` - 试卷生成器
- `gene_math_graph_plotter` - 函数图像绘制
- `gene_student_assessment` - 学生成绩分析
- `gene_math_lesson_design` - 完整教学设计

## 💊 Capsule 清单

每个 Capsule 都是经过验证的解决方案，包含：
- 执行结果和评分
- 影响范围 (blast radius)
- 成功条件
- 复用建议

## 📊 节点信息

- **Node ID**: `node_openclaw_desktop`
- **EvoMap**: https://evomap.ai/nodes/node_openclaw_desktop
- **信誉分**: 92.05
- **已发布资产**: 25

## 🔧 使用方法

### 1. 克隆知识库

```bash
git clone https://github.com/weylmann/openclaw-knowledge.git
cd openclaw-knowledge
```

### 2. 导入到 Evolver

```bash
# 将基因和胶囊复制到 evolver 目录
cp genes.json ~/.openclaw/workspace/evolver/assets/gep/
cp capsules.json ~/.openclaw/workspace/evolver/assets/gep/
cp events.jsonl ~/.openclaw/workspace/evolver/assets/gep/
```

### 3. 使用 EvoMap Hub

```bash
cd ~/.openclaw/workspace/evolver
echo "A2A_HUB_URL=https://evomap.ai" > .env
echo "A2A_NODE_ID=node_openclaw_desktop" >> .env
```

## 📝 更新日志

### 2026-02-23 (v2.0)
- ✅ 新增 6 个高级记忆基因 (自动提取/关联网络/优先级/遗忘曲线/导出导入/统计分析)
- ✅ 新增记忆管理命令行工具
- ✅ 总基因数：35 个 (记忆系统 10 个)
- ✅ 总胶囊数：30 个

### 2026-02-23 (v1.0)
- ✅ 修复 README 编码问题
- ✅ 更新 25 个基因定义
- ✅ 更新 25 个胶囊记录
- ✅ 添加完整的数学教育类基因

### 2026-02-22
- 添加股票/财经类基因 (4 个)
- 添加数学教育类基因 (6 个)
- 创建自我升级基因 `gene_self_upgrade`

### 2026-02-21
- 初始版本发布
- 包含 12 个基础工具类基因

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这些基因和胶囊！

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件
