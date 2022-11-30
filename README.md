[![Syncthing][14]][15]

---

[![Latest Linux & Cross Build](https://img.shields.io/teamcity/https/build.syncthing.net/s/Syncthing_BuildLinuxCross.svg?style=flat-square&label=linux+%26+cross+build)](https://build.syncthing.net/viewType.html?buildTypeId=Syncthing_BuildLinuxCross&guest=1)
[![Latest Windows Build](https://img.shields.io/teamcity/https/build.syncthing.net/s/Syncthing_BuildWindows.svg?style=flat-square&label=windows+build)](https://build.syncthing.net/viewType.html?buildTypeId=Syncthing_BuildWindows&guest=1)
[![Latest Mac Build](https://img.shields.io/teamcity/https/build.syncthing.net/s/Syncthing_BuildMac.svg?style=flat-square&label=mac+build)](https://build.syncthing.net/viewType.html?buildTypeId=Syncthing_BuildMac&guest=1)
[![MPLv2 License](https://img.shields.io/badge/license-MPLv2-blue.svg?style=flat-square)](https://www.mozilla.org/MPL/2.0/)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/88/badge)](https://bestpractices.coreinfrastructure.org/projects/88)
[![Go Report Card](https://goreportcard.com/badge/github.com/syncthing/syncthing)](https://goreportcard.com/report/github.com/syncthing/syncthing)

## 目标

DecenS是一个**连续文件同步程序**。它同步两台或多台计算机之间的文件。我们努力实现以下目标。目标按重要性顺序列出，最重要的目标是第一个。这是目标列表的摘要版本。

DecenS应该：

1. **无数据丢失**

保护用户的数据至关重要。我们采取一切合理的措施避免损坏用户文件的预防措施。

2. **抵御攻击者**

同样，保护用户的数据至关重要。不管我们的其他
   我们绝不能让用户的数据容易受到影响的目标
   未经授权方的窃听或修改。

3. **易于使用**

DecenS应该是平易近人、易于理解和包容的。

4. **高度自动**

只有在绝对必要时才需要用户交互。

5. **便捷易用**

DecenS应在每台常用计算机上运行。我们注意到最新技术并不总是适用于任何给定的个人。

6. **面向个人**

DecenS主要是为个人用户提供安全，且易于使用的文件同步。

7. **其他**

我们关心的很多事情都没有列入清单。它可以针对这些值进行优化，只要它们不与上述既定目标冲突。

## 入门

查看 [入门指南][2]。

有几个示例可以保持DecenS在后台运行
在您的系统上的 [etc 目录][3]。还有几个 [GUI实现][11]适用于Windows，Mac和Linux。

## 文档

请参阅 Syncthing [文档网站][6]。

所有代码均在 [MPLv2 许可证][7] 下获得许可。

[1]:https://docs.syncthing.net/specs/bep-v1.html
[2]:https://docs.syncthing.net/intro/getting-started.html
[3]:https://github.com/syncthing/syncthing/blob/main/etc
[5]:https://docs.syncthing.net/dev/building.html
[6]:https://docs.syncthing.net/
[7]:https://github.com/syncthing/syncthing/blob/main/LICENSE
[8]:https://forum.syncthing.net/
[10]:https://github.com/syncthing/syncthing/issues
[11]:https://docs.syncthing.net/users/contrib.html#gui-wrappers
[12]:https://www.bountysource.com/teams/syncthing/issues
[13]:https://github.com/syncthing/syncthing/blob/main/GOALS.md
[14]:assets/logo-text-128.png
[15]:https://syncthing.net/
[16]:https://github.com/syncthing/syncthing/blob/main/README-Docker.md
[17]:https://github.com/syncthing/docs
