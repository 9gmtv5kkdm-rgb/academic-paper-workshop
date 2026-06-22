---
name: academic-paper-workshop
slug: academic-paper-workshop
version: 1.3.0
displayName: 学术论文工坊
summary: 论文全生命周期12件套——查重预检/文献挖掘/写作语料/配图图表/审查诊断/排版/版本管理/文献规范/投稿辅助/摘要优化
description: |
  Academic Paper Workshop v1.3 - 12-skill suite for the full academic paper lifecycle.
  Now complete: plagiarism precheck (6-tier rewriting pyramid + CNKI/Turnitin rules),
  literature mining (reading notes + matrix + gap + PRISMA + evidence hierarchy),
  abstract optimizer (CN-EN symmetry + 4 discipline templates + abstract-body mapping),
  writing bank (chapter templates + phrase bank + 100+ transitions),
  figure generation (Graphviz DOT architecture diagrams),
  chart generation (10 statistical types + significance + error bars),
  review methodology (29 methods + P0-P3 + desensitization),
  DOCX toolkit (python-docx + XML + journal presets),
  version manager (scoring + decision audit),
  reference formatter (GB/T 7714 + APA + BibTeX + DOI),
  and submission helper (Cover Letter + Rebuttal + 45-item checklist).
  
  学术论文工坊v1.3——论文全生命周期12件套（最终完整版）。
  新增：查重预检与降重(6级降重金字塔+CNKI/Turnitin规则+AI查重双策略)、
  摘要优化与审查(中英对称30项清单+4学科模板+摘要正文映射验证)。
  完整12件：文献挖掘→查重预检→写作语料→架构配图→数据图表→审查诊断→
  DOCX排版→版本管理→文献规范→摘要优化→投稿辅助→套件入口。
  触发词：论文工坊、论文写作、学术写作套件、academic workshop、paper suite、写论文。
---

# 学术论文工坊（Academic Paper Workshop）

论文全生命周期技能套件。从文献调研到投稿发表，11个专业子技能 + 1个套件入口 = 12件套（最终完整版）。

## 套件架构

```
学术论文工坊 (academic-paper-workshop)
│
├── 📖 输入层：文献调研
│   └── literature-mining            阅读笔记3套 · 文献矩阵 · Gap识别 · PRISMA · 证据分级
│
├── 🛡️ 质量层：查重+摘要
│   ├── plagiarism-precheck          6级降重金字塔 · CNKI/Turnitin · AI查重双策略
│   └── abstract-optimizer           中英对称30项 · 4学科模板 · 摘要正文映射验证
│
├── ✍️ 创作层：写+画
│   ├── academic-writing-bank        8章模板 · 6类短语库 · 100+过渡词 · 避坑指南
│   ├── academic-figure-gen          Graphviz DOT · 5类架构图模板 · 3套配色
│   └── academic-chart-gen           10类统计图 · 显著性标注 · 误差线 · 期刊预设
│
├── 🔍 审查层
│   ├── paper-review-methodology     29类审查方法 · P0-P3分级 · 脱敏筛查
│   └── academic-reference-formatter  GB/T 7714 · APA · BibTeX · DOI
│
├── 📄 排版层
│   └── academic-docx-toolkit        python-docx · 表格/图片/段落 · XML操作 · 4刊模板
│
├── 📊 管理层
│   └── paper-version-manager        血缘树 · 四维评分 · 决策审计 · 安全底本
│
└── 📤 输出层：投稿发表
    └── submission-helper            Cover Letter · Rebuttal 6型 · 45项清单 · 审稿应对
```

## 快速安装

本技能为套件入口。安装后请依次安装11个子技能：

```bash
skillhub install academic-paper-workshop        # 本入口
skillhub install literature-mining               # 文献挖掘
skillhub install plagiarism-precheck             # 查重预检
skillhub install academic-writing-bank           # 写作语料库
skillhub install academic-chart-gen              # 数据图表
skillhub install academic-figure-gen             # 架构配图
skillhub install paper-review-methodology        # 审查诊断
skillhub install academic-docx-toolkit           # 排版执行
skillhub install paper-version-manager           # 版本管理
skillhub install academic-reference-formatter    # 文献规范
skillhub install abstract-optimizer              # 摘要优化
skillhub install submission-helper               # 投稿辅助
```

## 全流程工作流

### 阶段〇：文献调研
```
literature-mining → 检索策略构建 + 文献矩阵 + 阅读笔记
literature-mining → Gap识别 + PRISMA流程图 + 证据分级
```

### 阶段一：框架设计
```
paper-version-manager → 建立版本追踪
paper-review-methodology → 四维度评估论文方案
academic-writing-bank → 选定章节模板，建立段落骨架
literature-mining → 文献矩阵 + Gap确认（验证选题创新性）
```

### 阶段二：内容撰写与配图
```
academic-writing-bank → 短语库 + 过渡词驱动正文撰写
academic-figure-gen → 生成架构图/流程图/技术演进图
academic-chart-gen → 生成数据图表（柱状/箱线/热力图等）+ 显著性标注
academic-docx-toolkit → 表格格式化 + 图片插入 + 段落排版
```

### 阶段三：审查迭代
```
paper-review-methodology → 29类方法逐项审查 + P0-P3分级
academic-reference-formatter → 引用交叉检查 + 格式统一
paper-version-manager → CHANGELOG记录 + 评分追踪
plagiarism-precheck → 查重预检 + 高重复区定位 + 结构性降重
```

### 阶段四：终审定稿
```
academic-reference-formatter → 参考文献终审 + 零引用预警
academic-docx-toolkit → 期刊模板套用 + 最终排版
paper-review-methodology → 终审评分 + 脱敏筛查
abstract-optimizer → 中英摘要对称性审查 + 30项清单 + 关键词优化
plagiarism-precheck → 终版查重 + AI查重双检
```

### 阶段五：投稿发表
```
submission-helper → Cover Letter撰写 + 45项投稿检查清单
submission-helper → 审稿意见应对 + Rebuttal + 周期管理
```

## 跨技能联动模式

| 联动路径 | 说明 |
|---------|------|
| **文献 → 写作** | `literature-mining` Gap识别 → `academic-writing-bank` 引言/综述章节 |
| **查重 → 写作** | `plagiarism-precheck` 高重复区定位 → `academic-writing-bank` 重写模板 |
| **查重 → 审查** | `plagiarism-precheck` AI查重双检 → `paper-review-methodology` #23脱敏联动 |
| **写作 → 排版** | `academic-writing-bank` 章节模板 → `academic-docx-toolkit` 自动套用段落样式 |
| **图表 → 排版** | `academic-chart-gen` / `academic-figure-gen` 生成图片 → `academic-docx-toolkit` 自动嵌入并重排编号 |
| **审查 → 写作** | `paper-review-methodology` 结构审查 → `academic-writing-bank` 提供章节重写模板 |
| **审查 → 查重** | `paper-review-methodology` 内容审查 → `plagiarism-precheck` 引用边界检查 |
| **审查 → 版本** | `paper-review-methodology` 审查报告 → `paper-version-manager` 自动生成 CHANGELOG |
| **审查 → 文献** | `paper-review-methodology` #22 方法 → `academic-reference-formatter` 执行修正 |
| **版本 → 排版** | `paper-version-manager` 安全底本选定 → `academic-docx-toolkit` 多文档合并 |
| **摘要 → 正文** | `abstract-optimizer` 映射验证 → 正文补充缺失数据/修改不一致 |
| **终审 → 投稿** | `paper-review-methodology` 终审通过 → `submission-helper` 投稿检查清单 + Cover Letter |
| **摘要 → 投稿** | `abstract-optimizer` 终审摘要 → `submission-helper` 投稿材料打包 |
| **数据 → 图表 → 嵌入** | CSV/Excel → `academic-chart-gen` 统计图 → `academic-docx-toolkit` 嵌入Word |

## 典型话术

### 启动套件
- "启动论文工坊" / "Start academic workshop"
- "帮我从零开始写一篇论文" / "Help me write a paper from scratch"

### 阶段跳转
- "审查当前论文版本" → 触发 paper-review-methodology
- "生成论文配图" → 触发 academic-figure-gen
- "格式化论文排版" → 触发 academic-docx-toolkit
- "追踪版本演进" → 触发 paper-version-manager
- "检查参考文献格式" → 触发 academic-reference-formatter

### 串联指令
- "审查论文→修复P0问题→更新版本记录"（审查→排版→版本三联动）
- "生成配图→插入论文→重新排版"（配图→排版联动）

## 评分公式（通用）

加权评分：内容完整性×0.30 + 逻辑完整性×0.25 + 逻辑闭环×0.25 + AI检测评估×0.20

优质线：85分（具备送审条件）

## 适用场景

| 场景 | 涉及子技能 |
|------|-----------|
| 从零写论文 | 全部11个（文献→查重→写作→配图→审查→排版→版本→摘要→投稿） |
| 文献调研 | literature-mining |
| 正文撰写 | writing-bank + docx |
| 数据图制作 | chart-gen + docx |
| 架构图制作 | figure-gen + docx |
| 论文修改润色 | review + writing-bank + docx |
| 查重降重 | plagiarism-precheck + writing-bank |
| 摘要优化 | abstract-optimizer |
| 格式终审 | docx + reference + review |
| 版本管理 | version + review |
| 投稿全套 | submission-helper + reference + review + abstract-optimizer |
