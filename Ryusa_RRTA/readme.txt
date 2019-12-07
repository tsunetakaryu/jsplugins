【自述】
Ryusa Reference Time Assistor（流砂的参考时间小助手）
用于快速地获取基于曲速的压缩释放时间、混响预延迟及混响时间参数。

【特性】
·方便地获取基于曲速（Tempo）的各类时间参数
·曲速源可选择读取宿主或手动指定
·带有节拍指示灯，可以切换两种基本的节奏类型

【部署向导】
在 Reaper 中按照以下步骤导航到 Reaper 安装文件夹：
Options -> Show REAPER resource path in explorer/finder ...
解压 Effects.zip，复制 RRTA 文件至：
..\Reaper\Effects\utility
目录。

【加载向导】
在任意轨道中添加插件，在 All Plugins 或 JS 文件夹内搜索包括以下字符的任意内容即可：
Ryusa Reference Time Assistor

【版本信息】
1.07 - 优化代码，优化各项数值显示；优化界面随 Tempo 变色的行为；新增节拍指示灯。
1.06 - 小幅修正。
1.05 - 允许选择 Tempo 值跟随宿主或者手动设定；引入数值保护功能，当输入参数过大时自动修正到边界值。
1.04 - 修正插件在旁通状态下数值显示相当鬼畜的问题，修正单词拼写错误的问题。
1.03 - 精简代码，优化算法；小彩蛋：界面会随着 Tempo 变色。
1.00 - 初始化。

【作者信息】
Tsunetaka Ryu (yamazakiryusa@qq.com)
** 在 UI 的设计上参考了 Liteon 的 VU Meter 插件，特别感谢
** 在 HSB 转 RGB 的算法上参考了 kawa_ 的代码，特别感谢