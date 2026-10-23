# 魔法骑士雷阿斯 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/magic-knight-rayearth-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Magic Knight Rayearth (Japan) (SGB Enhanced)

原输入完整SHA-256：`3be897438e69a22c64be12ab1d5ed41f9f35a54e40a1ce909f9fe080734d7fa4`（262144字节）。

范围：633剧情/37内联UI/113动态字段含36敌名20地点43音乐语音条目与标题图；保版权/工作人员原文名，固定角色无自由命名

## 8px v0.1.0

字号范围：普通8px；标题两倍图字，不是10px；原生SGB图案/调色并非GBC或后期上色

目标完整SHA-256：`0e4ee943c1a1115c091fbccfa167b6615f5c396bcf587622015993a27870bcde`（1048576字节）。

补丁：`魔法骑士雷阿斯_v0.1.0_普通8px.bps`，SHA-256 `dac20eb75fbad743dd67ea4b5070d602c666454d3066e1298c34d347e4b476ae`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/magic-knight-rayearth-v0.1.0/magic-knight-rayearth-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/magic-knight-rayearth-v0.1.0/magic-knight-rayearth-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/magic-knight-rayearth-v0.1.0-8px-ninegrid.png)

魔法骑士雷阿斯 v0.1.0 8px限定测试版；普通8px；标题两倍图字，不是10px；原生SGB图案/调色并非GBC或后期上色 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：SGB模型0x20开场/肖像对白到罗塞塔镇、START状态/B返回/SELECT保存；镇内有进度新存/移动后取消电池SHA不变/覆盖改变；两次独立进程冷读地点；标题SELECT×32进入声音模式切换播放部分曲目；DMG标题/开场有限显示

提供者诊断路径：native1FFD战斗攻击/魔法/逃跑，非自然遇敌；剧情记录127是/否结果和长短句70/75/224/465/610；credits原署名字模，非自然结尾

保存边界：本版罗塞塔镇进度保存/取消/覆盖及独立进程电池冷读；原日文/其他汉化旧档动态名可能变化未保证，建议新开

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：自然首战/全怪物魔法/死亡完整升级
- 未验证：三线深支线/结局staffroll/商店购买
- 未验证：最长变量全组合/实机/旧档
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

