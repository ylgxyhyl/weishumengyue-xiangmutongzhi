# SOURCES.md - 资源来源登记清单

> **⚠️ 重要提示**
> 本文件是本项目「资源整合说明与声明」的必要附件。
> 使用、引用或分发本仓库任何内容前，请务必阅读本清单及对应的原始许可协议。
> **最后更新：** 2026-10-22 | **维护者：** [3130007694@qq.com]

## 一、字段说明
com
| 字段 | 必填 | 说明 |
| :--- | :--- | :--- |
| **类别** | ✅ | A=自研 / B=第三方开源 / C=爱好者自制 / D=官方素材 |
| **名称** | ✅ | 资源/组件的准确名称 |
| **来源地址** | ✅ | 原始仓库/发布页/下载链接（永久链接优先） |
| **作者/权利人** | ✅ | 原始创作者或版权持有方 |
| **允许再分发** | ✅ | ✅ 是 / ❌ 否 / ⚠️ 附条件（需注明条件） |
| **备注** | ❌ | 特殊限制、修改说明、兼容性警告等 |

## 二、资源登记清单

### A. 本项目自研内容

| 类别 | 名称 | 来源地址 | 作者/权利人 | 允许再分发 | 备注 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| A | 启动器与配置整合脚本 | 本仓库 `src/self/launcher/` | 本项目参与者 | ✅ | 仅含胶水代码，不含任何游戏资源 |
| A | 联机协议适配层 | 本仓库 `src/self/netcode/` | 本项目参与者 | ✅ | 独立编写，未复制官方网络协议代码 |
| A | 项目文档与声明汇编 | 本仓库 `docs/` | 本项目参与者 | ✅ | 可自由转载，需保留署名与相同方式共享 |

### B. 第三方开源组件

| 类别 | 名称 | 来源地址 | 作者/权利人 | 允许再分发 | 备注 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| B | Godot Engine | https://github.com/godotengine/godot/releases/tag/4.3-stable | Godot Contributors | ✅ | 运行时依赖，未修改引擎源码 |
| B | ENet | https://github.com/lsalzman/enet/releases/tag/v1.3.18 | Lee Salzman | ✅ | 用于联机底层通信 |
| B | Newtonsoft.Json | https://www.nuget.org/packages/Newtonsoft.Json/13.0.3 | James Newton-King | ✅ | 配置文件解析 |
| B | Noto Sans SC | https://github.com/notofonts/noto-cjk/releases/tag/Sans2.004 | Google / Adobe | ✅ | 字体文件置于 `assets/fonts/`，需保留OFL声明 |

### C. 爱好者自制资源

| 类别 | 名称 | 来源地址 | 作者/权利人 | 允许再分发 | 备注 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| C | Stronghold-Protocol (本体) | https://github.com/sganggs/Stronghold-Protocol | @哔哩哔哩—ausevay | ❌ | 项目核心框架；建议优先联系作者确认再分发许可 |
| C | Marisa's Mod Pack | https://github.com/Marisa-la/marisa-s-mod | @哔哩哔哩-海水有点咸_ (Marisa) | ❌ | 含罗德岛、结城理、鲲、sees、我们联合、怒潮凛冬(策略)等模组 |
| C | Stronghold-Protocol-XY (协议源石版) | https://github.com/hhyy2333/stronghold-protocol-xy | @哔哩哔哩-喵33是cjb (火燃于花) | ❌ | 独立分支版本 |
| C | Stronghold-Protocol Android | https://github.com/Paper-Yuan/Stronghold-Protocol | @哔哩哔哩-纸鸢安好 (纸鸢千机) | ❌ | 安卓端适配；含全皮、全语音、超限测试内容 |
| C | Rhodes-Kazdel Mod | https://github.com/yznx09/Stronghold-Protocol-Rhodes-Kazdel-Mod | @哔哩哔哩-伊佐那邪_ (伊佐那邪) | ❌ | 卫戍协议：盟约 · 罗德岛 / 卡兹戴尔盟约 Mod |
| C | Forge & Mods Repository | https://github.com/XiaMo233M/Stronghold-Protocol-Forge<br>https://github.com/XiaMo233M/Stronghold-Protocol-Forge-Mods | @哔哩哔哩-沫沐沐 (沫) | ❌ | Forge框架及Mods集合仓库（原链接粘连，已拆分） |
| C | 东盟约 Modpack | https://github.com/CLAPXO/-modpack/ | @哔哩哔哩-CLAPXO (东国区) | ❌ | 含干员：吉星、白雪、赤东、火龙S黑角、麒麟R夜刀 |
| C | Forge Full Pack | https://github.com/IncogniBox/stronghold-protocol-forge-full | @哔哩哔哩-不知名信箱 | ❌ | 含颂乐人偶、哥伦比亚、雷姆必拓、故事集前置、多索雷斯、职业分支扩展前置、全干员时装补充包、开发者功能扩展、数据显示 |
| C | 一服 危机合约 | 暂无 | @哔哩哔哩-是小狼崽口牙 | ❌ | 一服 危机合约 |
| C | 海克斯模组 十二服 |https://github.com/zwleternal2005/Stronghold-Protocol-Hex | @哔哩哔哩-Eternal千溟兮 | ❌ | 海克斯模组 十二服 |
| C | 四服 无限火力 | https://github.com/sganggs/Stronghold-Protocol | @哔哩哔哩-雨千代Chiyo | ❌ | 四服 无限火力 |
| C | 新经济玩法 六服 | https://dl.jiangjiangze.icu/ | @哔哩哔哩-jingjiangze | ❌| 新经济玩法六服 |
| C | 精英AI | https://github.com/HankDUMPLINGZhong/Stronghold-Protocol-AI | @哔哩哔哩-鬼街穿堂风 | ❌| 精英AI |
| C | 狩猎模拟 PVP | https://github.com/T1113047/Stronghold-Protocol-Hunt-Simulation | @哔哩哔哩-涂涂小第047 | ❌ | 狩猎模拟 PVP |
| C | 罗德岛盟约 | https://github.com/Stronghold-Protocol-Mod/Rhodes-Mod | @哔哩哔哩-暮池云_chiyun | ❌ | 罗德岛盟约 |
| C | 炸惊模拟 | https://github.com/nnmciak/stronghold-protocol-mod-zhajingmode | @哔哩哔哩-万い | ❌ | 炸惊模拟 |
| C | Mujica-Index MOD | 暂无 | @哔哩哔哩-Churtikkj | ❌ | Mujica-Index MOD |
| C | 危机合约 (Eibhlin) | 暂无 | @哔哩哔哩-Eibhlin_Selena | ❌ | 危机合约 |
| C | 罗德岛 调试模式 | 暂无 | @哔哩哔哩-典狱长二创典狱长拟人 | ❌ | 罗德岛 调试模式 |
| C | 安卓端+创意工坊 | 暂无 | @哔哩哔哩-Daisy_Theresa | ❌ | 安卓端+创意工坊 |
| C | 契约，肉鸽，13服 | https://1825905525.share.123pan.cn/123pan/9GBNJv-Cprx3?notoken=1&pwd=7999 | @哔哩哔哩-剑光卤煮-斩尽牛杂 | ❌ | 契约，肉鸽，13服 |

> **📌 致谢与遗漏声明**
> 以上名单不分先后，后续将随项目组人数增加持续更新。部分制作者因个人原因未列入，如有遗漏或信息更正，请通过 QQ: 3130007694 联系维护者，我们将及时补充。感谢所有为本项目付出努力的制作者！

### D. 官方素材（⚠️ 高风险类别）

| 类别 | 名称 | 来源地址 | 作者/权利人 | 允许再分发 | 备注 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| D | 角色立绘（测试用） | 用户自有客户端提取 | 上海鹰角网络 / Yostar | ❌ | **严禁再分发**；仅供本地运行验证；收到通知即刻删除 |
| D | UI界面切图（调试用） | 用户自有客户端提取 | 上海鹰角网络 / Yostar | ❌ | **严禁再分发**；同上 |
| D | 背景音乐（3首） | 用户自有客户端提取 | 上海鹰角网络 / Hypergryph | ❌ | **严禁再分发**；建议使用者替换为自制/免版税音乐 |
| D | 关卡数值配置表 | 用户自有客户端解包 | 上海鹰角网络 / Yostar | ❌ | **严禁再分发**；仅用于机制复现参考；本项目实际使用的是自行推导的重构配置 |

## 三、维护规范

1.  **新增必登**：任何新引入的第三方内容必须在合并/提交前完成登记，未登记的内容不得进入主分支。
2.  **变更同步**：来源更换、许可变更时，须在 24 小时内更新对应条目并在「备注」中标注变更日期。
3.  **移除留痕**：被移除的内容不直接删除行，而是将「允许再分发」改为 `🚫 已移除`，并在备注中注明移除日期与原因（如"权利人要求"/"许可冲突"），保留至少 6 个月以备追溯。
4.  **定期审计**：每月由维护者核查一次清单完整性，确保仓库实际内容与登记一致。
5.  **争议优先**：收到任何关于来源、署名或许可的异议，先按「存疑即下架」原则处理，核实后再恢复。

## 四、问题反馈

如发现本清单存在遗漏、错误或对某项内容的许可有疑问，请通过以下方式联系：
-   邮箱：3130007694@qq.com
-   原作者认领/更正：QQ 3130007694

我们将在 72 小时内核实并更新。
