# Cuberite

[![Jenkins Build Status](https://img.shields.io/jenkins/build?jobUrl=https%3A%2F%2Fbuilds.cuberite.org%2Fjob%2Fcuberite%2Fjob%2Fmaster&label=Jenkins)](https://builds.cuberite.org/job/cuberite/job/master/)
[![AppVeyor Build Status](https://img.shields.io/appveyor/ci/cuberite/cuberite/master.svg?label=AppVeyor)](https://ci.appveyor.com/project/cuberite/cuberite)

Cuberite是一个Minecraft兼容的多人游戏服务器，它是用C++编写的，旨在提高内存和CPU的效率，并具有灵活的Lua插件API。Cuberite与Java版Minecraft客户端兼容。

Cuberite可在Windows、*nix和Android操作系统上运行。这包括Android手机和平板电脑以及树莓派;对小型嵌入式设备的支持是实验性的。

目前我们支持Release 1.8 - 1.12.2 Minecraft协议版本。

Subscribe to [the newsletter][1] for important updates and project news.订阅 [时事通讯][1] 获取重要更新和项目新闻。

## 安装

有几种方法可以获得Cuberite。

### 二进制

- 最简单的方法是从[网站][2]下载Windows或Linux。
- 您可以使用适用于Linux和macOS的EasyInstall脚本，它会自动下载正确的二进制文件。该脚本如下所述。

#### 简单安装

此脚本将从项目站点下载正确的二进制文件。

    curl -sSfL https://download.cuberite.org | sh

### 编译

- 您可以使用“compile.sh”脚本自动编译Linux、macOS和FreeBSD。该脚本如下所述。
- 您也可以手动编译。看 [COMPILING.md][4].

编译可以提供更好的性能（1.5- 3倍的速度），并支持更多的操作系统。

#### compile.sh脚本

该脚本下载源代码并编译它。该脚本足够智能，可以通知您缺少依赖项并指导您如何安装它们。该脚本不适用于Windows。

使用curl:

    sh -c "$(curl -sSfL -o - https://compile.cuberite.org)"

或者使用wget:

    sh -c "$(wget -O - https://compile.cuberite.org)"

### 托管服务

- 托管Cuberite可通过 [Gamocosm][5].

## 贡献

Cuberite是在Apache License V2下授权的，我们欢迎任何人分叉并提交一个Pull Request，如果你想加入成为永久成员，我们可以将你添加到团队中。

Cuberite使用C++和Lua开发。要贡献代码，请查看[GETTING-STARTED.md][6]和[CONTRIBUTING.md][7]了解更多详细信息。

插件是用Lua编写的。您可以通过开发插件并将其提交到[插件存储库][8]或[论坛][9]来贡献。请查看我们的[插件介绍指南][10]了解更多信息。

如果您不是程序员，您可以通过测试Cuberite和报告错误来提供帮助。详情请参阅[TESTING.md][11]。

您也可以通过为[用户手册][12]贡献内容来帮助文档编制。

## 其他东西

至于其他的东西，请查看[主页][13]，[用户手册][14]，[论坛][15]和[插件API][16]。

在[Liberapay][17]支持Cuberite开发团队

[1]: https://cuberite.org/news/#subscribe
[2]: https://cuberite.org/
[4]: https://github.com/cuberite/cuberite/blob/master/COMPILING.md
[5]: https://gamocosm.com/
[6]: https://github.com/cuberite/cuberite/blob/master/GETTING-STARTED.md
[7]: https://github.com/cuberite/cuberite/blob/master/CONTRIBUTING.md
[8]: https://plugins.cuberite.org/
[9]: https://forum.cuberite.org/forum-2.html
[10]: https://api.cuberite.org/Writing-a-Cuberite-plugin.html
[11]: https://github.com/cuberite/cuberite/blob/master/TESTING.md
[12]: https://github.com/cuberite/users-manual
[13]: https://cuberite.org/
[14]: https://book.cuberite.org/
[15]: https://forum.cuberite.org/
[16]: https://api.cuberite.org/
[17]: https://liberapay.com/Cuberite