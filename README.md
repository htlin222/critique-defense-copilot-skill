# critique-defense-copilot

[![Build & Release Skill](https://github.com/htlin222/critique-defense-copilot-skill/actions/workflows/release.yml/badge.svg)](https://github.com/htlin222/critique-defense-copilot-skill/actions/workflows/release.yml)
[![GitHub Release](https://img.shields.io/github/v/release/htlin222/critique-defense-copilot-skill?include_prereleases&label=skill%20version)](https://github.com/htlin222/critique-defense-copilot-skill/releases/latest)
[![Release Date](https://img.shields.io/github/release-date-pre/htlin222/critique-defense-copilot-skill?label=released)](https://github.com/htlin222/critique-defense-copilot-skill/releases/latest)
[![Last Commit](https://img.shields.io/github/last-commit/htlin222/critique-defense-copilot-skill)](https://github.com/htlin222/critique-defense-copilot-skill/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Cite this repo](https://img.shields.io/badge/cite-CITATION.cff-blueviolet)](CITATION.cff)
[![Skills Protocol](https://img.shields.io/badge/protocol-vercel--labs%2Fskills-blue)](https://github.com/vercel-labs/skills)
[![Compatible Agents](https://img.shields.io/badge/agents-40%2B-green)](https://github.com/vercel-labs/skills#supported-agents)
[![Made for Claude Code](https://img.shields.io/badge/made%20for-Claude%20Code-d97757)](https://claude.com/claude-code)
[![Language](https://img.shields.io/badge/lang-繁體中文-blue)](#)
[![GitHub Stars](https://img.shields.io/github/stars/htlin222/critique-defense-copilot-skill?style=social)](https://github.com/htlin222/critique-defense-copilot-skill/stargazers)

> 線上被惡意質疑、人身攻擊、帶風向、截圖喊告恐嚇時的冷靜應對教練。

## Install

```bash
npx skills add htlin222/critique-defense-copilot-skill
npx skills add -g htlin222/critique-defense-copilot-skill        # global
npx skills add htlin222/critique-defense-copilot-skill --agent claude-code  # specific agent
```

## What it does

當你在網路上被某個人或一群人用操弄手法糾纏——帶風向的網紅、酸民、或一個用固定劇本攻擊你的對象——這個 skill 是陪在你身邊的應對教練。它的目標不是陪你打贏一場罵戰,而是讓你**看懂正在發生什麼、穩住情緒、做對選擇,全身而退而不被改變**。

它以四個模式運作:

- **模式 A — 拆解與預判**:指認對方在用哪一招操弄劇本(不可證偽門檻、隱性人身攻擊、截圖喊告恐嚇⋯⋯)、說明其目的、預判下一步,並給一個應對方向(通常是「不接這個球」)。
- **模式 B — 陪練**:在封閉沙盒裡扮演對手丟招,讓你練習不中計;每一輪都跳出角色標明招數與破解。
- **模式 C — 情緒煞車**:在你氣頭上想反擊時按下暫停,檢查你正要送出的訊息會不會反傷你自己。
- **模式 D — 分流與自保**:把收到的東西分成純情緒挑釁、值得一次性澄清、可能涉及法律三類,教你正確存證與何時找專業。

它**不生產攻擊**:不寫嘲諷文、不設計帶風向話術、不擬恐嚇訊息,也不針對特定真實對象產出可外傳的攻擊文本。涉及法律或情緒時,它給方向與陪伴,但不假裝是律師或心理師。

## Skill structure

```
critique-defense-copilot
├── references
│   ├── case-studies.md        # 真實台灣案例庫(楊又穎、113憲判3、揚言提告界線…)
│   ├── playbook-taxonomy.md   # 操弄劇本六招拆解
│   ├── sparring-mode.md       # 陪練腳本與點評
│   └── triage-and-legal.md    # 三類分流與台灣法律邊界
└── SKILL.md
```

## Protocol

This skill follows the [vercel-labs/skills](https://github.com/vercel-labs/skills) protocol.
Each push to `main` triggers a GitHub Action that packages the skill as a `.skill` file
and creates a release tagged with the commit SHA.

## Citation

If this skill helped your work, please cite it. Metadata lives in
[`CITATION.cff`](CITATION.cff) — GitHub renders a **"Cite this repository"**
button on the repo sidebar from it.

```bibtex
@software{lin_critique_defense_copilot_2026,
  author  = {Lin, Hsieh-Ting},
  title   = {critique-defense-copilot},
  version = {0.1.0},
  year    = {2026},
  url     = {https://github.com/htlin222/critique-defense-copilot-skill},
  license = {MIT}
}
```

## License

Released under the [MIT License](LICENSE) © Hsieh-Ting Lin (林協霆).
