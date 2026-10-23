# 魔法骑士雷阿斯2：遗失的色彩 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/magic-knight-rayearth-2-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Magic Knight Rayearth 2nd. - The Missing Colors (Japan) (SGB Enhanced)

原输入完整SHA-256：`ffeb6c8433f8d2bacceb833ec33d146ca0c2ddcd5980c2839a9c5416516c2c71`（262144字节）。

范围：347剧情/349UI字段、固定人物/物品魔法敌名/保存/声音/credits职务/标题；未知深入口不冒全可达

## 8px v0.1.0

字号范围：普通8px；标题位图，无10px，保256KiB/MBC2与原SGB标记

目标完整SHA-256：`ee00aa86c4a59ed79629dad9ea6adfb61f7aec3fe664d44fabf5c22b1d7863fe`（262144字节）。

补丁：`魔法骑士雷阿斯2_v0.1.0_普通8px.bps`，SHA-256 `65e427c29830952376e31e4012e55600dc831fd810ea0004654f4893307eed03`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/magic-knight-rayearth-2-v0.1.0/magic-knight-rayearth-2-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/magic-knight-rayearth-2-v0.1.0/magic-knight-rayearth-2-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/magic-knight-rayearth-2-v0.1.0-8px-ninegrid.png)

魔法骑士雷阿斯2：遗失的色彩 v0.1.0 8px限定测试版；普通8px；标题位图，无10px，保256KiB/MBC2与原SGB标记 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：开场/出神殿/随机战斗并胜利10经验、风HP110→95；主菜单/状态/魔法/空物品/摩可拿/SELECT帮助；诊断调用保存菜单后实际按键保存自然战斗进度，新OS进程原生Continue冷读；同电池原日版冷读24B进度一致

提供者诊断路径：保存菜单入口诊断，非自然找到保存NPC；取消/同值覆盖/第二槽写入，不称第二槽完整冷读；347剧情逐段原生renderer诊断并续接，非自然所有事件；18物品内存夹具列表和SELECT说明、声音/credits入口诊断；945glyph/native与11数字OBJ CPU像素、有限WRAM/栈观测

保存边界：保持MBC2 512×4bit，mGBA外部packed256B，不按容量裁剪别的模拟器格式；一个自然战斗进度电池与原日版冷读样本非全部旧档保证

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：自然保存NPC/商店/后期物品事件
- 未验证：全最长数值/失败死亡路线/全通
- 未验证：实机/其它模拟器/DMG完整回归
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

