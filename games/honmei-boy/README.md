# 本命赛马 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/honmei-boy-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Honmei Boy (Japan)

原输入完整SHA-256：`b1fbb2ea6bb711c9b99a8b13f9a179ed273425e8aaa67ef1f3a95acfc138a948`（262144字节）。

范围：赛马资料录入/修改/删除/预测工具；十赛场、四档、赔率/草沙成绩/跑法/保存/三种预测方法、标题副标/计算等待图片；不是操作赛马奔跑的动作游戏

## 12px v0.1.0

字号范围：真实Fusion12px位于原生16×16单元；密集列表/小字8px；不是16px字形或独立大字版，无10px

目标完整SHA-256：`cf454fb16f1cba50c7369dbf1ad0bb298b5bfc64287eb32d3aedcf42081479a4`（524288字节）。

补丁：`honmei-boy-v0.1.0-12px.bps`，SHA-256 `7a3ce4c5069f5597bc0e7bbfb3f926e72b87d05ace59d1285f81d5df2bd1af0f`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/honmei-boy-v0.1.0/honmei-boy-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/honmei-boy-v0.1.0/honmei-boy-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/honmei-boy-v0.1.0-12px-ninegrid.png)

本命赛马 v0.1.0 12px限定测试版；真实Fusion12px位于原生16×16单元；密集列表/小字8px；不是16px字形或独立大字版，无10px 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：快速与数据预测；5/8/18匹、3900距离/沙地/999.9赔率；8匹非零资料保存；读取/覆盖/B及否取消/删除后新进程仅读电池冷读；三种预测结果，DMG灰阶与强制SGB模型画面

提供者诊断路径：未使用诊断入口；仅限所列自然路径。

保存边界：原生8KiB电池记录；同自然输入原版/汉化电池逐字节相同属提供方记录，未承诺全部旧档/损坏档或所有模拟器；即时状态不可跨ROM

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：实机
- 未验证：全部资料组合/中断相位
- 未验证：音频听感对照
- 未验证：预测统计或现实赛果准确性
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

- 已核对说明更正：README称输入SGB头标志03错误：权威输入与目标的0x146实际均00。提供方强制SGB模式出现mGBA默认边框，不是原生SGB增强/自定义彩色。发布说明须明确纠正此项。
