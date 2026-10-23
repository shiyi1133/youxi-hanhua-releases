# 泡泡龙（Taito Memorial） v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/taito-memorial-bubble-bobble-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Taito Memorial - Bubble Bobble (Japan) (SGB Enhanced) (GB Compatible)

原输入完整SHA-256：`d0745da8c7824b2719e382d80eb79d9364efea83c1b7a4a185e4a864545d5b3e`（1048576字节）。

范围：菜单、密码、剧情及已识别图字；GBC兼容80、原生SGB03。

## 8px v0.1.0

字号范围：普通8px；另有story10px仅15页剧情窗口真实10px，其余界面仍8px。

目标完整SHA-256：`815acb859e5caf18d760e025936f93a2488bbfc375ba26db4b716dfac9bf4d08`（1048576字节）。

补丁：`BubbleBobble_zh_v0.1.0_8px.bps`，SHA-256 `9bce71bb675c6297eb39450adc09ace67539e858dee8bdbf1b99054a9bc79392`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/taito-memorial-bubble-bobble-v0.1.0/taito-memorial-bubble-bobble-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/taito-memorial-bubble-bobble-v0.1.0/taito-memorial-bubble-bobble-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/taito-memorial-bubble-bobble-v0.1.0-8px-ninegrid.png)

泡泡龙（Taito Memorial） v0.1.0 8px限定测试版；普通8px；另有story10px仅15页剧情窗口真实10px，其余界面仍8px。 自然路径与诊断范围见测试说明，不代表全流程。

## 10px v0.1.0

字号范围：仅15页剧情真实10px，其它界面8px；更易拖慢/刷新残留。

目标完整SHA-256：`0b7c086095e8603b013e79ca05313ced66a587d3e52335fae4618992fda17b83`（1048576字节）。

补丁：`BubbleBobble_zh_v0.1.0_story10px.bps`，SHA-256 `6a34c1fd277df4e0d3e2e10ce3d8867530a4451afae8b58ba963e71ed499b980`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/taito-memorial-bubble-bobble-v0.1.0/taito-memorial-bubble-bobble-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/taito-memorial-bubble-bobble-v0.1.0/taito-memorial-bubble-bobble-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/taito-memorial-bubble-bobble-v0.1.0-10px-ninegrid.png)

泡泡龙（Taito Memorial） v0.1.0 10px限定测试版；仅15页剧情真实10px，其它界面8px；更易拖慢/刷新残留。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：最终普通/剧情10px ROM的CGB/DMG开场、首关移动、暂停/恢复、死亡续关是/否及初始BBBB密码删除重输。

提供者诊断路径：15页剧情、最终Boss第二页与结尾名单；后两格不是自然通关。

保存边界：MBC5无SRAM；初始BBBB密码只能验证输入，不证明有进度密码保存或冷读。

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：自然首关过关
- 未验证：后期关卡和非初始进度密码
- 未验证：大字长时间刷新
- 未验证：实机及完整通关
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。


大字版更容易出现拖慢、刷新残留等问题，遇到请及时在原楼反馈。
