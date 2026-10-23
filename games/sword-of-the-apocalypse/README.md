# 末日之剑 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/sword-of-the-apocalypse-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Sword of the Apocalypse (user-provided GBC input)

原输入完整SHA-256：`376a1bb582e9391d34afe196e9939576a77586e985407763ca787d6ed3514a3d`（2097152字节）。

范围：389文本槽/268唯一译文、18背景文字组/10精灵文字组、剧情/物品对白/关卡/难度/音效/设置/清除提示；用户非零售认证基底，modified_base=null，不认证纯净零售版

## 8px v0.1.0

字号范围：普通原生8px对白菜单，少量标题图12px；无10px/大字正文

目标完整SHA-256：`2862a6e2b0eb14b7c0be39344e598340bb55fb45000673fecc1e3acf6a7c4a52`（4194304字节）。

补丁：`SwordOfTheApocalypse_zhCN_v0.1.0_8px.bps`，SHA-256 `b74328dcefa9d3439f213d5f977b44fb27d8724e521725769e40f2261330db9e`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/sword-of-the-apocalypse-v0.1.0/sword-of-the-apocalypse-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/sword-of-the-apocalypse-v0.1.0/sword-of-the-apocalypse-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/sword-of-the-apocalypse-v0.1.0-8px-ninegrid.png)

末日之剑 v0.1.0 8px限定测试版；普通原生8px对白菜单，少量标题图12px；无10px/大字正文 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：标题/难度/开场/首关NPC多段对白；移动跳跃攻击受伤/死亡复活/暂停B退出

提供者诊断路径：原生load_scene参数进入设置/完整开局/角色介绍/GameOver/自动存档；诊断菜单难度/曲目/清除取消及成功；已格式化RAM数字缓冲0/8/32767/-32768布局，不是printf全链路

保存边界：只有初始/设置电池导出后新进程启动，没有有进度存档冷读通过；未有意改格式不等于验证旧档兼容，勿跨SHA即时状态

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：首关通关/全路线深层/结局/全部角色自然解锁
- 未验证：真实有关卡进度的自然保存冷读
- 未验证：实机/联机
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

