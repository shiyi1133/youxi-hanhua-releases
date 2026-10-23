# 公主的任务 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/himes-quest-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Hime's Quest (World) (Digital) (Aftermarket) (Unl)

原输入完整SHA-256：`02bacba43892b372375d34ac56e060dca7f29111afacc94e541c33a34215e8f0`（2097152字节）。

范围：CGB-only aftermarket；253候选场景、1410槽中1386槽/940种正文已译，24原作者工具/数值图标控制串保留；9处图字改动，原艺术标题与品牌/按键缩写保留。

## 8px v0.1.0

字号范围：普通Fusion Pixel 8px；5tile窗口三行无不改布局的10px版。

目标完整SHA-256：`e64bcb72b2f81520e2866e180f87bd085fa1b19f80e60e6435f7037243637eda`（4194304字节）。

补丁：`himes-quest_v0.1.0_8px.bps`，SHA-256 `02d35ba41df84a408876fc1d2451e33c18e49fd919ca1803b0b2196269e7186a`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/himes-quest-v0.1.0/himes-quest-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/himes-quest-v0.1.0/himes-quest-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/himes-quest-v0.1.0-8px-ninegrid.png)

公主的任务 v0.1.0 8px限定测试版；普通Fusion Pixel 8px；5tile窗口三行无不改布局的10px版。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：新进程标题、新游戏取消/确认、物品栏10轮/地图5轮、离开动漫社进入城镇、NPC三页对白。

提供者诊断路径：28字体代表文本、价格货币0/32767/-32768、游戏结束/赌场/音乐/最终Boss场景仅加载。自然步行后显式切原狐仙雕像脚本，原生保存并新OS电池冷读；不是自然找到雕像或有效深进度验收。

保存边界：PROVIDER_SELFTEST_DIAGNOSTIC_NATIVE_SAVE_ENTRY_NEW_OS_COLD_READ_ONLY

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：自然雕像保存及有完成度深层存档
- 未验证：全部商店实际购买
- 未验证：完整战斗/死亡续关
- 未验证：所有支线结局和诅咒模式
- 未验证：实机
- 未验证：原版旧档兼容
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

