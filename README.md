### AndroidScreenShot
用于Android手机实时截屏的工具，提供API和使用的demo，主要基于minicap和scrpy工具，相关的文件下载好之后需要提前放入asset中
代码会帮忙检查手机的相关信息，然后push不同的文件进到手机中

### Related Tool
#### minicap
- 一个基于socket进行传输图像传输的工具，需要根据不同安装版本进行不同支持，目前最高支持到Android34，最新的minicap可以从如下link获取
- https://github.com/DeviceFarmer/minicap/commit/2aa036bb37f95251c3082aaa7a0184fa59a8e635

#### scrcpy
- 一个基于soket和client端的实时投屏工具，同时也提供了传输文本图像音频等的功能，以及控制手机的功能

### Usage Guide
通过执行如下的代码，可以直接运行代码中提供的三个Demo，可根据个人需求进行修改和完善
```
python screenshot.py
```
