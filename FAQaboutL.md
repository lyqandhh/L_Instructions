# 关于 **L: TRCN** 的常见问题

## 我可以更换字体吗? 如何更换?

### 使用 `.ttf` 字体文件作为游戏界面字体

* 下载 `.ttf` 字体文件后, 放到 `L.exe` 存在的目录 (即Terraria游戏目录, [安装教程][1]提到过)
![解压后文件][2]

* 此时打开游戏即可发现游戏界面字体已经更改. 完毕.

**注意: 文件夹下字体文件只能有一个, 才会生效.**

### 使用已经在系统安装的字体作为游戏界面字体

*注意: 下面操作涉及注册表操作, 请没自信或不懂的朋友略过. 官方的TRCN安装助手以后会放出下载, 可以使用这个软件修改字体..*

* 打开注册表编辑器 (`Regedit.exe`)

* 依次进入以下路径 `HKEY_CURRENT_USER\Software\Terraria`

* 修改 `Font` 项为你想要的字体名称. 完毕.
![修改注册表项][3]

**注意: 游戏目录下不能存在字体文件, TRCN才会读取系统字体.**

## 我可以用Steam启动Terraria汉化版吗?

* 游戏目录下重命名 `Terraria.exe` 为 `Terraria.exe.bak`

* 重命名 `L.exe` 至 `Terraria.exe`

* *(可选)* 打开主界面后, 打开**快速**选项. (详细界面教程在[这里][4])


[1]: HowToInstall.md
[2]: https://raw.githubusercontent.com/mistzzt/L_Instructions/master/images/InstallL_3.png
[3]: https://raw.githubusercontent.com/mistzzt/L_Instructions/master/images/FAQaboutL_1.png
[4]: HowToUse.md