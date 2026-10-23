# 2021：月球逃亡 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/2021-moon-escape-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：2021：月球逃亡2021 - Moon Escape (World) (Aftermarket) (Unl).gb

原输入完整SHA-256：`edaa96727092b65460b9eb6582a55f60f9e03c2f5649171679ac306a78b4587b`（2097152字节）。

范围：用户aftermarket输入，modified_base未知，不据header称日版零售。1791字符串已译，1767静态文本消费者，24遗留未证实可达也有译文；303背景/210精灵审计，12背景21精灵改动。

## 8px v0.1.0

字号范围：普通Fusion Pixel 8px；标题图像放大不算大字版，无10px。

目标完整SHA-256：`912e909590f8b7d5e711abe000d530ed6e22d62bbedecf9cecba50b673b361e7`（4194304字节）。

补丁：`2021-moon-escape-v0.1.0-zh-8px.bps`，SHA-256 `4740c01f2e726be48cbf69d1cbb0ed4b39fcf479b1e67ea1218dd55a28251df9`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/2021-moon-escape-v0.1.0/2021-moon-escape-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/2021-moon-escape-v0.1.0/2021-moon-escape-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/2021-moon-escape-v0.1.0-8px-ninegrid.png)

2021：月球逃亡 v0.1.0 8px限定测试版；普通Fusion Pixel 8px；标题图像放大不算大字版，无10px。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：开场、取得电磁脉冲枪、离船、四页HUD出入、自然敌人对白/射击与投射物、持枪正常保存及新OS进程Continue恢复枪和地图。

提供者诊断路径：1791条分别进入CPU原生UIShowText，核缓冲、字形VRAM及银行恢复；不是1791条剧情自然到达。

保存边界：PROVIDER_SELFTEST_MEANINGFUL_NATIVE_SAVE_NEW_OS_COLD_READ

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：全流程与支线
- 未验证：深层商店升级
- 未验证：最终Boss/结局
- 未验证：实机
- 未验证：所有旧电池及即时状态兼容
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

