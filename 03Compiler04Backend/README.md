<!--Copyright © ZOMI 适用于[License](https://github.com/chenzomi12/AISystem)版权许可-->

# 后端优化

《编译后端优化》后端优化作为 AI 编译器跟硬件之间的相连接的模块，更多的是算子或者 Kernel 进行优化，而优化之前需要把计算图转换称为调度树等 IR 格式，然后针对每一个算子/Kernel 进行循环优化、指令优化和内存优化等技术。

> 希望这个系列能够给大家、朋友们带来一些些帮助，也希望自己能够继续坚持完成所有内容哈！

**内容大纲**

> `PPT`和`字幕`需要到 [Github](https://github.com/chenzomi12/AISystem) 下载，网页课程版链接会失效哦~
>
> 建议优先下载 PDF 版本，PPT 版本会因为字体缺失等原因导致版本很丑哦~

| 小节 | 链接|
|:--|:--|
| 01 AI 编译器后端优化介绍 | [文章](./01Introduction.md), [PPT](./01Introduction.pdf), [视频](https://www.bilibili.com/video/BV17D4y177bP/), [字幕](./srt/01.srt) |
| 02 算子分为计算与调度 | [文章](./02OPSCompute.md), [PPT](./02OPSCompute.pdf), [视频](https://www.bilibili.com/video/BV1K84y1x7Be/), [字幕](./srt/02.srt) |
| 03 算子优化手工方式| [文章](./03Optimization.md), [PPT](./03Optimization.pdf), [视频](https://www.bilibili.com/video/BV1ZA411X7WZ/), [字幕](./srt/03.srt) |
| 04 算子循环优化| [文章](./04LoopOpt.md), [PPT](./04LoopOpt.pdf), [视频](https://www.bilibili.com/video/BV17D4y177bP/), [字幕](./srt/04.srt) |
| 05 指令和内存优化 | [文章](./05OtherOpt.md), [PPT](./05OtherOpt.pdf), [视频](https://www.bilibili.com/video/BV11d4y1a7J6/), [字幕](./srt/05.srt) |
| 06 Auto-Tuning 原理 | [文章](./06AutoTuning.md), [PPT](./06AutoTuning.pdf), [视频](https://www.bilibili.com/video/BV1uA411D7JF/), [字幕](./srt/05.srt) |

## 备注

文字课程内容正在一节节补充更新，每晚会抽空继续更新正在 [AISys](https://chenzomi12.github.io/) ，希望您多多鼓励和参与进来！！！

文字课程开源在 [AISys](https://chenzomi12.github.io/)，系列视频托管[B 站](https://space.bilibili.com/517221395)和[油管](https://www.youtube.com/@ZOMI666/videos)，PPT 开源在[github](https://github.com/chenzomi12/AISystem)，欢迎取用！！！

> 非常希望您也参与到这个开源项目中，B 站给 ZOMI 留言哦！
>
> 欢迎大家使用的过程中发现 bug 或者勘误直接提交代码 PR 到开源社区哦！
>
> 希望这个系列能够给大家、朋友们带来一些些帮助，也希望自己能够继续坚持完成所有内容哈！

```{toctree}
01Introduction
02OPSCompute
03Optimization
04LoopOpt
05OtherOpt
06AutoTuning
```