# Notch VS 古振兴

一个由 AI 辅助制作的 **Minecraft Java Edition / Fabric** 娱乐向恶搞模组。

在游戏中召唤 **Notch** 与 **古振兴**：他们会闲逛，当两种角色靠近到一定距离时，就会开始对唱。还加入了音乐唱片与生存模式交易内容。

> 本项目为非官方娱乐作品，与 Mojang Studios、Microsoft 及相关人物没有官方关联。

## 版本与运行要求

| 项目 | 要求 |
| --- | --- |
| 模组版本 | **1.17.6** |
| Minecraft Java Edition | **26.2** |
| 模组加载器 | Fabric Loader **0.19.5 或更高** |
| Fabric API | **0.160.0 或更高**、适配 Minecraft 26.2 |
| Java | **25 或更高** |

**注意：本模组针对 Minecraft 26.2 制作，请勿直接安装到其他游戏版本。**

## 下载

下载入口：[Releases（版本发布页面）](https://github.com/abcdefg625911-max/notch-vs-/releases)。

**正式 JAR 仍待添加到 Releases 附件**。发布后请在相应版本的 **Assets** 下下载 `Notch-VS-Gu-v1.17.6.jar`，不要下载 GitHub 自动生成的 `Source code.zip` 或 `Source code.tar.gz`，那些不是能直接安装的模组。

Fabric API 需要另外下载，可从 [Modrinth 的 Fabric API 页面](https://modrinth.com/mod/fabric-api) 获取适配 26.2 的版本。

## 安装方法

1. 安装 **Minecraft Java 26.2** 以及对应的 [Fabric Loader](https://fabricmc.net/use/installer/)。
2. 确保运行环境满足 Java 25 要求。
3. 下载适配该游戏版本的 **Fabric API**。
4. 将 **Fabric API JAR** 和 **Notch VS 古振兴 JAR** 放入游戏实例的 `mods` 文件夹。
5. 移除旧版同名模组，避免重复安装；然后通过 Fabric 启动游戏。

如果玩联机，服务器和客户端都需要安装相应版本的模组和依赖。

## 怎么玩？

- 创造模式下，在刷怪蛋分类找到 **Notch 刷怪蛋**、**古振兴刷怪蛋**。
- 分别生成两名不同角色，距离在 **8 格以内**会触发对唱；分开后停止。
- 生存模式可以交易：向古振兴支付 **5 个绿宝石**换取一个「迷你世界代码」U 盘，再向 Notch 支付 **1 个迷你世界代码 + 8 个绿宝石**换取唱片。
- 用唱片机播放 **Notch VS 古振兴 唱片**，无需把两个人物放在附近。
- 原版村庄有小概率生成其中一名角色。

### 指令

```mcfunction
/notchvsgu
/give @s notchvsgu:notch_spawn_egg
/give @s notchvsgu:gu_zhenxing_spawn_egg
/give @s notchvsgu:mini_world_code
/give @s notchvsgu:music_disc_duet
```

## 其他说明

- 这是个人娱乐项目，部分内容由 AI 辅助制作。
- 本仓库当前主要用于**发布和提供安装说明**，不提供完整开发工程源码。
- 遇到问题可通过 GitHub **Issues** 反馈，请注明 Minecraft、Fabric Loader、Fabric API 和模组版本。
- 有关第三方模型、贴图、音频与素材来源的注意事项，参见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
- 请勿因为本仓库公开，就假设其中所有素材都属于可自由转载、改编或商用的内容。

## 发布校验

下载正式模组后，可以用 [RELEASE_NOTES_v1.17.6.md](RELEASE_NOTES_v1.17.6.md) 中的 SHA-256 校验值核对文件完整性。上传前仍建议在目标 Minecraft 客户端实测。
