# 书本拆解 Skill - 实施计划

## 🎯 项目概述

创建一个类似于微信公众号文章生成器的新skill，专门用于拆解书本、章节或文章，生成个人学习、职场提升、能力精进类的公众号文章。

---

## 📋 核心功能模块

### [x] Task 1: 需求分析与功能定义
- **Priority**: P0
- **Depends On**: None
- **Description**: 
  - 确定书本拆解的核心流程
  - 定义输入方式（书名、章节内容、文章链接）
  - 确定输出格式（公众号文章）
  - 复用微信公众号生成器的现有功能
- **Success Criteria**:
  - 完整的功能清单
  - 清晰的输入输出定义
- **Test Requirements**:
  - `programmatic` TR-1.1: 功能清单包含至少8个核心功能
  - `human-judgement` TR-1.2: 功能设计符合用户使用场景
- **Notes**: 复用"快乐IT啊"作者人设

---

### [/] Task 2: 设计书本拆解工作流程
- **Priority**: P0
- **Depends On**: Task 1
- **Description**: 
  - 设计完整的拆解流程
  - 内容输入 → 核心提取 → 观点总结 → 个人感悟 → 文章生成
  - 确定每个步骤的输入输出
- **Success Criteria**:
  - 完整的工作流程图
  - 每个步骤的详细说明
- **Test Requirements**:
  - `programmatic` TR-2.1: 工作流程包含至少5个步骤
  - `human-judgement` TR-2.2: 流程逻辑清晰合理
- **Notes**: 参考微信公众号生成器的workflow.md

---

### [ ] Task 3: 创建skill目录结构和SKILL.md
- **Priority**: P0
- **Depends On**: Task 2
- **Description**: 
  - 创建 `.trae/skills/book-dissection-generator/` 目录
  - 编写SKILL.md主文件
  - 包含功能介绍、使用方法、注意事项
  - 描述中说明"Invoke when user wants to dissect a book/chapter/article"
- **Success Criteria**:
  - 目录结构正确
  - SKILL.md包含完整frontmatter和正文
- **Test Requirements**:
  - `programmatic` TR-3.1: SKILL.md存在且格式正确
  - `programmatic` TR-3.2: description包含"做什么"和"什么时候调用"
  - `human-judgement` TR-3.3: 功能描述清晰易懂
- **Notes**: 参考微信公众号生成器的SKILL.md

---

### [ ] Task 4: 设计书本拆解模板系统
- **Priority**: P1
- **Depends On**: Task 3
- **Description**: 
  - 创建templates.md
  - 设计3-4种拆解模板
    - 核心观点型：金句 + 解读 + 个人感悟
    - 方法实践型：步骤 + 案例 + 行动计划
    - 思维成长型：概念 + 启发 + 应用建议
    - 综合解读型：背景 + 核心 + 总结 + 感悟
  - 每个模板都包含固定开头【大家好，我是快乐IT啊。】
- **Success Criteria**:
  - 至少3种拆解模板
  - 每个模板都有完整结构
- **Test Requirements**:
  - `programmatic` TR-4.1: templates.md包含至少3种模板
  - `human-judgement` TR-4.2: 模板结构清晰实用
- **Notes**: 参考微信公众号生成器的templates.md

---

### [ ] Task 5: 创建作者人设文档（复用）
- **Priority**: P1
- **Depends On**: Task 3
- **Description**: 
  - 复用"快乐IT啊"作者人设
  - 可以根据书本拆解场景适当补充读书相关的经历
  - 确保作者人设一致
- **Success Criteria**:
  - author-persona.md存在
  - 人设与微信公众号生成器一致
- **Test Requirements**:
  - `programmatic` TR-5.1: author-persona.md存在
  - `human-judgement` TR-5.2: 人设风格一致
- **Notes**: 可以直接复制微信公众号生成器的author-persona.md

---

### [ ] Task 6: 创建工作流程文档
- **Priority**: P1
- **Depends On**: Task 2, Task 4
- **Description**: 
  - 创建workflow.md
  - 详细描述每个步骤
  - 内容输入阶段：支持书名、粘贴内容、链接
  - 核心提取阶段：提取金句、观点、案例
  - 观点总结阶段：提炼核心思想
  - 个人感悟阶段：加入"快乐IT啊"的经历和感悟
  - 文章生成阶段：应用模板，生成完整文章
- **Success Criteria**:
  - workflow.md包含完整步骤说明
  - 每个步骤都有输入输出定义
- **Test Requirements**:
  - `programmatic` TR-6.1: workflow.md包含至少5个阶段
  - `human-judgement` TR-6.2: 步骤说明清晰可操作
- **Notes**: 参考微信公众号生成器的workflow.md

---

### [ ] Task 7: 创建去AI味优化策略（复用）
- **Priority**: P2
- **Depends On**: Task 3
- **Description**: 
  - 复用微信公众号生成器的去AI味策略
  - 强调在书本拆解中加入个人读书感悟
  - 固定开头【大家好，我是快乐IT啊。】
- **Success Criteria**:
  - de-ai-optimization.md存在
  - 包含书本拆解专用的优化策略
- **Test Requirements**:
  - `programmatic` TR-7.1: de-ai-optimization.md存在
  - `human-judgement` TR-7.2: 优化策略适合书本拆解场景
- **Notes**: 可以复制并适当修改微信公众号生成器的de-ai-optimization.md

---

### [ ] Task 8: 创建增强功能文档（复用）
- **Priority**: P2
- **Depends On**: Task 3
- **Description**: 
  - 复用微信公众号生成器的增强功能
  - 文件保存、SEO优化、标题A/B测试、版本管理等
- **Success Criteria**:
  - enhanced-features.md存在
  - 包含所有增强功能说明
- **Test Requirements**:
  - `programmatic` TR-8.1: enhanced-features.md存在
  - `human-judgement` TR-8.2: 增强功能说明清晰
- **Notes**: 可以直接复制微信公众号生成器的enhanced-features.md

---

### [ ] Task 9: 创建示例文档
- **Priority**: P2
- **Depends On**: Task 4, Task 6
- **Description**: 
  - 创建example.md
  - 包含完整的使用示例
  - 示例1：拆解一本书（如《原子习惯》）
  - 示例2：拆解一篇文章
  - 示例3：拆解一个章节
- **Success Criteria**:
  - example.md存在
  - 包含至少2个完整示例
- **Test Requirements**:
  - `programmatic` TR-9.1: example.md存在
  - `human-judgement` TR-9.2: 示例清晰易懂
- **Notes**: 参考微信公众号生成器的example.md

---

## 📁 最终文件结构

```
.trae/skills/book-dissection-generator/
├── SKILL.md                    # 主文件
├── author-persona.md            # 作者人设（复用）
├── de-ai-optimization.md       # 去AI味优化（复用+修改）
├── enhanced-features.md         # 增强功能（复用）
├── example.md                  # 示例文档
├── templates.md                # 拆解模板
└── workflow.md                 # 工作流程
```

---

## 🎯 依赖关系图

```
Task 1 (需求分析)
    ↓
Task 2 (工作流程设计) ────────────┐
    ↓                              │
Task 3 (SKILL.md) ────────────────┤
    ↓                              │
    ├────────────────────────────┤
    ↓         ↓         ↓         ↓
Task 4    Task 5    Task 6    Task 7    Task 8
(模板)    (人设)    (流程)    (优化)    (增强)
    ↓         ↓         ↓         ↓         ↓
    └───────────────────────────────────────┘
                      ↓
                 Task 9 (示例)
```

---

## ✅ 验收标准

1. 所有9个任务都标记为完成
2. 所有文件都存在于正确的目录
3. SKILL.md格式正确，description包含"做什么"和"什么时候调用"
4. 所有模板都包含固定开头【大家好，我是快乐IT啊。】
5. 至少包含3种拆解模板
6. 示例文档包含至少2个完整示例
7. 可以正常调用skill进行测试
