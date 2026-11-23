# 倪金海 · nijinhai

**全栈开发求职｜TypeScript · React / Next.js · Python**

我希望参与从页面交互、应用接口到数据模型的完整开发，也关注 AI 能力如何接入可验证、可维护的软件系统。

重庆邮电大学 · 生物信息学。这里展示我的公开项目、实现方式和可核查的实验记录。

## 技术与开发方向

| 方向 | 项目中使用的技术 |
| --- | --- |
| 前端与应用 | TypeScript、React、Next.js、Tailwind CSS |
| 数据与交互 | PostgreSQL、Prisma、React Hook Form、Zod、ECharts |
| Python 与 AI 集成 | Python、模型 API 接入、执行验证、程序合成 |
| 测试与交付 | Vitest、Python unittest、GitHub Actions、Docker |

我关注清晰的数据流、输入校验、错误处理和可复现的交付。对于 AI 功能，我会同时检查实际输出、失败路径与调用成本。

## 公开项目

### [Search Gap · 程序搜索与大模型协作](https://github.com/nijinhai/search-gap)

将外部模型的建议接入 DreamCoder，支持程序、草图、搜索权重和函数积木四类动作，通过执行验证和失败反馈完成多轮协作。

- **工程实现：** API 接入、结构化响应验证、预算控制、失败回退、结果记录与离线核验。
- **可核查结果：** 257 道合成任务中，固定预算解题率从 58.8% 提升至 75.9%；49 项测试及 GitHub Actions 检查通过。
- **评价边界：** 结果限于合成仿射任务；计入 API 延迟后总耗时更高，尚未验证跨领域泛化。

[项目说明](https://github.com/nijinhai/search-gap#readme) · [案例与取舍](https://github.com/nijinhai/search-gap/blob/main/docs/CASE_STUDY.md) · [自动检查](https://github.com/nijinhai/search-gap/actions)

### [Reusable Program Library · 可验证程序复用](https://github.com/nijinhai/reusable-program-library)

从输入输出样例出发进行符号程序合成，研究经过验证的函数库如何在有限搜索预算下组合与复用。

**展示重点：** Python 实现、程序正确性检查、模块复用与可复现实验。

### [Wild Demo · Python / C++ 交互式模拟](https://github.com/nijinhai/wild-demo)

使用 Python 与 C++ / pybind11 构建落沙和水模拟原型，提供交互绘制、调试控制台、结构化日志与性能观测。

**展示重点：** 跨语言集成、交互程序、调试工具和性能问题定位。

## 我希望参与的工作

- 使用 TypeScript、React / Next.js 开发业务应用，围绕页面、接口与数据库完成需求。
- 将 Python 或模型 API 接入应用，用明确的输入输出、验证和错误处理支撑功能。
- 通过代码审查、自动测试和持续集成，让功能便于维护与交付。

全栈应用经历涉及的私有代码不在此公开；本页项目链接均指向公开仓库。
