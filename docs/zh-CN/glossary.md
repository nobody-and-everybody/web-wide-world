# 术语对照表（英文 ↔ 中文）

## 核心名词

| 英文 | 中文 | 解释 |
|------|------|------|
| Web Wide World | 互联网广域世界 | 描述一个覆盖整个互联网的共享虚拟世界 |
| Site | 站点 | 托管部分世界内容的网站、服务或服务器 |
| Program | 服务程序 | 提供具体功能（如 3D 渲染、社交、交易）的后端服务 |
| Asset | 资产 | 3D 模型、纹理、音效、代码脚本等可复用内容 |
| Contract | 契约 | 站点之间或站点与服务程序之间的交互协议 |
| Entity | 实体 | 世界中的可交互对象（如 NPC、建筑、物品） |
| User | 用户 | 参与世界的个体 |
| Versioning | 版本管理 | 独立站点发布更新同时保持世界同步的机制 |
| Permissions | 权限控制 | 对实体、资产、功能等资源的访问控制体系 |
| Decentralized | 去中心化 | 无单一控制节点，各节点独立运行并协作 |

## 技术方向

| 英文 | 中文 | 说明 |
|------|------|------|
| 3D Gaussian Splatting | 3D 高斯泼溅渲染 | 当前主流的 3D 场景实时渲染技术 |
| Scene | 场景 | 一个完整的三维空间 |
| Region Replace | 区域动态替换 | 拉远时用简模（或卸载），拉近时加载高精度区域 |
| GLB / GLTF | GLB / GLTF 格式 | 标准 3D 模型格式 |
| Collision Mesh | 碰撞网格 | 用于物理检测的简化几何 |
| NPC | 非玩家角色 | 由 AI 或规则控制的虚拟角色 |
| Avatar | 用户化身 | 用户在世界中使用的角色模型 |
| Real-time Pub/Sub | 实时发布订阅 | 多用户状态同步的通信模式 |

## 项目组织

| 英文 | 中文 | 说明 |
|------|------|------|
| Issue | 议题 | GitHub 上提出的问题、建议或任务 |
| Pull Request | 合并请求 | 提交的代码修改建议 |
| Commit | 提交 | 代码库的一次变更记录 |
| Repository | 代码仓库 | 项目的全部代码和文档 |
| Community | 社区 | 参与项目的所有贡献者与用户 |
| Contribution | 贡献 | 对项目任何部分的改进（代码、文档、翻译等） |

## 相关链接

- [GitHub 中文社群指南](https://docs.github.com/zh/communities) —— GitHub 官方中文社区文档
- [术语翻译最佳实践](https://open-source-guide.openssf.org/zh-hans/translation/) —— 开源项目翻译规范
- [Web Wide World 英文词汇表](docs/en/glossary.md) —— （待建）

如有新术语需要添加或现有解释需要完善，请提交 Issue 或直接修改本文件。