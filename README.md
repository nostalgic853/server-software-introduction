# server-software-introduction

[![Tencent QQ](https://img.shields.io/badge/Tencent%23QQ-%2312B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)](https://jq.qq.com/?_wv=1027&k=i2MG7npf)

Minecraft 服务器核心介绍。<br>
本文皆在帮助你挑选一个合适的服务器核心用于你的服务器。<br>

*由于作者的习惯，本文会将"服务端"与"服务器核心"两个称呼混用，在这里指的是同一个意思。事实上这两个词也该指的是同一个意思。(服务端整合包指的才应该是一个配置好的服务器) 考虑到大部分读者的习惯，故在此说明。*

___另外，本文所说的 原版特性 与 BUG 是同一个东西。别和我开什么那是特性不是 BUG 的玩笑，如果你想说这种话，我建议你赶快关闭我的文章。___

## 前情提要

许多原版特性存在的原因是因为 Mojang 代码的执行效率过于低下导致可以被利用 (例如抑制光照更新，切地狱门) 如果你又想要原版特性有想要好优化那么我可以说 **这样的服务器核心不存在**。<br>

如果你是想开一个生电服务器，请使用 Fabric + Carpet + (可选) MCDR 或 vanilla + (可选) MCDR，具体是什么自己搜索，我不懂生电服。<br>
*(如你所见，我不懂生电服，所以上面那句话如果说错了请告诉我。)*

___顺带一提，你所看到的什么绿宝石印钞机，破基岩，TNT复制，刷沙子这些全是利用原版 BUG 实现的。别问任何人为什么不能用，因为你自己没选好服务端。___

## vanilla

**📋 简介** | 官方打造的原版核心。 *(vanilla 一词意为香草，故又称香草服务端)* 拥有所有原版特性。但是由于 Minecraft 臭名昭著的优化问题，官方服务端的优化必然是很差的。

**⚙️ 是否支持插件/模组** | 不支持插件，不支持模组。

**🛠️ 维护状态** | ✅

**❓ 原版特性** | 全部。

**🕹️ 适用的服务器类型** | 生电服务器与只是和几个朋友联机的服务器。

**🖊️ 作者评价** | 除了上面提到的那两种服务器类型，否则你最好别用。如果你要用，建议搭配较为优秀的硬件。

**✨ 推荐指数** | ⭐

## CraftBukkit

**📋 简介** | 插件服核心的开山鼻祖，最早拥有 Bukkit API 的核心。现已暂停新功能的开发，只在每个新的 Minecraft 版本发布时进行适配更新。*已经不支持大部分插件且性能极差。*

**⚙️ 是否支持插件/模组** | 支持插件，不支持模组。

**🛠️ 维护状态** | ✅

**❓ 原版特性** | 经过优化有削减但是仍然保留大部分。

**🕹️ 适用的服务器类型** | 没有。你还不如去用原版端，CraftBukkit 的插件兼容性约等于没有。

**🖊️ 作者评价** | 别用，不会适合你。

**✨ 推荐指数** | 完全不推荐。

## Spigot

**📋 简介** | 基于 CraftBukkit 打造并进一步优化的服务端，但是性能提升依旧十分小。 (与原版端几乎没差别) 现已暂停新功能的开发，只在每个新的 Minecraft 版本发布时进行适配更新。

**⚙️ 是否支持插件/模组** | 支持插件，不支持模组。

**🛠️ 维护状态** | ✅

**❓ 原版特性** | 经过优化有削减但是仍然保留大部分。

**🕹️ 适用的服务器类型** | 想用插件的生电服务器、只是和几个朋友联机的服务器。

**🖊️ 作者评价** | 除了上面提到的那两种服务器类型，否则你最好别用。如果你要用，建议搭配较为优秀的硬件。

**✨ 推荐指数** | 完全不推荐。

## Paper

**📋 简介** | 基于 Spigot 打造并进一步优化的服务端，获得了较为可观的性能提升。修复了很多原版特性，所以比较适合不那么注重于 **以游玩 BUG 为乐** 的服务器。且该服务端是目前稳定性最好的服务端。

**⚙️ 是否支持插件/模组** | 支持插件，不支持模组。

**🛠️ 维护状态** | ✅

**❓ 原版特性** | 几乎没有。

**🕹️ 适用的服务器类型** | 多人生存，建筑服务器。使用插件扩展原版玩法内容的服务器。高版本小游戏服务器。

**🖊️ 作者评价** | 目前稳定性最好的服务端，也是下文我要介绍的优化服务端的坚实的地基。不过因为稳定性，优化肯定不如下文要介绍的服务端好。

**✨ 推荐指数** | ⭐⭐⭐
