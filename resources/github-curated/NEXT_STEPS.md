# GitHub 精选项目：下一步引入计划

> 更新日期：2026-11-06  
> 目标仓库：`simonhan900525-sketch/skills`

## 本轮筛选结论

不建议把资源索引中的所有项目都 Fork。Fork 会持续占用仓库空间，也会带来上游同步、许可证和安全更新维护成本。建议先引入真正可能长期使用或需要跟踪的项目。

| 优先级 | 上游项目 | 建议 | 主要理由 |
|---|---|---|---|
| P1 | [anthropics/skills](https://github.com/anthropics/skills) | Fork 前先比对现有 `skills` 仓库 | Agent Skills 规范与示例价值高；避免重复 Fork 或覆盖现有内容 |
| P1 | [SagerNet/sing-box](https://github.com/SagerNet/sing-box) | 单独 Fork | 网络协议、路由和配置能力强；适合长期跟踪上游变更 |
| P1 | [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo) | 单独 Fork | 规则、DNS、策略组和代理内核资料有持续参考价值 |
| P2 | [ollama/ollama](https://github.com/ollama/ollama) | 先观察，确认本地模型使用需求后再 Fork | 本地模型运行工具；主要面向桌面/服务器环境 |
| P2 | [immich-app/immich](https://github.com/immich-app/immich) | 先观察，部署前再 Fork | 私有照片与视频管理；需要服务器、存储和备份维护 |
| P3 | [open-webui/open-webui](https://github.com/open-webui/open-webui) | 暂不 Fork | 可作为本地模型 Web 界面，但与 Ollama 使用场景有重叠 |
| P3 | [langgenius/dify](https://github.com/langgenius/dify) | 暂不 Fork | AI 应用与工作流平台，部署复杂度较高，适合有明确项目后再引入 |

## 引入前检查清单

对每个准备 Fork 的项目，逐项检查：

1. 上游仓库是否仍在维护，是否已归档。
2. 阅读 `LICENSE`、`NOTICE` 和商标政策；Fork 不等于获得任意商用或再分发权。
3. 检查最近 Release、重要安全公告和依赖风险。
4. Fork 时保留上游来源，不修改上游许可证文件。
5. 在本仓库记录用途、上游地址、许可证、同步方式和本地修改。
6. 不提交 Token、订阅链接、Cookie、私钥或个人数据。

## 当前执行状态

- 已完成：建立资源索引。
- 已完成：筛选优先候选并记录引入策略。
- 尚未完成：在 GitHub 上创建真正的 Fork。

**执行限制：** 当前可用的 GitHub 连接器支持读取仓库和向现有仓库写入文件，但没有提供创建 Fork 的操作。因此本轮没有用复制源码或新建同名仓库冒充 Fork，也没有改动现有项目源码。要完成真正的 Fork，需要通过 GitHub 网页上的 Fork 操作，或使用具备 GitHub Fork API 权限的工具。

## Fork 后的维护约定

- 上游更新通过 GitHub 的 Sync fork / 同步上游流程处理。
- 本地改动尽量放在独立分支，避免直接污染上游同步分支。
- 仅在有实际用途时保留 Fork；长期不使用的项目可取消关注或删除个人 Fork。
