# 家庭赛马2 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/family-jockey-2-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Family Jockey 2 - Meiba no Kettou (Japan)

原输入完整SHA-256：`37708a2ddc3eadeb0dd5846223befc938637be69941ce69299d5b6e950b8ffb1`（131072字节）。

范围：120普通脚本字段、319动态源记录/281去重记录、独立草泥HUD、命名/赛前/下注/赛后/领奖图字；195根/2489指令/382字段为静态枚举非自然全通

## 8px v0.1.0

字号范围：普通8px；原16px图字槽内部12px；不是全局12px，无10px或大字版

目标完整SHA-256：`6049dc55340fca91ed3955f6248ee409882b98496670c5d255cd79f387fb121a`（262144字节）。

补丁：`Family Jockey 2 - Meiba no Kettou (J) [ZH v0.1.0 8px].bps`，SHA-256 `a330a2af3012c2109bb57757c0128ad18c22fc812931cd1a32b444d7728ef9a8`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/family-jockey-2-v0.1.0/family-jockey-2-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/family-jockey-2-v0.1.0/family-jockey-2-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/family-jockey-2-v0.1.0-8px-ninegrid.png)

家庭赛马2 v0.1.0 8px限定测试版；普通8px；原16px图字槽内部12px；不是全局12px，无10px或大字版 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：主人杨咩咩、重复/删重输、4格上限；500初始款不足购买/取消；首场1000米自然第6名/无奖励、正常保存和新进程电池冷读

提供者诊断路径：资金改50000后原生购买/配种/出生/8字马名保存冷读；诊断资金下骑师/六马表/买9单位扣9、草泥HUD；八G1奖杯图字仅诊断显示

保存边界：本版自然首赛进度和诊断资金路线8字马名电池冷读有提供方记录；旧日文/其它汉化档及即时状态兼容未验证

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：自然赚款/购买繁殖/G1胜利
- 未验证：完整代际/退役出售全部分支
- 未验证：全部最长变量组合
- 未验证：条形码实物/多人附件/实机
- 未验证：START暂停功能未证实
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

