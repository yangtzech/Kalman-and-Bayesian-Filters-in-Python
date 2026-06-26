# 卡尔曼滤波与贝叶斯滤波 — 中文翻译

本目录包含 Roger R. Labbe 所著 [Kalman and Bayesian Filters in Python](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python) 的完整简体中文翻译。

## 目录

| 章节 | 文件 |
|------|------|
| 前言 | [00-前言.ipynb](00-前言.ipynb) |
| 目录 | [00-A目录.ipynb](00-A目录.ipynb) |
| 第1章：g-h 滤波器 | [01-g-h滤波器.ipynb](01-g-h滤波器.ipynb) |
| 第2章：离散贝叶斯 | [02-离散贝叶斯.ipynb](02-离散贝叶斯.ipynb) |
| 第3章：高斯模型 | [03-高斯模型.ipynb](03-高斯模型.ipynb) |
| 第4章：一维卡尔曼滤波器 | [04-一维卡尔曼滤波器.ipynb](04-一维卡尔曼滤波器.ipynb) |
| 第5章：多维高斯模型 | [05-多维高斯模型.ipynb](05-多维高斯模型.ipynb) |
| 第6章：多维卡尔曼滤波器 | [06-多维卡尔曼滤波器.ipynb](06-多维卡尔曼滤波器.ipynb) |
| 第7章：卡尔曼滤波器中的数学 | [07-卡尔曼滤波器中的数学.ipynb](07-卡尔曼滤波器中的数学.ipynb) |
| 第8章：设计卡尔曼滤波器 | [08-设计卡尔曼滤波器.ipynb](08-设计卡尔曼滤波器.ipynb) |
| 第9章：非线性滤波 | [09-非线性滤波.ipynb](09-非线性滤波.ipynb) |
| 第10章：无迹卡尔曼滤波器 | [10-无迹卡尔曼滤波器.ipynb](10-无迹卡尔曼滤波器.ipynb) |
| 第11章：扩展卡尔曼滤波器 | [11-扩展卡尔曼滤波器.ipynb](11-扩展卡尔曼滤波器.ipynb) |
| 第12章：粒子滤波器 | [12-粒子滤波器.ipynb](12-粒子滤波器.ipynb) |
| 第13章：平滑化 | [13-平滑化.ipynb](13-平滑化.ipynb) |
| 第14章：自适应滤波器 | [14-自适应滤波器.ipynb](14-自适应滤波器.ipynb) |
| 附录A：安装 | [附录A-安装.ipynb](附录A-安装.ipynb) |
| 附录B：符号和标记 | [附录B-符号和标记.ipynb](附录B-符号和标记.ipynb) |
| 附录D：H无穷滤波器 | [附录D-H无穷滤波器.ipynb](附录D-H无穷滤波器.ipynb) |
| 附录E：集合卡尔曼滤波器 | [附录E-集合卡尔曼滤波器.ipynb](附录E-集合卡尔曼滤波器.ipynb) |
| 附录G：设计非线性卡尔曼滤波器 | [附录G-设计非线性卡尔曼滤波器.ipynb](附录G-设计非线性卡尔曼滤波器.ipynb) |
| 附录H：最小二乘滤波器 | [附录H-最小二乘滤波器.ipynb](附录H-最小二乘滤波器.ipynb) |
| 附录I：性能分析评估 | [附录I-性能分析评估.ipynb](附录I-性能分析评估.ipynb) |

## 已翻译的 Supporting Notebooks

| 文件 | 说明 |
|------|------|
| [Taylor-Series.ipynb](Supporting_Notebooks/Taylor-Series.ipynb) | 泰勒级数线性化 |
| [Converting-Multivariate-Equations-to-Univariate.ipynb](Supporting_Notebooks/Converting-Multivariate-Equations-to-Univariate.ipynb) | 多维方程转一维 |
| [Interactions.ipynb](Supporting_Notebooks/Interactions.ipynb) | 交互式演示 |
| [Computing_and_plotting_PDFs.ipynb](Supporting_Notebooks/Computing_and_plotting_PDFs.ipynb) | 概率密度函数的计算与绘图 |
| [Iterative-Least-Squares-for-Sensor-Fusion.ipynb](Supporting_Notebooks/Iterative-Least-Squares-for-Sensor-Fusion.ipynb) | 传感器融合中的迭代最小二乘法 |

## 术语对照

| 英文 | 中文 |
|------|------|
| Kalman filter | 卡尔曼滤波器 |
| Gaussian | 高斯分布 |
| covariance | 协方差 |
| measurement | 测量 |
| prediction | 预测 |
| update | 更新 |
| state | 状态 |
| estimate | 估计 |
| process model | 过程模型 |
| variance | 方差 |
| standard deviation | 标准差 |
| mean | 均值 |
| probability | 概率 |
| prior / posterior | 先验 / 后验 |
| likelihood | 似然 |
| Kalman gain | 卡尔曼增益 |
| residual / innovation | 残差 / 新息 |
| Extended Kalman Filter (EKF) | 扩展卡尔曼滤波器 |
| Unscented Kalman Filter (UKF) | 无迹卡尔曼滤波器 |
| particle filter | 粒子滤波器 |
| smoothing | 平滑化 |
| adaptive filtering | 自适应滤波 |

## 翻译说明

- 前6章（第1-4章 + 前言）基于 `loveuav` 和 `carl-3070` 的已有翻译
- 第7-14章及附录使用 ChatGPT 翻译，经人工审校
- 所有 LaTeX 公式和代码保持原样，仅翻译文本说明
- 代码中的变量名、函数名、类名保持英文不变

## 许可证

- 内容：[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
- 代码：[MIT License](../license.html)
