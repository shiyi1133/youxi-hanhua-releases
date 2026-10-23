# 沙加2 DX v0.1.3（限定测试版）

[公开反馈](feedback.md) · [报告BUG](https://github.com/shiyi1133/youxi-hanhua-releases/issues/new?template=bug_report.md)

[公开源码与补丁Release](https://github.com/shiyi1133/youxi-hanhua-releases/releases/tag/saga-2-dx-v0.1.3)

原游戏／实际输入：Final Fantasy Legend II DX (user-provided English color modified edition)

原输入完整SHA-256：`3330a0c9187afe8b9a9f33b5975880f9e965f5e5bfa6944e89b4b69f937c40a2`（524288字节）。

## v0.1.3 8px music

字号范围：普通对白/菜单/取名/战斗为原生8px；标题为独立静态字图。

目标完整SHA-256：`88b264e5dd1f8a079a3d6230b96600e1e9bebf0b10d0404e1165f1a52266523f`（524288字节）。

补丁：`SaGa2-DX-zh-v0.1.3-8px-music.ips`；完整SHA-256 `4d28b8ef2a1d372d964a09d8a131d335c4e17f1663fedec617e28650578d0a4b`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-source-public-r01.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-patches-public.zip)

![最终ROM对应实际九宫格](screenshots/saga-2-dx-v0.1.3-8px-music-nine-grid.png)

v0.1.3 普通8px最终CGB九格；两格缺独立单帧，按提供方最终ROM绑定记录。

## v0.1.3 8x12 music

字号范围：仅普通对白原生8×12并上移4px；菜单、取名、战斗和密集UI保持原生8px；本次九宫格未展示8×12对白。

目标完整SHA-256：`fb86988cf60391f188ee9c0b4b8e8bc0e52d7c8c4e60e0d0c42762b2e1bc755f`（524288字节）。

补丁：`SaGa2-DX-zh-v0.1.3-8x12-music.ips`；完整SHA-256 `f9dae0a96811286ac5e3e85acb366301223d3a7c21e1459609a2d45f65790da6`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-source-public-r01.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-patches-public.zip)

![最终ROM对应实际九宫格](screenshots/saga-2-dx-v0.1.3-8x12-music-nine-grid.png)

v0.1.3 对白8×12版最终CGB九格，图中菜单、取名和战斗仍原生8px；未展示8×12对白；两格缺独立单帧，按提供方最终ROM绑定记录。

## v0.1.3 8px no-music

字号范围：普通对白/菜单/取名/战斗为原生8px；标题为独立静态字图。

目标完整SHA-256：`e38d72610fa5ed6eb754e4f7c67e1f0689b9d8520fabd451c35b9d8eb755797b`（524288字节）。

补丁：`SaGa2-DX-zh-v0.1.3-8px-nomusic.ips`；完整SHA-256 `b505c14d28984f0fb6f7763660d9f9915d86ddbce83844714d6edaa663fff864`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-source-public-r01.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-patches-public.zip)

![最终ROM对应实际九宫格](screenshots/saga-2-dx-v0.1.3-8px-nomusic-nine-grid.png)

v0.1.3 普通8px最终CGB九格；两格缺独立单帧，按提供方最终ROM绑定记录。

## v0.1.3 8x12 no-music

字号范围：仅普通对白原生8×12并上移4px；菜单、取名、战斗和密集UI保持原生8px；本次九宫格未展示8×12对白。

目标完整SHA-256：`99369f30e5c17a562e0ba2cd4f8bd3486c9862eb87b00c67edfa38c3b645270d`（524288字节）。

补丁：`SaGa2-DX-zh-v0.1.3-8x12-nomusic.ips`；完整SHA-256 `5afccc52f8259b1cb012b1c356eb0f175749370550346815c7b9f95bf9b9738d`。

[源码（完整性未独立确认）](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-source-public-r01.zip) · [补丁包](https://github.com/shiyi1133/youxi-hanhua-releases/releases/download/saga-2-dx-v0.1.3/saga-2-dx-v0.1.3-patches-public.zip)

![最终ROM对应实际九宫格](screenshots/saga-2-dx-v0.1.3-8x12-nomusic-nine-grid.png)

v0.1.3 对白8×12版最终CGB九格，图中菜单、取名和战斗仍原生8px；未展示8×12对白；两格缺独立单帧，按提供方最终ROM绑定记录。

## 范围与限制

- v0.1.3针对v0.1.2菜单反复开关死机；四变体各仅改变30字节，位于两处菜单临界区调用/IE掩码包装与校验和，字体和音频驱动未变。
- 提供方四个最终ROM各600次START/B循环，并测自然取名/重复字/删除重填、早期战斗、进度保存和新进程冷读；不是玩家特定存档、完整流程或实机验收。
- 四张九宫格分别7/9格与原生单帧像素相符；第7/8格缺独立原生PNG，仅保留提供方对应最终ROM声明，不称9/9独立核验。
- 8×12版九宫格所示菜单、取名、战斗仍为8px；未展示8×12对白，不以缩放替代大字取证。
- Issue #68音乐卡顿不属本次菜单死机修复，保持开放；神明乱码、宙斯变身等未验收。
- 维护未执行附件源码、未重建、未新增ROM运行、听感测试、全通或实机验收；源码完整性保持未独立确认。

源码完整性未独立确认；维护源码执行、重建、ROM新增运行均未执行。

大字版更容易出现拖慢、刷新残留等问题，遇到请及时在原楼反馈。

[此前完整版本记录](history/readme-a8b54d0c0eb2b524f700.md)。
