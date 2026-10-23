# 宝可梦 灵魂水晶42.0 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/pokemon-soul-crystal-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Pokemon Soul Crystal 42.0 (provider-declared English modification)

原输入完整SHA-256：`75625593baeb55241379ecc410fdf65372ef6753a0902e785cb1e52a66b62dc9`（2097152字节）。

范围：普通8px限定测试版；基于提供者英文改版Soul Crystal 42.0，非零售原版。开局、命名、菜单、野战及部分图形标签已有提供者运行证据；商店和图鉴取自既有实际进度，最长变量分页取自诊断入口。

## 8px v0.1.0

字号范围：Fusion Pixel 2026.09.25 真实普通8px，原生8px字格；无10px大字版，CGB原生彩色，非SGB验收。

目标完整SHA-256：`1dec06b6e1f41be705fe3066d360c1d9b701b8f6593b8998db1e28289c36f26a`（2097152字节）。

补丁：`pokemon-soul-crystal-v0.1.0-8px.bps`，SHA-256 `1d618f0f5cfb8fde9303c61df5566104e98c17f5fdcc09ced8ace33eb1bd092c`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/pokemon-soul-crystal-v0.1.0/pokemon-soul-crystal-v0.1.0-8px-SOURCE-public.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/pokemon-soul-crystal-v0.1.0/pokemon-soul-crystal-v0.1.0-8px-PATCH.zip)

![最终ROM对应实际九宫格](screenshots/pokemon-soul-crystal-v0.1.0-8px-nine-grid-8px.png)

v0.1.0 普通8px最终ROM真实九宫格。1—5格：标题、自然命名、开场、伙伴状态、野战；6—7格：既有实际进度商店与正常保存后新进程电池SAV冷读；8格：既有图鉴进度的正常菜单；9格：诊断入口最长255变量分页。原生160×144逐格像素核对，不是自然深层或全流程验收。

## 测试及限制

提供者自然路径：提供者自然新开局、时钟与命名、开场、领取伙伴、状态页、野生战斗；商店购买/卖出和图鉴菜单使用既有实际进度SAV，不能说新开局已经走到这些场景。

提供者诊断路径：九宫格第9格为诊断入口的最长255变量分页夹具；箱名、改名师及片尾原生初始化等诊断结果不称自然到达或自然深层验收。

保存边界：MBC3/RTC/32KiB SRAM与2MiB ROM容量不改。提供者记录正常SAVE、覆盖取消与新OS进程仅电池SAV冷读；商店资金3000→2700→2850。维护本次未重新运行ROM，不以复制SAV推定实际载入成功。

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 已知输入限制：中文输入页仅45字，玩家/劲敌字段最多3汉字加1ASCII；邮件仍使用原生字母符号
- 未验证：全流程通关、自然片尾和所有地图/道具/图鉴/深层Mega场景
- 未验证：实机、全部跨模拟器兼容及全部存档路径
- 未验证：真实联机、红外、打印机、移动通信及RTC长期漂移
- 未验证：维护独立源码重建、源码语义完整性与独立人员QA
- 未验证：外来或别版SAV、自定义旧昵称及旧存档兼容未穷尽；建议新开档并先备份电池存档
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

