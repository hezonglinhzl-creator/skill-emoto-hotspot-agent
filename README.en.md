# eMoto Social Trend Scout / 电摩社媒热点选题助手

[简体中文](README.md) | **English**

Research live trends and video frames, judge electric-mobility brand fit, and propose practical content angles.

[Download complete project ZIP](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools/raw/main/packages/skill-emoto-hotspot-agent.zip) · [All projects](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools)

## Features

- TikTok / Reels / Shorts research
- Opening, middle and ending frame checks
- Do-now, watch, adapt and skip recommendations

## What is included

| Part | Location |
| --- | --- |
| Skill instructions | [SKILL.md](skill/emoto-hotspot-agent/SKILL.md) |

This project is a Codex skill/workflow with its own instructions or scripts; it has no separate app server to launch.

## Download and extract

1. Open this repository, choose **Code → Download ZIP**, or use the complete-project download above.
2. Right-click the downloaded ZIP and choose **Extract All**. Open the extracted folder containing this README.
3. Keep the whole folder together. Start the program first using the next section, then install/use its skill.

## 1. Set up the program first

No app installation is required. Prepare Codex and the input listed below. If the skill includes Python scripts, install the stated script dependency before running them.

## 2. Install the Skill

1. At the extracted project's root, double-click `安装Skill.cmd` on Windows.
2. The installer copies `skill/emoto-hotspot-agent` to `%USERPROFILE%\.codex\skills\emoto-hotspot-agent`. Existing same-name skills are skipped; check the displayed result.
3. Reopen Codex and start a new chat. Use the exact skill name shown below.
4. If scripts cannot run under your organization policy, open install.ps1 for review or copy the skill directory manually to the same destination.

## 3. First task

| Prepare | Details |
| --- | --- |
| Input | Market, product, platform, date and available filming resources. |
| Output | A topic table with sources, retrieval dates and frame evidence. |

```text
Use emoto-hotspot-agent to research five US eMoto Instagram Reels ideas for today. Verify frames, cite sources and exclude unverified candidates.
```


## Limits and troubleshooting

Requires live research access and your account when a platform requests login. Titles and view counts alone do not establish relevance.

| Problem | Next step |
| --- | --- |
| Skill not visible | Check the installer output and destination SKILL.md, reopen Codex and start a new chat. |
| Program fails to start | Open its directory in PowerShell and run the documented command so the error remains visible; check that program's README. |
| Browser panel missing | Select the exact folder containing manifest.json, check supported websites and refresh the website tab. |
| External service unavailable | Supply your own authorization/settings and verify access. Keep local output rather than claiming a sync/send succeeded. |

## Privacy and status

This is a source/skill distribution. No real accounts, OAuth tokens, customer/KOL lists, contracts, orders, mailbox exports or business media are included. You configure your own services. Documentation and package paths were checked; live orders, sends and publications were not executed as part of documentation validation.
