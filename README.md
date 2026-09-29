# Premium Developer Workbench 设计资料

这组资料用于改进现有的 Agent / developer workbench。目标是让它更像一件成熟、安静、可信的产品：保留 Claude 式的阅读舒适度，同时具备 Linear、Raycast、GitHub、Vercel、Stripe Workbench 和现代 IDE 的任务效率。

这里的“Claude 气质”指内容清楚、节制、易读；不指复制 Claude 的品牌色、字体、标志或整页视觉。

## 文件导航

| 文件 | 用途 |
|---|---|
| [Premium-Developer-Workbench-Reference-Atlas.md](Premium-Developer-Workbench-Reference-Atlas.md) | 40 个具体网站、产品工作区、设计系统和获奖作品。每项都注明可借鉴的决策与迁移边界。 |
| [Claude-Adjacent-Developer-Workbench-Design-System.md](Claude-Adjacent-Developer-Workbench-Design-System.md) | 视觉方向、初始颜色 Token、字体职责、桌面工作区布局、组件、状态与动效规则。 |
| [Luna-Developer-Workbench-Redesign-Brief.md](Luna-Developer-Workbench-Redesign-Brief.md) | 可以直接交给 Luna 的执行任务书，包含项目审查、参考选择、实施顺序和验收要求。 |

## 推荐阅读与使用顺序

1. 先读本 README，了解目标和约束。
2. 读参考图册，先看优先级最高的 9 个工作台参考；再按实际页面功能查看其他条目。
3. 读设计系统，把参考中的设计决策转译为适合当前产品的规则。
4. 把三份资料连同 README 一起交给 Luna，按任务书先审查现有界面，再实施改版。

每个参考要回答一个实际问题：它改善了什么，适合落在哪个现有组件，为什么适合当前工作流。不要把不同品牌的配色、卡片、动效拼成大杂烩。

## 设计目标

- **桌面优先的工作台**：当前任务、Agent 过程、结果、错误和下一步操作都容易找到。
- **安静而有质感**：依靠层级、排版、对齐、真实内容和克制的细节建立高级感。
- **开发工具应有的信息密度**：简化视觉噪音，但不隐藏任务状态、事件、代码上下文或恢复入口。
- **像当前产品，而不是模板**：沿用真实的品牌、术语、数据、路由和交互；不添加虚构功能或营销内容。

## 必须保留的产品行为

这次改版针对现有前端。不得擅自改变 API 契约、SSE 事件与顺序、路由、持久化、任务执行、错误恢复、重试/继续/取消行为或已有键盘快捷键。设计系统和任务书都以这些现有行为为前提。

## 参考与证据说明

40 个条目按正式奖项、设计画廊收录、成熟产品范本等不同依据分类；并非所有页面都获过奖。网站会更新，画廊截图也可能对应旧版，实施前应核对当前页面和现有产品实际状态。

## 一句话方向

**做一件严谨好用的开发工具，让人愿意长时间阅读和工作；让真实任务与结果成为界面的主角。**

