# 黄昏之血 · 手机同人网页小游戏

The Duskbloods Mobile Fan Game — 中文与英文可玩成品。

一个适合手机横屏游玩的单人动作小游戏：选择六名角色之一，在九个区域中战斗、收集强化、召唤眷属，经历三轮发育阶段，再挑战最终 Boss。

**非官方同人作品。** 角色名称与世界观引用 The Duskbloods；本项目与原作权利方无关联。游戏使用程序生成的画面与音效，没有附带官方美术或音频素材文件。

## 打开游戏

| 语言 | 成品文件 |
| --- | --- |
| 中文 | [index.html](index.html) |
| English | [en/index.html](en/index.html) |

每个 HTML 文件都包含完整的游戏程序和 Phaser 3.90.0 引擎，不依赖 CDN、外部素材或服务器接口。将文件下载到电脑，用浏览器打开即可游玩。GitHub 的文件展示页只展示代码；需要下载后打开，或由使用者放到静态网页托管服务。

手机建议通过 HTTP(S) 链接横屏打开；文件管理器对本地 HTML 的打开方式因系统而异。首次点击会尝试全屏并启用音效，全屏是否允许由浏览器决定。

仓库只收录中英文最终游戏、使用说明与许可证，不包含开发日志、补丁脚本、测试录屏、浏览器资料或历史版本。

## 手机操作

按住屏幕左侧移动，使用右下角的攻击、远程、闪避、吸血、嚎叫和血技按钮。系统自动瞄准最近的敌人。竖屏时显示旋转提示。

先攻击累积敌人韧性，破韧后吸血可造成伤害并回血。嚎叫可打断敌人蓄力、击落飞行物。

## 电脑操作

| 按键 | 操作 |
| --- | --- |
| WASD / 方向键 | 移动 |
| 鼠标 | 瞄准 |
| 鼠标左键 / J | 近战，按住连击 |
| 鼠标右键 / K | 远程，按住连射 |
| 空格 | 闪避 |
| Q / E | 嚎叫 / 吸血 |
| R / F | 血技一 / 血技二 |
| 1 / 2 / 3 | 三选一强化 |
| M / Esc | 静音 / 暂停返回 |

## 玩法

- 六名角色：阿尔伯特、「血手」杨、庄兰、狙击手莱拉、元老院萨米尔·帕特雷斯、卓克，各有不同武器与血技。
- 前三个阶段各 60 秒，用于打怪与成长；阶段切换时换区、恢复生命并刷新敌人。第四阶段挑战染血的沃尔瓦德。
- 地图包含大教堂、街区、大桥、下水道、中央城区、湖、森林、遗迹和时钟塔九个区域。
- 炼金炉提升武器，三选一强化与血袋盛宴提供成长；玩家最高 20 级。
- 可召唤双刀或火焰法师眷属，一局选择一种，眷属最高 5 级。

## English

Open [en/index.html](en/index.html) after downloading it, or serve it with any static web host. No installation or external asset downloads are required. On mobile, use landscape mode, the floating joystick on the left, and action buttons on the right. On desktop, use WASD/arrows, mouse aim, J/K for melee/ranged, Space to dodge, Q/E to howl/drain, and R/F for Blood Arts.

This is an unofficial fan game referencing The Duskbloods. Art and sound are generated procedurally. The original code is MIT licensed; third-party characters, names and setting are not licensed by this project.

## 许可与来源

原创代码采用 [MIT](LICENSE)，版权署名 Eladriel777；实现使用 AI 编程工具协作。随成品内嵌的 Phaser 3.90.0 使用其 [MIT 许可证](licenses/Phaser-MIT.txt)。角色、名称、标识与原作世界观的权利仍归相应权利方，MIT 不授予这些内容的权利。参见 [来源声明](NOTICE.md)。
