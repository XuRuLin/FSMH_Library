# 超表面全息 FDTD Solutions 脚本库

![](https://img.shields.io/badge/build-passing-brightgreen)
![](https://img.shields.io/badge/language-Lumerical-orange)
![](https://img.shields.io/badge/license-GPLv3-lightgrey)

FDTD Solutions Script Library for Metasurface Holographic

暂时自用，未完成。

## 项目简介

Lumerical FDTD Solutions 仿真超表面（Metasurface）用到的脚本文件。

## 功能特性

`./data/Material/`: 存放材料数据

`./source/`: 存放 lsf 源代码

`./source/Template.lsf`: 构建超表面阵列脚本模板

`./source/GDSII`: 导出 GDSII 文件

`./source/Analysis/`: 分析脚本

`./source/Modeling/`: 构造 Metasurface 阵列

`./source/experimental/`: 试验性质的代码（谨慎使用）

``` Lumerical
FarField.lsf                # 远场投影(直角坐标)
FarField_polar.lsf          # 远场投影(球坐标) 速度快无畸变 建议使用
Diffraction.lsf             # 沿光轴衍射
PhaseAnalysis.lsf           # 扫描后相位分析
CircularPolarization.lsf    # 圆极化分析
EfficiencyAnalysis.lsf      # 效率分析
TicToc                      # 类MATLAB程序运行计时
```

其他功能可以通过脚本片段自行组合实现

## Benchmark

`./Benchmark.md`: 对不同问题规模的基准测试，提供耗时参考。

## 协议

* GNU GPLv3

## P.S.
* UTF-8 without BOM