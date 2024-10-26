![](https://img.shields.io/github/languages/code-size/DSPBluePrints/MechaBluePrints?style=for-the-badge)
![](https://img.shields.io/github/last-commit/DSPBluePrints/MechaBluePrints?style=for-the-badge)

# 戴森球计划 机甲蓝图 | Dyson Sphere Program Mecha Blueprints

## 简介 | Introduction

> 这是游戏[戴森球计划](https://store.steampowered.com/app/1366540/_/)中的蓝图仓库，用于储存与分享来自社区的机甲蓝图 <br> This is the blueprint warehouse in the game [Dyson Sphere Program](https://store.steampowered.com/app/1366540/_/), which is used to store and share mecha blueprints from the community

---

## 蓝图仓库使用方法 | How to use the blueprint warehouse

> 蓝图仓库已集成Git与自动更新脚本，无需任何基础也可以正常使用 <br>
The blueprint warehouse has integrated Git and automatic update scripts, which can be used normally without any foundation

### 第一次下载 | First Download

1. 在电脑上打开github上的蓝图仓库主页: `https://github.com/DSPBluePrints/MechaBluePrints` <br> Open the blueprint warehouse homepage on github on your computer: `https://github.com/DSPBluePrints/MechaBluePrints`
2. 从这个页面->[**Releases**](https://github.com/DSPBluePrints/MechaBluePrints/releases)<-，下载最新的蓝图包，文件名应该叫`MechBluePrints_X.Y.Z.7z`，请**不要**从绿色的Code处下载，那样文件不！完！整！<br> From this page -> [**Releases**](https://github.com/DSPBluePrints/MechaBluePrints/releases), download the latest blueprint package, the file name should be called `MechaBluePrints_X.Y.Z.7z`, please **do not** download from the green Code, **as this does not include all files**!
3. 解压后，放入游戏的默认机甲蓝图文件夹。放进去以后应该是这样：`C:\Users\％用户名称％\Documents\Dyson Sphere Program\Customize\Mecha\MechaBluePrints\README.md` <br> After decompression, put it into the game's default Mecha blueprint folder. After putting it in, it should look like this: `C:\Users\%username%\Documents\Dyson Sphere Program\Customize\Mecha\MechaBluePrints\README.md`

### 更新 | Update

1. 只需双击即可：`update.bat` | Run `update.bat`

> Q: 为什么我打不开蓝图仓库主页 / 下载特别慢 / 更新特别慢？<br> Why can't I open the homepage of the blueprint warehouse / the download is very slow / the update is very slow?<br>
> A: 通常是网络问题。蓝图仓库被托管在github上，可以通过在[Watt Toolkit](https://steampp.net)(原名steam++)中开启github加速服务解决。~~或者魔法？~~ <br> Usually it is a network problem. The blueprint repository is hosted on github, which can be solved by enabling the github acceleration service in Watt Toolkit (formerly known as steam++). ~~Or magic?~~

<!--

### 以下内容已过时，出于信息完整性考虑暂不删除，但是已经隐藏 | The following content is outdated and will not be deleted for information integrity, but has been hidden

### 视频教程 | Video Tutorial

内容同下方的文字教程，视频时长约1.5min <br> The content is the same as the text tutorial below, and the video duration is about 1.5 minutes
https://www.bilibili.com/video/bv1RK411Z7b2

---

### 文字教程 | Text Tutorial

#### 基础用法 | Basic Usage

您可以直接进入[蓝图仓库的网页](https://github.com/DSPBluePrints/MechaBluePrints)，寻找并打开自己需要的蓝图文件，点击位于蓝图代码右上方的**全选复制**(Copy raw contents). 
然后进入游戏，在蓝图页面依次点击**新建空蓝图**，**粘贴**，**保存更改**，就可以将蓝图代码保存到本地，像平常那样使用。<br>
You can go directly to the [Blueprint Warehouse Webpage](https://github.com/DSPBluePrints/MechaBluePrints), find and open the blueprint file you need, and click **Select All**(Copy raw contents).
Then enter the game, click **New Empty Blueprint** on the blueprint page, **Paste**, **Save Changes**, you can save the blueprint code locally and use it as usual.

> 常见问题：| Common Problem:
> Q: 为什么蓝图仓库网页打开特别慢，我该怎么办？<br> Why is the blueprint warehouse web page very slow to open, what should I do?
> A: 蓝图仓库被托管在github上，可以通过在[Watt Toolkit](https://steampp.net)(原名steam++)中开启github加速服务解决。~~或者魔法？~~ <br> The blueprint repository is hosted on github, which can be resolved by enabling the github acceleration service in [Watt Toolkit](https://steampp.net) (formerly known as steam++). ~~Or magic?~~  ~~only china~~

#### 进阶用法 | Advanced Usage

如果您有[Git](https://git-scm.com/)的使用基础，**可以将整个蓝图仓库用`clone`命令拉取到游戏的蓝图文件夹内**。这样您将以蓝图合集的形式将完整的蓝图仓库下载到本地，并且可以在游戏内直接访问，享受在线蓝图仓库与游戏无缝衔接的体验。<br> If you have a foundation of [Git](https://git-scm.com/), **you can use the `clone` command to pull the entire blueprint warehouse into the blueprint folder of the game**. In this way, you will download the complete blueprint warehouse locally in the form of a blueprint collection, and you can directly access it in the game, enjoying the seamless connection between the online blueprint warehouse and the game.

```cmd
git clone https://github.com/DSPBluePrints/MechaBluePrints.git
```

> 常见问题: | Common Problem:
> Q: `error: SSL_read` 相关  <br> `error: SSL_read` Relevant
> A: 通常是网络波动，重试即可。如果已经排除网络问题可以搜索 `git SSL_read` 并逐一排查错误原因，此处不再赘述 <br> Usually the network fluctuates, just try again. If the network problem has been ruled out, you can search `git SSL_read` and troubleshoot the cause of the error one by one, so I won’t go into details here

除非你真的非常清楚你正在做什么，否则请不要手动修改`.git`文件夹内的任何文件，这可能导致以后的自动更新出错  <br> Unless you really know what you are doing, please do not manually modify any files in the `.git` folder, which may cause errors in future automatic updates

可以通过`pull`命令进行对本地蓝图文件夹进行更新。Git将自动检查上次更新以来发生变动的蓝图/蓝图合集，并以增量更新的形式更新本地仓库  
**或者直接双击仓库根目录下的"双击更新蓝图仓库.bat"** <br> The local blueprint folder can be updated through the `pull` command. Git will automatically check for blueprints/blueprint collections that have changed since the last update, and update the local warehouse in the form of incremental updates
**Or directly double-click "Double-click to update blueprint update.bat" in the root directory of the warehouse** 

```cmd
git pull origin main
```
-->

## 协议 | license

1. 如果蓝图作者对自己的蓝图发布使用协议，则自从使用协议发布起，对相关蓝图使用蓝图作者发布的使用协议。<br> If the blueprint author publishes a usage agreement for his own blueprint, the usage agreement published by the blueprint author will be used for the relevant blueprint since the usage agreement is published.
2. 若无特殊声明，蓝图仓库内的一切蓝图及其他文件使用默认协议：**知识共享 署名-非商业性使用-相同方式共享 4.0 国际(CC BY-NC-SA 4.0)**。<br> Unless otherwise stated, all blueprints and other files in the blueprint warehouse use the default license: **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.
