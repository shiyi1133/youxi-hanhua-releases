# 荣耀猎人 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/glory-hunters-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Glory Hunters(v2.0.1).gb

原输入完整SHA-256：`9d5023734c2f2090cf16187ff70711a79062913f648965699af9e2419bb79812`（4194304字节）。

范围：黑白GB原生SGB增强/边框；英西文分支译文，西语基底本来缺失的剧情仍缺失，不虚构补齐。

## 8px v0.1.0

字号范围：普通8px；标题2倍艺术字不是独立大字版。无10px。

目标完整SHA-256：`b12ddba944e035aeaa5bee942828ae05abb0ac527892e257e7a9a64207e680b9`（4194304字节）。

补丁：`GloryHunters_zh_v0.1.0_8px.bps`，SHA-256 `3c9a98df74e66f45c952b8205d672422b21760bb5e1d77ce1b7be729451282e1`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/glory-hunters-v0.1.0/glory-hunters-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/glory-hunters-v0.1.0/glory-hunters-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/glory-hunters-v0.1.0-8px-ninegrid.png)

荣耀猎人 v0.1.0 8px限定测试版；普通8px；标题2倍艺术字不是独立大字版。无10px。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：取得首朵花、成就获得1荣耀并用于打开首门、NPC、物品状态地图和成就页。

提供者诊断路径：四次坐标RAM写入绕过剧情到存档房间后才正常保存/取消/重试及新OS电池冷读；存档内容有效但进入存档房间不是自然路线。

保存边界：提供者诊断进入后正常保存32KiB电池冷读有效进度；不冒称完整自然保存路线。

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：完整自然路线和深层Boss
- 未验证：商店、最长变量
- 未验证：实机震动/打印机/联机及全通
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

