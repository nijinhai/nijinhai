# 倪金海

**AI 应用开发 / 全栈工程 / 算法探索**

约 3 年开发经验，做过 AI 产品从需求梳理到全栈开发、部署试点。使用 Python、TypeScript、React/Next.js 与多模态 LLM，以原型和实验权衡效果、成本及限制；近期探索程序合成、状态空间模型与可复用计算。

## 代表工程项目

**AI 教育批阅系统｜技术方案与全栈开发**<br>
面向教师批阅和学情反馈，负责「木晨 100」「小晨优学」的方案、开发、部署与试点；串联答卷定位切割、OMR、主观题多模态分析、异常复核、错题与练习生成，覆盖 Web 教师端和家长小程序。采用受约束模型决策与代码编排，结合异常降级、教师复核控制效果和调用成本。**已在 2 所学校小范围试点**；业务源码未公开。

**农业数字化平台｜需求与方案、原型验证**<br>
围绕农业技术问诊与数字农场，负责业务梳理、平台定位和方案取舍，结合使用场景、合规与投入成本推进平台原型、对外展示方案。**阶段：需求梳理与原型推进**；业务源码未公开。

## AI Research & Experiments

**Search Gap** — 外部建议如何帮助程序搜索？实现 LLM 提议、程序验证、失败反馈与多轮闭环。<br>
**观察：**257 道合成仿射任务、每题 2,048 候选与 60 秒预算下，解题率 58.8% → 75.9%；含 API 延迟的总耗时更高，未验证跨领域泛化。[仓库与实验记录](https://github.com/nijinhai/search-gap)

**WSR** — 额外计算能否形成可复用中间结果？实现冻结 Mamba-2 的可微状态编辑与续算，并独立构建预计算对照。<br>
**观察：**小型规则图实验中，7 配置 × 3 配对种子；计算量匹配的宽单遍模型在留出组合上优于循环模型，尚无循环特有的泛化优势。沙盒未接入 Mamba。[仓库与实验记录](https://github.com/nijinhai/wsr-state-reorganization)

**Reusable Program Library** — 验证后的函数能否减少重复搜索？实现从示例合成、验证入库到冻结函数库组合调用。<br>
**观察：**3 种子合计 156 道合成后续任务解出 108 道；相对逐题重合成，按实验账本的增量操作调用少约 33.3%，也少解 27 题，体现成本与覆盖的取舍。[仓库与实验记录](https://github.com/nijinhai/reusable-program-library)

## 技术栈

**AI / Research：**Python、PyTorch、LLM、Multimodal、Program Synthesis<br>
**Engineering：**TypeScript、React、Next.js、Node.js、PostgreSQL、Docker、Linux

## Resume & Contact

- GitHub：[github.com/nijinhai](https://github.com/nijinhai)
- 邮箱：[1540804315@qq.com](mailto:1540804315@qq.com)
