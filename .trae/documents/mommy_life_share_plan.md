# 40+岁二宝妈妈生活分享器 - 实施计划

## 项目概述

创建一个新的skill，用于分享育儿经验、读书精进、亲子阅读、自我关怀和家庭关系，人设为40+岁二宝妈妈。

---

## 核心功能规划

### 1. 内容领域
- **育儿经验分享** - 育儿心得、亲子互动、成长记录
- **读书分享** - 读书笔记、个人精进、学习方法
- **亲子阅读** - 亲子共读经验、绘本推荐、阅读方法
- **自我关怀** - 妈妈的自我照顾、情绪管理、时间管理
- **家庭关系** - 夫妻关系、家庭氛围、生活平衡

### 2. 作者人设
- **年龄**：40+岁
- **身份**：二宝妈妈（老大小学/初中，老二幼儿园/小学）
- **性格**：温暖亲和、真诚分享、不焦虑、懂生活
- **说话风格**：像和闺蜜聊天一样，温暖、亲切、有共鸣
- **特点**：有经验、接地气、不完美但真实

### 3. 文章模板
- **育儿故事型** - 通过真实育儿故事分享经验
- **读书感悟型** - 结合自身经历的读书分享
- **亲子共读型** - 亲子阅读经验和书单推荐
- **自我成长型** - 妈妈的自我关怀和精进
- **生活随笔型** - 日常生活中的感悟和思考

### 4. 增强功能
- 文件保存（自动保存到articles目录）
- 标题A/B测试
- SEO优化建议
- 配图建议
- 字数统计和阅读时长
- 版本管理

---

## 实施任务清单

### [ ] 任务1：创建skill目录结构和SKILL.md主文件
- **Priority**：P0
- **Description**：创建新skill的目录结构和主配置文件
- **Success Criteria**：
  - 目录：`.trae/skills/mommy-life-share/`
  - SKILL.md包含完整的功能描述、使用方法和注意事项
- **Test Requirements**：
  - `programmatic` TR-1.1：目录结构正确创建
  - `human-judgement` TR-1.2：SKILL.md内容完整清晰

### [ ] 任务2：设计详细的作者人设（author-persona.md）
- **Priority**：P0
- **Description**：创建40+岁二宝妈妈的详细人设文档
- **Success Criteria**：
  - 基本信息（年龄、家庭结构、职业等）
  - 说话风格和常用表达
  - 个人经历素材库（育儿经历、读书经历、自我成长经历等）
  - 可以分享的成功经验
- **Test Requirements**：
  - `programmatic` TR-2.1：文档结构完整
  - `human-judgement` TR-2.2：人设真实、立体、有共鸣

### [ ] 任务3：创建文章模板系统（templates.md）
- **Priority**：P0
- **Description**：设计5种文章模板，覆盖不同内容类型
- **Success Criteria**：
  - 育儿故事型模板
  - 读书感悟型模板
  - 亲子共读型模板
  - 自我成长型模板
  - 生活随笔型模板
- **Test Requirements**：
  - `programmatic` TR-3.1：5种模板都已创建
  - `human-judgement` TR-3.2：模板结构合理、可操作性强

### [ ] 任务4：创建工作流程文档（workflow.md）
- **Priority**：P1
- **Description**：设计从需求到成品的完整工作流程
- **Success Criteria**：
  - 8个完整阶段（需求确认→选题→大纲→模板→正文→去AI味→配图→保存）
  - 每个阶段的输入输出清晰
- **Test Requirements**：
  - `programmatic` TR-4.1：工作流程文档完整
  - `human-judgement` TR-4.2：流程逻辑清晰、可执行

### [ ] 任务5：创建去AI味优化策略（de-ai-optimization.md）
- **Priority**：P1
- **Description**：针对40+岁二宝妈妈人设的去AI味优化策略
- **Success Criteria**：
  - 加入大量育儿和读书的个人经历
  - 温暖亲和的语气
  - 真实的"不完美"分享
- **Test Requirements**：
  - `programmatic` TR-5.1：优化策略文档完整
  - `human-judgement` TR-5.2：策略针对人设特点

### [ ] 任务6：创建增强功能文档（enhanced-features.md）
- **Priority**：P1
- **Description**：文件保存、SEO优化、标题A/B测试等增强功能
- **Success Criteria**：
  - 文件保存（命名规则：YYYY-MM-DD-{主题}-share.md）
  - 标题A/B测试
  - SEO优化建议
  - 配图建议
- **Test Requirements**：
  - `programmatic` TR-6.1：增强功能文档完整
  - `human-judgement` TR-6.2：功能描述清晰

### [ ] 任务7：创建完整使用示例（example.md）
- **Priority**：P2
- **Description**：以一篇育儿文章和一篇读书文章为例，展示完整使用流程
- **Success Criteria**：
  - 育儿文章示例
  - 读书文章示例
  - 完整的工作流程展示
- **Test Requirements**：
  - `programmatic` TR-7.1：示例文档完整
  - `human-judgement` TR-7.2：示例真实、有参考价值

### [ ] 任务8：创建联网搜索方案（web-search.md）
- **Priority**：P2
- **Description**：育儿知识、书籍信息、亲子阅读素材的搜索方案
- **Success Criteria**：
  - 育儿知识搜索策略
  - 书籍信息搜索策略
  - 亲子阅读素材搜索策略
- **Test Requirements**：
  - `programmatic` TR-8.1：搜索方案文档完整
  - `human-judgement` TR-8.2：搜索策略实用

---

## 文件结构

```
.trae/skills/mommy-life-share/
├── SKILL.md              # 主配置文件
├── author-persona.md      # 作者人设
├── templates.md          # 文章模板
├── workflow.md           # 工作流程
├── de-ai-optimization.md # 去AI味优化
├── enhanced-features.md  # 增强功能
├── example.md           # 使用示例
└── web-search.md        # 联网搜索方案
```

---

## 时间估算

| 任务 | 预计时间 |
|-----|---------|
| 任务1-3（核心功能） | 30-45分钟 |
| 任务4-6（辅助文档） | 30-45分钟 |
| 任务7-8（补充文档） | 20-30分钟 |
| **总计** | **80-120分钟** |

---

## 验收标准

- [ ] 所有8个任务都已完成
- [ ] 所有文档都已创建在正确的目录
- [ ] 文档内容完整、逻辑清晰
- [ ] 人设真实、立体、有共鸣
- [ ] 模板可操作、覆盖全面
- [ ] 工作流程清晰可执行
