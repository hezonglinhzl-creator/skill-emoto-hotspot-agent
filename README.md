# 电摩社媒热点选题助手 / eMoto Social Trend Scout

**简体中文** | [English](README.en.md)

先查真实热点和视频画面，再判断电摩品牌适配度，输出可拍摄的选题方向。

[下载完整项目包](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools/raw/main/packages/skill-emoto-hotspot-agent.zip) · [全部项目](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools)

## 功能特性

- TikTok / Reels / Shorts 趋势检索
- 开头、中段和结尾画面验证
- 执行、观察、改编和跳过建议

## 这个包里有什么

| 内容 | 位置 |
| --- | --- |
| Skill 指令 | [SKILL.md](skill/emoto-hotspot-agent/SKILL.md) |

本项目是 Codex 工作流/脚本 Skill，没有另外一套需要启动的网页后台。

## 下载和解压

1. 在本仓库点绿色 **Code → Download ZIP**，或者点上方“下载完整项目包”。
2. 下载完成后右键 ZIP，选择**全部解压**，打开能看到此 README 的文件夹。
3. 保留整个目录；先按下一节准备程序，再安装和使用对应 Skill。

## 1. 先准备程序

无需另装程序。准备已登录的 Codex 和下方输入资料即可；带 Python 脚本的项目再按本页脚本说明安装依赖。

## 2. 再安装 Skill

1. 回到解压后的项目根目录，双击 `安装Skill.cmd`。
2. 安装器把 `skill/emoto-hotspot-agent` 复制到 `%USERPROFILE%\.codex\skills\emoto-hotspot-agent`。遇到同名 Skill 会跳过，留意窗口结果。
3. 重新打开 Codex，新建对话，使用下面的 Skill 名称和示例。
4. 公司策略禁止脚本时，可先阅读 install.ps1，或手动把整个 Skill 目录复制到同一目标位置。

## 3. 第一次怎么用

| 准备项 | 内容 |
| --- | --- |
| 输入 | 目标市场、车型、平台、日期和能拍摄的场景。 |
| 输出 | 带来源、时间和画面证据的选题表。 |

```text
使用 emoto-hotspot-agent，查今天美国电摩适合 Instagram Reels 的 5 个选题，逐个看画面并标注来源；没有画面证据的不要推荐。
```


## 当前限制与常见问题

需要联网检索能力；遇到平台登录要求时使用自己的账号。不能只根据标题或播放量判断内容。

| 问题 | 怎么处理 |
| --- | --- |
| 找不到 Skill | 检查安装窗口结果和目标 SKILL.md，重新打开 Codex 并新建对话。 |
| 程序启动失败 | 在程序目录打开 PowerShell 运行本文命令，让错误保留在窗口，再对照对应程序 README。 |
| 网页看不到插件 | 确认选中直接包含 manifest.json 的目录、网站受支持，并刷新网页。 |
| 外部服务不可用 | 配置自己的授权并检查资源权限；保留本地结果，不把失败说成同步/发送成功。 |

## 隐私与验证范围

这是程序源码与 Skill 分发包，不附带真实账号、OAuth 令牌、客户/KOL 台账、合同、订单、邮箱导出或业务媒体。服务需使用自己的配置。已检查文档和包内入口；此次文档核对没有执行真实下单、发邮件或发布内容。
