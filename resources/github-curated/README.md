# GitHub 精选资源库

> 整理日期：2026-11-06  
> 目的：集中收藏值得持续关注的开源项目、技术目录与学习资料，优先覆盖 AI、Agent、iPhone/iOS、网络工具和自托管服务。

本目录采用**资源索引**方式：保留上游仓库链接、用途说明和使用提醒，不把第三方仓库的全部源码直接复制进来。这样可以避免覆盖上游更新、遗漏许可证义务或把不相关代码混入现有 `skills` 项目。需要实际使用某个项目时，再按其许可证和官方安装说明单独 Fork、Clone 或安装。

## 1. AI、模型与 Agent

| 项目 | 用途 | 仓库 |
|---|---|---|
| Hugging Face Transformers | 主流开源模型的加载、训练与推理工具库 | https://github.com/huggingface/transformers |
| Ollama | 在本地运行和管理大语言模型 | https://github.com/ollama/ollama |
| Open WebUI | 自托管的模型交互界面，可连接本地模型服务 | https://github.com/open-webui/open-webui |
| Dify | 构建 AI 应用、工作流和 Agent 的平台 | https://github.com/langgenius/dify |
| Anthropic Skills | Agent 可复用技能与工作流示例 | https://github.com/anthropics/skills |
| Awesome LLMOps | LLM 部署、服务、监控、数据和运维工具精选目录 | https://github.com/tensorchord/Awesome-LLMOps |

## 2. Agent 技能与开发效率

| 项目 | 用途 | 仓库 |
|---|---|---|
| Matt Pocock Skills | 面向真实软件工程流程的 Agent Skills；当前账号的 `skills` 仓库本身就是这一项目的副本/来源线索 | https://github.com/mattpocock/skills |
| Awesome AI DevTools | AI 辅助开发工具目录 | https://github.com/jamesmurdza/awesome-ai-devtools |
| Public APIs | 可用于学习和集成的公开 API 目录 | https://github.com/public-apis/public-apis |
| Free Programming Books | 免费编程书籍与学习资料索引 | https://github.com/EbookFoundation/free-programming-books |

## 3. iPhone、iOS 与 Apple 开发

| 项目 | 用途 | 仓库 |
|---|---|---|
| iOS Developer Tools | iOS 开发、调试、分析、网络和辅助工具目录 | https://github.com/LeoMobileDeveloper/ios-developer-tools |
| Awesome iOS | iOS 开发生态精选资源 | https://github.com/vsouza/awesome-ios |
| Apple Open Source | Apple 官方开源项目与源码入口 | https://github.com/apple |

## 4. 网络、代理与连接工具

| 项目 | 用途 | 仓库 |
|---|---|---|
| sing-box | 通用代理平台与网络连接工具链；适合研究协议、路由和规则配置 | https://github.com/SagerNet/sing-box |
| Mihomo | 规则驱动的代理内核，可用于理解策略组、规则和 DNS 行为 | https://github.com/MetaCubeX/mihomo |
| Clash Verge Rev | 桌面端代理客户端，适合研究配置管理与规则使用 | https://github.com/clash-verge-rev/clash-verge-rev |
| v2rayN | Windows 平台代理客户端与配置管理工具 | https://github.com/2dust/v2rayN |

**安全提醒：** 代理客户端、订阅链接和规则文件都可能改变设备流量去向。只使用可信来源；导入配置前检查远程脚本、DNS、证书、规则范围和更新地址。不要把个人订阅 URL、Token、密码或私钥提交到公开仓库。

## 5. 自托管与个人数据管理

| 项目 | 用途 | 仓库 |
|---|---|---|
| Awesome Selfhosted | 自托管服务与 Web 应用的分类目录 | https://github.com/awesome-selfhosted/awesome-selfhosted |
| Immich | 自托管照片和视频管理方案 | https://github.com/immich-app/immich |
| Syncthing | 多设备间去中心化文件同步 | https://github.com/syncthing/syncthing |
| Uptime Kuma | 自托管服务可用性监控面板 | https://github.com/louislam/uptime-kuma |

## 6. 通用精选目录

| 项目 | 用途 | 仓库 |
|---|---|---|
| Awesome | 高质量开源资源列表的总目录 | https://github.com/sindresorhus/awesome |
| Awesome Mac | macOS 应用与工具目录 | https://github.com/jaywcjlove/awesome-mac |

## 使用与维护原则

1. **先看上游，再决定是否引入代码。** 本索引只负责发现和导航，不代表对每个项目的安全性、活跃度或适用性作永久保证。
2. **检查许可证。** Fork、复制、二次分发或商用前，阅读仓库中的 LICENSE、NOTICE 和商标说明。
3. **检查维护状态。** 关注最近提交、Release、Issue、已知漏洞和维护者公告。
4. **保护凭据。** 不提交 API Key、访问 Token、私有订阅链接、Cookie、证书私钥、个人数据或设备标识。
5. **优先 Fork，而非直接复制。** 需要长期跟踪的项目，使用 GitHub Fork 并保留上游来源；需要少量参考时只记录链接和必要说明。
6. **定期复核。** 发现仓库归档、迁移、失去维护或出现安全问题时，更新本索引并标注状态。

## 后续可扩展方向

- AI Agent 与自动化工作流的实用模板
- iOS 网络诊断、DNS、隐私和设备管理资料
- Apple Intelligence 与跨区域功能的官方文档
- 数据备份、密码管理和个人知识库
- 适合个人使用的开源服务及其部署指南
