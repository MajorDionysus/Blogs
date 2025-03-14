---
title: "实验报告示例"
author: "你的名字"
date: "2025-03-14"
categories: [实验, 物理, Markdown]
layout: post
---

# 实验报告

## 实验名称
**牛顿第二定律实验**

## 实验目的
1. 研究牛顿第二定律的适用性。
2. 通过实验测量加速度与力的关系。

## 实验器材
- 小车
- 砝码
- 滑轮
- 电子计时器
- 刻度尺
  [test](logo.png)

## 代码示例
实验数据处理 Python 代码：

```python
import numpy as np
import matplotlib.pyplot as plt

# 数据
mass = np.array([0.5, 1.0, 1.5])
force = np.array([1.0, 2.0, 3.0])
acceleration = force / mass

# 绘图
plt.plot(force, acceleration, 'ro-', label='F = ma')
plt.xlabel("Force (N)")
plt.ylabel("Acceleration (m/s²)")
plt.legend()
plt.grid()
plt.show()
```

## 结论
实验结果验证了牛顿第二定律，即加速度与作用力成正比，与物体质量成反比。

## 参考文献
1. 牛顿. 《自然哲学的数学原理》
2. 物理实验教材 (2025)

