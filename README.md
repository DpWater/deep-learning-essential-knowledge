# 深度学习必备知识（Deep Learning Essential Knowledge）

这是一个面向长期积累的深度学习知识库，目标是把“数学基础 -> 模型原理 -> 训练优化 -> 项目实践 -> 工程部署”串成可复用的学习与实战路径。

## 本次结构调整

`基础数学` 已按你的要求重构为三大模块：

- 高等数学（高数内容集中）
- 线性代数（矩阵内容集中）
- 概率与离散（概率与离散内容集中）

并且章节安排已对齐你提供的 B站课程分集（BV1gQ4y1E7iy），同时保留 D2L 线性网络实践映射。

## 完整目录（当前）

```text
.
├─README.md
├─基础数学
│  ├─README.md
│  ├─课程映射.md
│  ├─数学速查手册.md
│  ├─高等数学
│  │  ├─README.md
│  │  ├─01-函数与极限.md
│  │  ├─02-导数偏导方向导数梯度.md
│  │  ├─03-积分与泰勒展开.md
│  │  ├─04-拉格朗日乘子法.md
│  │  ├─05-激活函数与非线性.md
│  │  └─06-数值稳定与误差分析.md
│  ├─线性代数
│  │  ├─README.md
│  │  ├─01-向量矩阵与张量.md
│  │  ├─02-行列式矩阵操作与秩.md
│  │  ├─03-线性变换特征值与特征向量.md
│  │  ├─04-SVD与特征空间应用.md
│  │  └─05-核函数与特征映射.md
│  ├─概率与离散
│  │  ├─README.md
│  │  ├─01-随机变量与概率基础.md
│  │  ├─02-似然与极大似然估计.md
│  │  ├─03-期望不等式与贝叶斯直觉.md
│  │  ├─04-常见分布与信息熵.md
│  │  ├─05-回归分析与统计建模.md
│  │  ├─06-假设检验与相关分析.md
│  │  ├─07-方差分析与聚类扩展.md
│  │  ├─08-线性回归与softmax理解应用.md
│  │  ├─09-偏差方差与正则化.md
│  │  └─10-贝叶斯分析与MCMC.md
│  └─images
│     ├─fig_dot_product.png
│     ├─fig_linear_regression_fit.png
│     ├─fig_logsumexp_stability.png
│     ├─fig_mse_convex_contour.png
│     ├─fig_softmax_temperature.png
│     └─gifs
│        ├─calculus_change.gif
│        ├─matrix_transform.gif
│        └─probability_shift.gif
├─神经网络基础
│  └─README.md
├─训练与优化
│  └─README.md
├─常见模型
│  ├─README.md
│  ├─CNN
│  │  └─README.md
│  ├─RNN与时序模型
│  │  └─README.md
│  ├─Transformer
│  │  └─README.md
│  └─生成模型
│     └─README.md
├─项目实践
│  └─README.md
├─工程化与部署
│  └─README.md
├─数据处理与评估
│  └─README.md
└─论文与资料
   └─README.md
```

## 模块说明

- `基础数学`：按“高数 -> 矩阵 -> 概率离散”组织，适合系统学习与查阅
- `神经网络基础`：感知机、MLP、反向传播、激活与归一化
- `训练与优化`：损失函数、优化器、学习率策略、正则化、训练诊断
- `常见模型`：CNN、RNN、Transformer、Diffusion/GAN/VAE
- `项目实践`：经典项目阅读、复现与改造
- `工程化与部署`：训练脚本工程化、模型导出、服务部署与监控
- `数据处理与评估`：数据治理、评估指标、实验管理
- `论文与资料`：论文、课程、工具链与参考资源

## 参考资料

- B站课程：<https://www.bilibili.com/video/BV1gQ4y1E7iy>
- D2L 线性网络：<https://zh.d2l.ai/chapter_linear-networks/index.html>

## 建议学习路径

1. 先完成 `基础数学/高等数学`、`基础数学/线性代数`、`基础数学/概率与离散`
2. 然后进入 `神经网络基础` 与 `训练与优化`
3. 再做 `项目实践`，形成“理论 -> 实验 -> 复盘”闭环
4. 最后沉淀到 `工程化与部署` 与 `数据处理与评估`
