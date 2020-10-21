# 使用脚本构建阵列 Benchmark

## 0、说明

我发现仿真规模对实验结果与耗时有相当重要的影响，有时等待几天的仿真结果与仿真几小时的结果提升并不大。为了获得结果与耗时之间的一个平衡，需要一定的经验值。

## 1、硬件测试环境

| 项目 | 参数 |
| - | - |
| CPU | Intel i7-8700 3.2GHz |
| 内存 | 16GB 2400MHz |
| 固态硬盘 | TOSHIBA KSG60ZMV256 |
| 机械硬盘 | WDC WD10EZEX-75WN4A0 |
| 独立显卡 | NVIDIA GTX 1070 |


## 2、软件测试环境

- Mircosoft Windows 10 Professional 1909 (18363.1082)
- Lumerical FDTD Solutions 2019b r4


## 3、建模测试
| 规模 | 耗时(秒) | 耗时（分钟）| 耗时（小时）|
| - | - | - | - |
| 10×10 | 0.842 |  |  |
| 20×20 | 4.018 |  |  |
| 30×30 | 12.623 |  |  |
| 40×40 | 32.689 |  |  |
| 50×50 | 74.206 | 1.24  |  |
| 60×60 | 147.353 | 2.46 |  |
| 70×70 | 284.057 | 4.73 |  |
| 80×80 | 670.909 | 11.18 |  |
| 90×90 | 1043.33 | 17.39 |  |
| 100×100 | 1762.05 | 29.37 |  |
| 110×110 | 2974.44 | 49.57 |  |
| 120×120 | 4851.93 | 80.87 | 1.34 |
| 130×130 |  |  |  |
| 140×140 |  |  |  |
| 150×150 | 13972.4 | 232.87  | 3.88 |
| 160×160 |  |  |  |
| 170×170 |  |  |  |
| 180×180 |  |  |  |
| 190×190 |  |  |  |
| 200×200 |  |  |  |
| 210×210 |  |  |  |
| 220×220 |  |  |  |
| 230×230 |  |  |  |
| 240×240 |  |  |  |
| 250×250 |  |  |  |
| 260×260 |  |  |  |
| 270×270 |  |  |  |
| 280×280 |  |  |  |
| 290×290 |  |  |  |
| 300×300 |  |  |  |






