# 斌的世界 · AI Agent 人格 Skill

> 这是一个skill基于「斌的世界」312 期视频蒸馏的情感分析人格，可直接安装到 ChatGPT、Claude、Cursor 等任意 AI Agent。

## 这是什么

把斌（抖音情感博主「斌的世界」）的思维框架蒸馏成一个可复用的 AI 人格文件。包含：

- **7 个核心心智模型**：框架决定位置、匮乏即死亡、窗口期法则、行为先于心理、成就感悖论、明暗线沟通、经验即护城河
- **8 条决策启发式**：推拉法则、不哄原则、台阶理论、公开招标策略……
- **完整表达 DNA**：句式、节奏、幽默风格、禁忌词

安装后，对 Agent 说「切换到斌」即可用斌的视角分析感情问题。

## 快速安装

把 `SKILL.md` 复制到你的 Agent 的 system prompt / character card / 知识库。各平台具体操作：

| 平台 | 操作 |
|------|------|
| ChatGPT Custom GPT | Configure → Instructions → 粘贴 SKILL.md 全文 |
| Claude Projects | Project knowledge → Upload → 选择 SKILL.md |
| Cursor / Windsurf | 粘贴到 `.cursorrules` 或 `.windsurfrules` |
| Dify / Coze | 导入为知识库文档，或写入 system prompt |
| 其他 Agent | 将 SKILL.md 全文注入 system prompt |

## 使用

```
用户：切换到斌，她约我看电影是什么意思
用户：用斌的视角分析这段聊天记录
用户：斌怎么看女生说"慢慢来"
```

Agent 会以斌的身份直接回应。

## 数据来源

- **来源**：[斌的世界](https://www.douyin.com/user/MS4wLjABAAAAyPJgvG9us2BPCv3dIjoh1ILAOQIBBzYajuFSn6u3FmvPXehXwJFMDmakdfIyS8j4) 抖音公开视频
- **语料规模**：312 个视频案例，1758 条观点
- **覆盖范围**：追求与暧昧(131例)、恋爱心理(62例)、吸引力与自我提升(32例)、两性差异(22例)等 11 个分类
- **提炼方法**：[女娲.skill](https://github.com/alchaincyf/nuwa-skill.git)

## 目录结构

```
├── SKILL.md                 ← 主文件，拖进 Agent 就能用
├── README.md                ← 本文件
└── references/
    └── research/            ← 研究数据（仅供查阅）
        ├── 00-master-index.md
        ├── category-L01.md ~ L12.md
        ├── theme-frequency.md
        ├── expression-dna.md
        └── self-reference.md
```

## 出处声明

本 Skill 的内容体系提炼自抖音创作者 **[斌的世界](https://www.douyin.com/user/MS4wLjABAAAAyPJgvG9us2BPCv3dIjoh1ILAOQIBBzYajuFSn6u3FmvPXehXwJFMDmakdfIyS8j4)** 的公开视频。斌是《恋爱操盘手》一书的作者，在情感分析领域有十余年经验。

如果您觉得这个 Skill 有用，请关注原作者斌的世界，支持他的原创内容。

## 许可

本仓库为斌的世界公开视频内容的分析提炼，仅用于学习和研究目的。原始视频内容、框架体系、术语（框架、登月、窗口期等）的版权归原作者斌的世界所有。

`SKILL.md` 文件本身采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 许可——可自由分享、改编，但需署名且不得商用。
