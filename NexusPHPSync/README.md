# NexusPHPSync

NexusPHP站点之间转种的脚本，可以相对的方便的进行种子转发操作

## 介绍

目前全网找到的相关脚本只有[PT种子搬运助手](https://greasyfork.org/zh-CN/scripts/402942-pt%E7%A7%8D%E5%AD%90%E6%90%AC%E8%BF%90%E5%8A%A9%E6%89%8B)，但由于每个站的界面或多或少都基于原NexusPHP做过一些修改，这个脚本不能很好的处理这些差异，导致很多项并不能精准填写（当然想必有Coding能力的朋友自己会自己做一些修改来便于使用）

因为并不擅长前端，所以最开始也联系一些朋友尝试在此脚本修改，但发现脚本的写法很不利于处理站点的差异，而且代码结构比较混乱，很难维护，所以无奈**重写**。

新脚本能较灵活的处理站点之间的差异，而且方便开发人员扩展和维护，但由于：
1. 部分站点本人没有发种权限，导致无法测试是否支持发种
2. 部分站点基于NexusPHP改动较多，支持起来会耗费较多的精力，所以第一个版本最开始没有支持
第一版支持站点仍较少，后续会不断完善。

不过已经几乎可以填写所有区域，转种人只需要手动上传种子文件而已（这个由于chrome插件限制，不好实现，后续可能会有本地脚本来实现）

## 站点支持情况
| 站点 | 作为源站点 | 作为目标站点 |
| ---- | ---- | ---- |
| CHD | ✔ | ✔ |
| FRDS | ✔ | × |
| HDSky | ✔ | × |
| Beitai | ✔ | × |
| OurBits | ✔ | × |
| PTHome | ✔ | ✔ |
| HD4Fun | ✔ | × |
| SSD | ✔ | ✔ |
| CHD | ✔ | ✔ |
| PTERCLUB | ✔ | ✔ |
| MTEAM | ✔ | ✔ |
| TJUPT | ✔ | × |
| LemonHD | ✔ | × |
| HaiDan  | × | ✔|

## 使用方式
同原PT搬运助手
## 想要更多的站点支持
1. 如果有想要支持的站点，或者发现了Bug，可以提交Issue或者PR
2. 如果对本脚本有一些建议，也欢迎提交Issue
## 参考
[PT种子搬运助手](https://greasyfork.org/zh-CN/scripts/402942-pt%E7%A7%8D%E5%AD%90%E6%90%AC%E8%BF%90%E5%8A%A9%E6%89%8B)

