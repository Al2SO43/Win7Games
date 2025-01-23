简体中文 | [English](./File_archiving/README_en_US.md)
--------

Win7Games语言精简版（支持使用Wine运行）
========
Win7Games语言精简版（仅保留英文（en_US）和简体中文（zh_CN）语言版本），并支持在Linux下使用Wine运行它们！

我该如何运行它们？
==========
1. 下载文件：
- 如果你安装了Git，那么你可以直接运行以下命令克隆本仓库：
```
git clone https://github.com/Al2SO43/Win7Games.git
```
- 如果你没有安装Git，你可以点击本仓库的“Code”按钮，然后选择“Download ZIP”下载本仓库文件。
- 你也可以在本仓库的Releases页面下载对应的压缩包，然后解压缩到一个指定目录并打开！

2.运行游戏：
- 如果您使用Windows系统：
  1. 您可以直接运行游戏对应的exe可执行文件，然后开始玩游戏。
  2. 如果出现一些问题，那么请查看下文的“常见问题说明”部分。

- 如果您使用Linux系统：
  1. 确保您已经安装了Wine并已经配置好环境（您可以自行搜索安装教程）。
  2. 安装一些必要的字体（尤其是使用简体中文语言的游戏版本，本仓库已经预先准备了一些简体中文字体，将其安装即可），否则可能会造成一些文字显示错误或不显示问题。
  3. 确保已经安装了Winetricks（您可以自行搜索安装教程）。 
  4. 在Winetricks中安装wmp11（Windows Media Player）或者在终端执行以下命令来安装Windows Media Player：```winetricks -q wmp11```
  5. 打开终端，切换到游戏目录，使用wine运行游戏的对应exe文件。
  6. 如果出现一些问题，那么请查看下文的“常见问题说明”部分。

常见问题说明与特别鸣谢
========
1. 常见问题说明：
   - Windows：为什么我点击游戏exe可执行文件后，没有任何反应？
     1. 请尝试对游戏进行调整，右键游戏exe可执行文件，选择“属性”，然后在“兼容性”选项卡进行调整。
     2. 如果仍然无法运行，那么请尝试直接安装原版Win7GamesForWindows版本（未精简版），[点击此处前往对应网址](https://win7games.com/)。
   - Linux Wine：为什么我在Wine环境下运行游戏时，字体显示异常？
     1. 请尝试安装更多您所用的语言的相关字体，这可能会解决问题。
     2. 如果仍未解决，那么请尝试运行英文精简语言版本的游戏。
   - Linux Wine：为什么我的游戏没有声音？
     1. 由于一些问题，现版本的游戏无法播放这些游戏音效，只有少部分的游戏可以播放自己的音效。如果您有更好的解决办法，欢迎联系本仓库管理者！
   - Linux Wine：为什么我的游戏无法自由的控制窗口大小（尤其是当我更改窗口大小时，游戏卡死）？
     1. 由于一些问题，现版本的游戏无法自由的控制窗口大小，但有一些时候是可以的。如果您有更好的解决办法，欢迎联系本仓库管理者！
   - Linux Wine：为什么我的游戏在一些场景很卡？
     1. 由于一些问题，现版本的游戏在一些场景下可能出现画面卡顿（尤其在国际象棋最为明显），您可以选择适当的降低画面效果。如果您有更好的解决办法，欢迎联系本仓库管理者！
   - Linux Wine：为什么我的游戏无法运行，总是弹出大量报错？
     1. 请尝试更换一个wine版本或安装更多可能使用的依赖项目。如果不能解决问题，您可以自行搜索解决办法。
   - Deepin/UOS：为什么统信Windows兼容引擎无法运行这些游戏？
     1. 由于一些问题，此游戏确实无法直接在此环境运行。但您可以通过部署Wine环境或者在Deepin/UOS的应用商店搜索安装Wine运行器来运行这些游戏。
   - 关于本项目：为什么没有更多语言的精简版了？
     1. 由于仓库管理者精力有限，目前只能手动做出英文和简体中文的精简版。如果您希望自己制作更多语言的相关精简版，您可以参考[这篇文章](./File_archiving/[Windows][ResourceHacker]%20embedding%20mui%20into%20a%20exe%20so%20it%20will%20be%20able%20to%20run%20without%20external%20files,%20and%20even%20if%20the%20Windows%20language%20is%20currently%20different%20than%20the%20one%20you%20are%20embedding%20(reupload).md)（此文章为本站备份，原文作者为
     [MarcellaVT](https://gist.github.com/MarcellaVT/52f21102a29292d96e20a3033285098b)），一般根据此教程制作的精简版均可以支持在Wine环境运行！
   - 关于本项目：我在哪里可以找到“更多游戏”和“互联网游戏本体”？
     1. 在本项目的“More_Internet_Games”文件夹下，您可以找到被精简语言的“互联网游戏”以及“更多游戏”的dll文件。请注意，我们并没有对“互联网游戏”进行Wine环境的兼容更改，这些“互联网游戏”服务器也已经关闭。如果您有特殊需求，则请自行下载它们。
   - 关于本项目：这个项目版本已经比较老了或者我希望下载到更新的Win7GamesForWindows原版未精简版本，我该如何做？
     1. 您可以访问[此网站](https://win7games.com/)下载到原版Win7GamesForWindows版本，此版本就是Windows7原版的游戏对于最新Windows的适配了。一般情况下，您依然可以使用上文提到的文章对其进行精简与Wine环境的适配！
   - 关于字体：这些简体中文字体对应的具体信息是什么？
     1. simsun.ttc：宋体（SimSun），是Windows操作系统中非常基础的简体中文字体，广泛应用于文档编辑和网页显示。
     2. simhei.ttf：黑体（SimHei），以其简洁明快的线条深受用户喜爱，适用于标题或需要明确、现代感的文本展示。
     3. simfang.ttf：仿宋（SimFang），常用于正式文档、书籍排版，给人以古典雅致的感觉。
     4. simkai.ttf：楷体（SimKai），具有手写般的自然流畅，适合文学作品、通知、信函等，能够增添文本的艺术性和可读性。
2. 特别鸣谢：
   - Win7Games精简教程的保留发布者：[MarcellaVT](https://gist.github.com/MarcellaVT/52f21102a29292d96e20a3033285098b)
   - Win7GamesForWindows发布者：[Win7Games](https://win7games.com/)
   - ResourceHacker工具作者：[angusj](https://www.angusj.com/resourcehacker/)
   - 本项目灵感来源：[闲着没事突然想在Linux上运行win7游戏结果失败的仓库管理者，然后突然找到了这篇文章](https://forum.winehq.org/viewtopic.php?t=37417 )
   - Github平台的支持：[Github](https://github.com/)

最后更新：2025.1.23 | [查看协议](./LICENSE)
--------