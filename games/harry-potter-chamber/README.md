# 哈利波特与密室
当前公开源码／补丁资产：待本轮逐包核验与发布。此页面先登记实际最新版本与完整哈希，不提供ROM。

原输入：Harry Potter and the Chamber of Secrets (multilingual USA/Europe, revision 0)

原输入SHA256：`2788df60fc6373bdf7c9fa241a4409da14726f23017953adc1121bb90ad6b99a`

| 字号 | 实际版本 | 输出SHA256 |
| --- | --- | --- |
| 8px | v1.0.3 | `02246189b6a410574c43d0a60890433fdb65c0135e1b7209fb3cb19d3b430d20` |
| 10px-dialogue | v1.0.3 | `bc1331e74dee231df31ae42fae32d76393c6cce1021f6c99dc148234c767ba50` |

两字号均为v1.0.3限定排版修订测试版。CGB专用；普通8px保留四行，大字仅标准头像框使用10px，菜单、命名和战斗等仍8px。

已有记录包含实际窗口参数的受控排版与字形回归，两版正常开局、菜单、战斗／胜利、手动保存和独立新进程普通电池冷读。小游戏计分和姓名经过按键与保存回读；前置解锁为诊断设置，九图第8、9格不表示自然剧情解锁。

标题Logo漏“与”字的反馈实际仍开放；不据此声称本版已复现或已修。商店、全部成绩路线、后期／全通关、任意存档与跨版兼容和实机未验收。

大字版更容易出现拖慢、刷新残留等问题。先备份普通电池档，不跨版本搬即时状态。

[公开反馈及BUG状态](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

## 对应最终ROM真实截图

下列图片按实际版本／字号／最终ROM绑定，已从实际Git全文读取、核完整SHA256并逐张查看；本次资料整理未重新运行模拟器。[图片核验记录](../../data/Harry-screenshot-provenance.json)。

![版本 v1.0.3／8px](screenshots/v1.0.3-8px-257ad0ec2e8e.png)

v1.0.3 8px final native CGB: opening/menu/save/cold/battle; cells8/9 diagnostically unlock minigame then native score/name; UI8px; no fullgame/hardware claim

![版本 v1.0.3／10px-dialogue](screenshots/v1.0.3-10px-dialogue-d42d55fbe973.png)

v1.0.3 10px-dialogue final native CGB: opening/menu/save/cold/battle; cells8/9 diagnostically unlock minigame then native score/name; UI8px; no fullgame/hardware claim
