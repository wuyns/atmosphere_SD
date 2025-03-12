# 大气层配置

## 适用于最新的19.0.1系统

## 注意事项

为了防止误操作进入大气层真实系统导致ban机，我在`bootload/hekate_ipl.ini`中删除了这个选项，如果你需要使用大气层真实系统，请使用`bootload/hekate_ipl.ini.bak`文件替换`bootload/hekate_ipl.ini`

建立虚拟系统建议使用`SD Partition`而非`SD File`，原因是`SD Partition`对比`SD File`有明显的速度优势

已经在机器上通过测试，暂未发现任何Bug

## 使用方法

1. Code -> Download ZIP
2. 格式化SD卡
3. 解压ZIP文档，将其中的文件全部复制到SD卡根目录
4. 按照正常的软破解流程进入hekate，建立虚拟系统（如果你的机器已经被ban的话，当然可以不建立虚拟系统直接使用CFW-sysMMC进入大气层真实系统，不会占用SD卡额外的空间，而且速度比较好）
5. 进入CFW-emuMMC

## 已安装的软件

- [Awoo-Installer](https://github.com/Huntereb/Awoo-Installer) 安装游戏 汉化
- [DBI](https://github.com/rashevskyv/dbi) 用于安装游戏 英文
- [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader) 叠加层加载工具 (未测试)
- [Tesla-Menu](https://github.com/WerWolv/Tesla-Menu) 叠加层 (未测试)
- [EdiZon](https://github.com/WerWolv/EdiZon) 存档修改工具 (未测试)

## 参考（感谢）

- [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
- [hekate](https://github.com/CTCaer/hekate)
- [大气层switch使用指南](https://github.com/esrrhs/atmosphere-switch)
- [GBATEMP Sigpatches](https://gbatemp.net/threads/sigpatches-for-atmosphere-hekate-fss0-fusee-package3.571543/)
- [SIGPATCHES](https://sigmapatches.su/)
- [SYS-PATCH](https://sigmapatches.su/)
