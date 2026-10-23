# 融化公寓 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/the-melting-apartment-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：融化公寓The Melting Apartment.gb

原输入完整SHA-256：`00b42de93718b90a5379eacfa6a5147ba1d7660bbcd83492faaa3d8a8ab86a09`（524288字节）。

范围：CGB-only aftermarket（不能据.gb推GB）；89候选场景、303LOAD_TEXT/213唯一文本及10选择入口已处理；日期原数值和作者名保留，10背景6精灵图字；未证实可达KERNEL PANIC英文调试说明保留。

## 8px v0.1.0

字号范围：Fusion Pixel普通8px；原生双行18格，无10px。

目标完整SHA-256：`4adb0778c4daa64b11f7f74ec54733f2c088eb34d0624875356937adf126cf3b`（1048576字节）。

补丁：`融化公寓_v0.1.0_8px.bps`，SHA-256 `ad3c95dc0f02477921c5dcf0a6236f1ffc89134ac974c5baa0d7042c634c151e`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/the-melting-apartment-v0.1.0/the-melting-apartment-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/the-melting-apartment-v0.1.0/the-melting-apartment-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/the-melting-apartment-v0.1.0-8px-ninegrid.png)

融化公寓 v0.1.0 8px限定测试版；Fusion Pixel普通8px；原生双行18格，无10px。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：标题开场、手套箱取枪、后视镜留辞选项、辞职结局/制作人员返回开场；另一线取枪街道/START背包/装备提示/B返回。

提供者诊断路径：213唯一文本/1879字形逐像素原生LOAD_TEXT；海报、死亡和另两种结局场景诊断，非自然全路线。

保存边界：NO_EFFECTIVE_PROGRESS_SAVE_OR_COLD_READ_VERIFIED_SRAM_ALL_FF_IS_NOT_SUCCESS

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：另两种结局自然路线
- 未验证：全部自然死亡与分支事件组合
- 未验证：实机/闪存卡/长期稳定性
- 未验证：有效进度保存与冷读
- 未验证：所有引擎保存消费者不可达尚未证明
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

