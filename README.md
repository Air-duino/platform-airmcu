# platform-airmcu
AIRM2M MCU: development platform for PlatformIO 


- 2023/7/11: Preliminary platfrom.json & /boards/air001.json completed

# PlatfromIO 自定义开发板 Air001

这是一个基于 Air001 的 PlatfromIO 自定义开发板，Air001 是一款 TSSOP20 封装的 MCU，内置 32K Flash 和 4K SRAM。

## 目录结构

这个自定义开发板的目录结构如下：


  - boards
    - air001.json # 自定义开发板的配置文件（已完成，待校对）
  - builder
    - main.py # 自定义开发板的构建脚本（未完成）
  - platform.json # 自定义平台的元数据和依赖文件（已完成，待校对）

## 安装

要安装这个自定义开发板，您需要：

- 在 PlatfromIO 的 core 目录下，或者在项目目录下（如果您想要每个项目使用不同的开发板），创建一个 `air001` 文件夹。
- 从这个仓库中复制 `boards`，`builder` 和 `platform.json` 文件到 `air001` 文件夹中。
- 通过 PlatfromIO IDE 或者 CLI 命令 `pio platform install air001` 来安装自定义平台。
- 在您的项目中选择 `Air001` 作为目标开发板。

## 使用

您可以像使用其他 PlatfromIO 开发板一样使用这个自定义开发板。您可以使用您喜欢的框架来编写代码，编译和上传固件，以及调试您的设备。

更多细节，请参考 PlatfromIO 的文档。


Please navigate to [documentation](https://docs.platformio.org/page/platforms/air001.html).
