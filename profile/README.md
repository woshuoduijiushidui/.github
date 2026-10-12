# 我说对就是队

做 agentic operating system：一个 agent 内核，上面跑真正能用的桌面和手机 shell。

## 核心项目

| 项目 | 是什么 |
| --- | --- |
| [OctoSense](https://github.com/woshuoduijiushidui/OctoSense) | agent shell：桌面端（macOS / Windows / Linux）、Android Home、OnePlus 6 的 LineageOS ROM。一个 system agent 管着每个 app 自己的 app agent，危险动作必须经过人 |
| [octos](https://github.com/woshuoduijiushidui/octos) | Rust 写的开源 agent 内核。跑 agent session，session 可以拥有别的 session（peers） |
| [octos-arc](https://github.com/woshuoduijiushidui/octos-arc) | ARC-Bench 参赛用：钉死的 kernel + 完整的比赛流程（adapter、公开测试、本地跑分、打包） |
| [octos-arc-analysis](https://github.com/woshuoduijiushidui/octos-arc-analysis) | ARC-Bench 的分数分析 |
| [arc-adapter](https://github.com/woshuoduijiushidui/arc-adapter) | ARC-Bench adapter |
| [pantry-steward](https://github.com/woshuoduijiushidui/pantry-steward) | 智能冰箱卡片 |
| [agentic-requirement-compiler](https://github.com/woshuoduijiushidui/agentic-requirement-compiler) | 需求编译器 |
| [agentic-app](https://github.com/woshuoduijiushidui/agentic-app) | agentic app 实验 |
| [agentic-software-engineering-hackathon](https://github.com/woshuoduijiushidui/agentic-software-engineering-hackathon) | hackathon 相关 |

除注明外，以上多为 fork 自上游组织（`OctoSense-org`、`octos-org`）的工作副本。

## 上手

想给 OctoSense 写 app，不用 clone shell 仓库：先看 [OctoSense App Flow](https://github.com/OctoSense-org/OctoSense-App-Flow)（读 `AGENTS.md`，再读 `docs/QUICKSTART.md`），然后看 [OctoSense-App-Hub](https://github.com/OctoSense-org/OctoSense-App-Hub)。shell 仓库里的 `apps/` 是完整的示例 app。

---

It's a small team in China. Issues and PRs are welcome in either English or 中文.
