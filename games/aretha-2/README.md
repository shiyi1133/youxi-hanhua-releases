# 阿蕾莎2 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/aretha-2-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Aretha II (Japan)

原输入完整SHA-256：`afaf5380f970c2f07ff585a84bab50295fd17888591511cc1d71e8d7ddad7599`（262144字节）。

范围：1646事件文本、253物品/253名称、110UI、开场结尾、标题/旅馆招牌/佩拉货币图；标题/货币实际，旅馆仅静态图块未自然到达

## 8px v0.1.0

字号范围：Fusion8px；49bit无损压缩恢复完整8×8，非裁大字；无10px，保256KiB/MBC2，无SGB

目标完整SHA-256：`ddbf19b791976e3306aa4afe083c8191d877cbf349114591fc703b144adeec2c`（262144字节）。

补丁：`aretha2_v0.1.0_8px.bps`，SHA-256 `9a5ea3416ec0bc1790f1a08d89f53d1889cc781d53852990d3fe4384cd1b69b0`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/aretha-2-v0.1.0/aretha-2-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/aretha-2-v0.1.0/aretha-2-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/aretha-2-v0.1.0-8px-ninegrid.png)

阿蕾莎2 v0.1.0 8px限定测试版；Fusion8px；49bit无损压缩恢复完整8×8，非裁大字；无10px，保256KiB/MBC2，无SGB 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：完整开场/到村庄/SELECT六菜单进退；改名杨咩咩/重复删重输/8字上限拒绝第9字/8双字节原字符编辑；正常保存新OS进程仅读SAV冷读/嵌套窗口16父窗字形保持

提供者诊断路径：自然字体初始化后原事件表5事件2商店，购买短剑30000→22000；出售未可靠验收；注入蜻蜓遭遇，攻击/受伤/死亡暖重启；非自然遇敌/胜利奖励；3HRAM动态模板/18operand CPU执行；1698实际字形CPU逐像素

保存边界：原生17B/8字符姓名和MBC2记录结构保留，本版自然保存冷读有提供方记录；旧日文名可能编码冲突未保证，建议新档，勿跨SHA即时状态

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：自然商店/自然战斗/胜利奖励/出售
- 未验证：全部物品隐藏/最长变量实际窗口/深图事件/结尾全通
- 未验证：原NINTONDO隐藏名自然触发
- 未验证：实机/联机/旧日文姓名SAV
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

