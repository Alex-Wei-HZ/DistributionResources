# Third-party notices / 第三方声明

各组件按随附许可分发：

- 项目自有部分及安装工具：MIT，copyright 2026 Alex-Wei。
- Arduino ESP32 2.0.17 核心及 SPI/Wire/FS/SD：LGPL-2.1-or-later。对应库源码、应用对象和重链接工具随同版本 LGPL ZIP 提供；允许接收者修改用于自身使用，并为调试这些修改进行逆向工程，不限制 LGPL 授予的权利。
- M5Cardputer、M5Unified、M5GFX：M5Stack 及贡献者。MIT 与相关子组件声明保存在 `LICENSES/`，包括 LovyanGFX、efont、Adafruit 字体和图形工具的原有声明。
- Noto Sans SC：SIL OFL 1.1，原许可和来源在 `LICENSES/`。
- ESP-IDF 4.4.7 及 SDK 组件：Apache-2.0 及各组件许可，见 `LICENSES/esp-idf/`。Newlib 与 GCC runtime exception 见 `LICENSES/toolchain-runtime/`。
- Aiden 语音：Qwen 团队的 Qwen3-TTS 1.7B CustomVoice Aiden，经 MLX Community 固定 revision 转换，在本地使用 MLX-Audio 生成。模型卡声明 Apache-2.0；模型 revision、参数、逐文件记录和 MIT/Apache/MLX/MLX-Audio 许可均保存在 SD 资源包的 `TFVOICE/PKG00001/`。未分发模型权重、训练录音或语音克隆参考音频。

清理版本移除了编译调试信息，将构建机绝对路径改为同长度的中性路径，保留重链接所需符号及重定位。SDK 省略未使用的内存配置、bootloader 文件和 Mbed TLS 公共测试证书对象。原版权声明及许可保留，处理方法在重链接 ZIP 内 `privacy.py` 与 `relink.py` 中。与上游源码的区别属于分发构建处理；未将这些二进制处理结果表述为原始未修改库。

普通玩家只需 SD 资源包；LGPL 套件供接收者修改、重编译库及重链接使用，不提供完整游戏源码。清理不保证机器码无法逆向。
