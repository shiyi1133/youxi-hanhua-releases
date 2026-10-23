# 阿蕾莎 v0.1.0（限定测试版）

[源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/aretha-v0.1.0) · [公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

原游戏／实际输入：Aretha (Japan)

原输入完整SHA-256：`b9bb5b4d3274a7f4c443bd8fb2bf5f1018358d76a54c01e3a53f7ff610fa4fa6`（131072字节）。

范围：18脚本表1056对白字段、253物品地点标签、127敌名、114固定UI；原事件控制保留。PERA/旅馆/提款机图字已处理；原品牌、作者名及不再调用的遗留词典保留。

## 8px v0.1.0

字号范围：Fusion Pixel普通8px；无10px。

目标完整SHA-256：`e4a181529addc2b1a2f051449892ebeb3c0f342e205e6c6db304c8f442ddb1cb`（262144字节）。

补丁：`阿蕾莎_v0.1.0_普通8px.ips`，SHA-256 `eb5d2f450769ee61263dfd947ce380c7037b165f8fd98c2884b243e364f9f67c`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/aretha-v0.1.0/aretha-v0.1.0-source-public-r02.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/aretha-v0.1.0/aretha-v0.1.0-patch.zip)

![最终ROM对应实际九宫格](screenshots/aretha-v0.1.0-8px-ninegrid.png)

阿蕾莎 v0.1.0 8px限定测试版；Fusion Pixel普通8px；无10px。 自然路径与诊断范围见测试说明，不代表全流程。

## 测试及限制

提供者自然路径：开场城镇、提款机条件借款10000、商店确认购买10000→2000、装备、第一角色杨咩咩重复咩删除重输、正常保存/新OS进程电池冷读、自然出城战斗攻击/胜利、宝箱、旅馆及败北返回标题。

提供者诊断路径：静态18列检查仅按NAME6字/BUFFER10字预算；字体和缓存/栈观测均限所跑路径，不是全代码证明。

保存边界：PROVIDER_SELFTEST_MEANINGFUL_NATIVE_SAVE_NEW_OS_COLD_READ

同一实现者自测，不是独立人员QA；维护未新增ROM运行或源码重建，未宣称实机或完整通关。

- 未验证：第二三角色自然加入后的命名保存
- 未验证：全部法术装备/深层事件
- 未验证：所有最长变量与页末组合
- 未验证：全流程和实机
- 未验证：旧日文姓名及所有历史档兼容
- 未验证：10px未制作
- 核对补丁还原、资产完整SHA和截图字节不等于全部游戏功能验收。

