---
title: "从小事做起，逐渐成为开源社区的核心力量"
author: "achao"
description: "从小事做起，逐渐成为开源社区的核心力量"
categories: "Apache ShenYu Committers"
tags: ["Apache ShenYu"]
date: 2024-08-14
---

### 个人介绍

- **姓名**: 阿超
- **GitHub**: [VampireAchao](https://github.com/VampireAchao)
- **Email**: [achao@apache.org](mailto:achao@apache.org)

### 初识 Apache ShenYu 网关

最初接触 Apache ShenYu 时，我正参与 Dromara 社区的开发工作。当时，猫大人（Apache ShenYu 的创始人和 VP）在社区中发起了一个前端开发需求。由于我正好熟悉 ShenYu 使用的 React 技术，我便决定加入贡献者的行列。虽然我并非 ShenYu 的直接用户，但为社区贡献我的前端技术，感觉是一个非常自然的选择。

### 开源贡献之路

在贡献 ShenYu 项目的过程中，我逐渐明确了自己的方向，并通过阅读源码来深入了解项目结构。在这个过程中，我积极地提交代码并进行修复，以下是我在 ShenYu 项目中的一些贡献：

#### ShenYu

> [13 commits](https://github.com/apache/shenyu/commits?author=VampireAchao)  
> 6,084 ++    2,379 --

- **功能开发**: 实现了客户端 ID 验证，确保在新登录时失效旧令牌 (#5600)
- **功能添加**: 为警报模块增加了菜单按钮及其相关权限管理 (#5156)
- **测试扩展**: 为 PortUtils.findPort 增加了单元测试用例 (#4604)
- **默认配置改进**: 设置 NettyClient 作为默认的 HttpClient (#5200)
- **问题修复**: 修复了因上下文路径更新导致的路由匹配错误 (#5510)
- **时间格式修正**: 解决了警报模块中 LocalDateTime 的格式化问题 (#5180)

#### ShenYu Dashboard

> [27 commits](https://github.com/apache/shenyu-dashboard/commits?author=VampireAchao)  
> 1,780 ++    402 --

- **功能开发**: 在新登录时，使令牌失效，提升安全性 (#467)
- **新特性**: 添加了通用组件的命名空间选择功能 (#462)
- **安全优化**: 在多次错误密码输入后要求输入验证码 (#465)
- **界面优化**: 移除了多余的管理员信息编辑按钮，简化界面 (#463)
- **批量操作支持**: 增加了选择器和规则的批量启用/禁用功能 (#452)
- **用户体验提升**: 改进了 JSON 编辑器的使用体验 (#374)
- **性能优化**: 优化了 React 生命周期管理，提高了 Dashboard 的响应速度 (#369)
- **模块改进**: 对警报模块进行了关键功能优化 (#346)
- **集成增强**: 将警报模块的管理界面和功能进行了整合 (#333)
- **参数管理**: 在 API 请求参数缺失时，自动采用文档中的默认参数 (#332)
- **文档标准化**: 统一了 API 文档格式，并修复了多个集成问题 (#303)
- **文档改进**: 对 API 文档进行了全面的优化调整 (#301)
- **导航功能**: 在菜单导航中新增了系统和资源的搜索功能 (#279)
- **路由修正**: 修正了上下文路径更新后的路由匹配问题 (#428)
- **标签管理**: 解决了警报模块中标签删除的相关问题 (#377)
- **删除确认**: 为 API 标签删除功能增加了确认步骤，防止误操作 (#375)
- **页面错误修复**: 修复了组件挂载时导致的代理页面错误 (#351)
- **查询渲染修复**: 解决了 HeadersEditor 中查询渲染的问题 (#331)

### 社区参与和成长

通过参与 ShenYu 的社区例会和贡献代码，我不仅提升了自己的技术水平，还学到了如何更有效地在开源项目中进行协作。与社区成员的合作，让我深刻体会到开源社区的开放与包容。

### 给开源开发者的建议

对于想要加入开源项目的开发者，我的建议是：从小处着手，不要怕事情小，只要它有助于项目的发展，你的每一次贡献都会被社区所重视。持续学习和不断尝试，最终你会找到适合自己的贡献方式。

### 一起为 ShenYu 贡献力量

如果你也想为 Apache ShenYu 贡献力量，可以从以下几点入手：

- 阅读 [贡献者指南](https://shenyu.apache.org/zh/community/contributor-guide)
- 参与 [GitHub Issues](https://github.com/apache/shenyu/issues) 讨论，寻找适合你的贡献机会

### 结语

被提名为 ShenYu Committer 对我来说是一个重要的里程碑。我将继续为 ShenYu 贡献力量，也期待更多的开发者加入我们，共同推动 ShenYu 的发展。
