# 发掘 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/unearthed-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：发掘Unearthed (World) (v1.1) (2024 Version) (GB Compatible) (Aftermarket) (Unl).gbc

原输入完整SHA-256：`9c9741ab1e915ed772c463446f5907b3f7091815b361626fab34a0fb547955a0`（2097152字节）。

范围：用户World v1.1/2024 aftermarket输入；实际CGB-only，文件名GB Compatible不是DMG证据。1011译文、277候选场景、998文本消费者；272背景/310精灵审计，保留作者/商标/按键与隐藏开发注释，候选入口不等于自然可达。

## 8px v0.1.0

字号范围：普通Fusion Pixel 8px；无10px。

目标完整SHA-256：`b4f832916ae161fad945be6bf793f42b433ce776850806ad82fd2ef04f177366`（4194304字节）。

补丁：`unearthed_zh_v0.1.0_8px.bps`，SHA-256 `26e0d67ba36ebfdda2ecca8faee7b0b89fc28298fa09d48210b266a1bce198b8`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/unearthed-v0.1.0/unearthed-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/unearthed-v0.1.0/unearthed-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/unearthed-v0.1.0-8px-ninegrid.png)

发掘 v0.1.0 8px限定测试版；普通Fusion Pixel 8px；无10px。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：开场教程、地上地下切换、推箱/矿石/机甲、暂停返回；首关23步成绩及地图解锁，正常电池保存，新OS进程继续恢复地图。

提供者诊断路径：1011译文原UI拷贝、变量最大值、VRAM/缓冲与银行恢复；深图像LoadScene诊断，包括绕过原初始化的遗留scene100，不冒自然到达。

保存边界：PROVIDER_SELFTEST_FIRST_CLEAR_23_MOVES_UNLOCKED_MAP_NEW_OS_COLD_READ

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：全剧情自然流程
- 未验证：全部谜题和结局
- 未验证：实机
- 未验证：所有旧存档和即时状态兼容
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

