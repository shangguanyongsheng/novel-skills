# Novel Skills

Agent skills for novel writing, review, and polishing.

Designed for Hermes Agent (and compatible with other AI coding agents).

## Usage

### Install

```bash
# Clone this repo as a skills source
git clone https://github.com/shangguanyongsheng/novel-skills.git
```

Or copy individual skill directories into your agent's skills directory.

## Available Skills

### story-review-iteration

短故事多轮审校迭代 — 输入短故事文件，通过 P0/P1/P2 分级问题识别 + 多轮版本迭代 + 自动评分，直到收敛为止。

适用于番茄小说、知乎盐选等平台的短篇小说精修。

**触发词**: "审校这个故事"、"多轮迭代修复"、"参考 Karpathy autoresearch 的思路审校"

**流程**: 备份原稿 → 6 Pass 全面审校 → 生成报告 → 循环修复 → 迭代评估 → 收敛判断

## Structure

```
novel-skills/
├── README.md
├── .gitignore
└── skills/
    └── story-review-iteration/
        └── SKILL.md
```

## License

MIT
