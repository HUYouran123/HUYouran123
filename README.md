# :octocat: 👋 Hi, I'm HUYouran

> 🎮 专注于 **Minecraft 便携版** 生态维护｜🛠️ 自建导航、收录、开服资料站
> 📌 个人 / 社区自发维护，**非官方项目，与 Mojang Studios / Microsoft 无关**

[![Stars](https://img.shields.io/github/stars/FirgtZhong/mcpenav?style=flat&logo=github)](https://github.com/FirgtZhong/mcpenav/stargazers)
[![Forks](https://img.shields.io/github/forks/FirgtZhong/mcpenav?style=flat&logo=github)](https://github.com/FirgtZhong/mcpenav/network/members)
[![Contributors](https://img.shields.io/github/contributors/FirgtZhong/mcpenav?style=flat&logo=github)](https://github.com/FirgtZhong/mcpenav/graphs/contributors)
[![Last commit](https://img.shields.io/github/last-commit/FirgtZhong/mcpenav?style=flat&logo=github)](https://github.com/FirgtZhong/mcpenav/commits/main)
[![Top language](https://img.shields.io/github/languages/top/FirgtZhong/mcpenav?style=flat&logo=github)](https://github.com/FirgtZhong/mcpenav)

[:globe_with_meridians: 主站](https://mcpenav.top/) · [:card_index_dividers: 收录站](https://mc.mcpenav.top/) · [:books: 核心站](https://pm.mcpenav.top/) · [:memo: 个人页](https://huyouran123.github.io/wz/)

---

## :wave: 我是谁

站是自己搭的，更新不快，但一直在。主要做 Minecraft 携带版 0.14 这一段的导航、收录和开服资料整理。

:warning: 不是官方，不运营任何被收录的服务器，不代收账号密码，也不代收涉及金钱的东西。收录只代表信息被登记，不代表推荐或认证。

---

## :card_index_dividers: 我维护的站点矩阵

| 🏷️ 标签 | 🔗 站点 | 📝 简介 |
| :--- | :--- | :--- |
| 🧭 导航站 | [mcpenav.top](https://mcpenav.top/) | 最早的 MCPE 0.14 综合导航：服务器入口、原版 / 流量端 / Bingo 客户端下载、友情链接。Cloudflare Pages 托管，更新较慢 |
| 📋 收录站 | [mc.mcpenav.top](https://mc.mcpenav.top/) | **MCPEMAP v2.0.0**，0.13～1.1，人工审核、免费收录。按版本 / 类型 / 状态 / 印象标签筛选，列表、排行、统计与在线数据以本站为准 |
| 📖 资料站 | [pm.mcpenav.top](https://pm.mcpenav.top/) | 0.14 便携版核心站：版本协议矩阵、服务端核心对照、配置字段、报错排查、运维手册、UDP 在线探测。开服包不预置演示条目，提交审核通过才出现 |

实时台数、浏览数、票数一律去站上看，这里不写死。

### :mag: 三站怎么分

- **找服玩** → `mc.mcpenav.top`
- **下客户端 / 翻老导航** → `mcpenav.top`
- **自己开一台** → `pm.mcpenav.top`

三个站内容不互相复制，也不共享后台。

---

## :package: 仓库与页面

| | 仓库 / 页面 | 说明 |
| :--- | :--- | :--- |
| :file_folder: | [`FirgtZhong/mcpenav`](https://github.com/FirgtZhong/mcpenav) | 主站源码，HTML / CSS / JavaScript，**简中 · 繁中 · English · Русский 四份 README** |
| :file_folder: | [`pm014/0.14-portable-cores`](https://github.com/pm014/0.14-portable-cores) | 核心站源码，PHP 7.4 / 8.x + JSON 存储，无数据库、无 Composer、无前端框架 |
| :page_facing_up: | [`huyouran123.github.io/wz`](https://huyouran123.github.io/wz/) | 把这份个人简介做成能直接打开的静态页，纯 HTML + CSS |
| :bust_in_silhouette: | [`github.com/HUYouran123`](https://github.com/HUYouran123) | 个人主页，这段 README 就渲染在这里 |

---

## :busts_in_silhouette: 协作伙伴

- <img src="https://github.com/FirgtZhong.png" width="18" align="top"> **[@FirgtZhong](https://github.com/FirgtZhong)** — 域名提供与稳定性保障
- <img src="https://github.com/ibukifuuko-arch.png" width="18" align="top"> **[@ibukifuuko-arch](https://github.com/ibukifuuko-arch)** — 技术支持，不定时维护

主站仓库还有一位贡献者 [@HUYouran123](https://github.com/HUYouran123)，80 commits、2 contributors，语言占比 HTML 61.1% / CSS 27.4% / JavaScript 11.5%。

---

## :pushpin: 几个口径（都写在站里了）

- :label: `0.14.x` 是**区间标签**，不自动展开成 0.14.0~0.14.3，也不推断或分配协议号
- :bar_chart: 协议号分两列：**服务端最低支持版本**（pmmp 表）和 **客户端正式版协议号**（Wiki 表），不互相代换
- :satellite: 在线状态来自 UDP / RakNet 的 Unconnected Ping，默认端口 19132，**只反映探测那一刻**；不以 TCP 连通性判在线
- :hammer_and_wrench: **网站本身的 PHP** 和 **2016 年 0.14 核心用的定制 PHP 二进制**不是一回事，别混
- :lock: 开服包按随机 ID + `.bin` 存储，走 `download.php` 下载，上传目录禁执行，不自动解压、不代跑

---

## :sparkles: 补充说明

- :books: 主站源码仓库提供四语 README；收录站前台可切 **简体中文 / 繁體中文 / English / Русский**；核心站目前只有深浅色切换
- :arrows_counterclockwise: 收录信息由网友提交并人工核对，可能滞后或变更，以服务器官方公告为准
- :coffee: 「请杯咖啡」完全自愿，不影响收录结果与排序
- :shield: 这里只列下面两个公开事务邮箱，其余联系方式、群号、备案号、后台地址都不放在个人主页

---

## :label: 技能标签

`Minecraft PE` `MCPE 0.14` `PHP` `HTML` `CSS` `JavaScript` `Java` `Cloudflare Pages` `GitHub Pages` `GitHub Actions` `JSON 存储` `UDP / RakNet` `版本协议矩阵` `服务器收录` `静态站点` `开源维护`

> 标签是范围说明，不是技能认证 :wink:

---

## :email: 联系

- 📧 收录申请 / 修改信息 / 申请下架 → [admin@hucx.cn](mailto:admin@hucx.cn)
- 💬 技术支持 → [ibuki_fuko@hucx.cn](mailto:ibuki_fuko@hucx.cn)

其余事项不在这里受理。

---

> 💡 *“慢慢来，把每一寸世界过成自己喜欢的样子。”*

:octocat: Rendered on GitHub · Minecraft 为 Mojang Studios 商标，与 Mojang Studios / Microsoft 无关联
