# 阿蕾莎3 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/aretha-3-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Aretha III (Japan)

原输入完整SHA-256：`f7311a0a392183697b06b72929e480eaf11e856d44b9b218641465cfc4b29942`（262144字节）。

范围：1134去重语义对白/1458物理字段、249物品技能地名、253敌人NPC、142界面和12选项已处理；已知固定PERA图字已译，尚未逐项解码全部压缩和深层图像，不能称全图像完成。

## 8px v0.1.0

字号范围：Fusion Pixel原生普通8px；无10px。

目标完整SHA-256：`f672d22b0e685e26afa650cf52966be5e29dcf6e0855b242705f07c09848024a`（524288字节）。

补丁：`Aretha3_v0.1.0_8px.ips`，SHA-256 `4f6f06b7ad5d35077d58d804a2331482cd04065482dbb2534ac8ca5884a6c5b8`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/aretha-3-v0.1.0/aretha-3-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/aretha-3-v0.1.0/aretha-3-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/aretha-3-v0.1.0-8px-ninegrid.png)

阿蕾莎3 v0.1.0 8px限定测试版；Fusion Pixel原生普通8px；无10px。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：开场、SELECT主菜单、第一角色自然输入杨咩咩/重复咩/删除重输、正常保存和新OS进程仅电池读回、属性显示。

提供者诊断路径：原生事件入口显式设置后的战斗命令/伤害/死亡返回标题再读档，商店买卖/取消；1634字缓存、249词条居中和名称边界诊断。不能称自然遇敌、自然到店或战斗胜利。

保存边界：PROVIDER_SELFTEST_PRIMARY_NAME_AND_NATIVE_SAVE_NEW_OS_COLD_READ

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：全部伙伴命名
- 未验证：商店交易后保存冷读
- 未验证：跨FE片段最长变量
- 未验证：所有NL纯排版与否
- 未验证：所有嵌套窗口及深层图像
- 未验证：运行时自动换行兜底未新增
- 未验证：全流程和实机
- 未验证：原版或旧即时状态兼容
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

