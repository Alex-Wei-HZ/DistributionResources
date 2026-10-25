# Typing Fighter / 打字战神 v0.1.0-rc.2

适用 **M5Stack Cardputer ADV / K132-ADV**。完整固件通过 M5Burner 安装，SD 单词语音另行安装。

| 下载 | 用途 |
|---|---|
| [Aiden SD 资源包](TypingFighter-v0.1.0-rc.2-Aiden-SD.zip) | 全部 512 词、可直接复制的 TFVOICE 目录及已有 SD 卡的安装工具 |
| [LGPL 源码与重链接材料](TypingFighter-v0.1.0-rc.2-LGPL-relink.zip) | 必要第三方库源码和清理后的链接对象；普通玩家无需下载 |
| [许可与第三方声明](THIRD-PARTY-NOTICES.md) / [许可证](LICENSES/) | 组件来源与适用条款 |
| [SHA-256](SHA256SUMS.txt) | 下载校验 |

在 GitHub 点击 ZIP 后使用 **Download raw file** 保存。解压 SD 资源包，按其中 `README.md` 安装：新卡直接将 `TFVOICE` 复制到 FAT32 / MBR 卡根目录；已有语音包时使用包内安装器，保留旧包并切换到 Aiden。无需下载模型或注册 TTS 账号。

安全弹出卡，关机插卡后重新开机。Enter 确认，直接使用方向标识键，`p` 暂停、`r` 重开。无声音时检查静音/音量、目录结构并按包内说明运行校验。完整烧录会覆盖启动器、设置及内部存档，SD 卡不受影响。

Download the SD package, then follow its README. Copy `TFVOICE` to the root of a fresh FAT32/MBR card, or use the included installer for a card with existing voice packages. The LGPL kit is supplied for modifying libraries and is optional for playing. Match the resource version to the M5Burner firmware.
