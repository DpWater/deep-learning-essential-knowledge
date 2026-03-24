# 深度学习必备知识（Deep Learning Essential Knowledge）

这是一个面向长期积累的深度学习知识库，目标是把“数学基础 -> 模型原理 -> 训练优化 -> 项目实践 -> 工程部署”串成可复用的学习与实战路径。

## 项目现状分析

当前仓库已完成并沉淀的核心内容：

- `基础数学/数学速查手册.md`：高于 D2L 线性网络章节的系统化手册
- `基础数学/images/`：对应图示（内积、线性回归、softmax、logsumexp 稳定性等）

其余模块已建立目录骨架，便于后续持续补充。

## 完整目录（当前）

```text
.
├─README.md
├─基础数学
│  ├─数学速查手册.md
│  └─images
│     ├─fig_dot_product.png
│     ├─fig_linear_regression_fit.png
│     ├─fig_logsumexp_stability.png
│     ├─fig_mse_convex_contour.png
│     └─fig_softmax_temperature.png
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

- `基础数学`：线性代数、微积分、概率统计在深度学习中的核心落地
- `神经网络基础`：感知机、MLP、反向传播、激活与归一化
- `训练与优化`：损失函数、优化器、学习率策略、正则化、训练诊断
- `常见模型`：CNN、RNN、Transformer、Diffusion/GAN/VAE
- `项目实践`：经典项目阅读、复现与改造
- `工程化与部署`：训练脚本工程化、模型导出、服务部署与监控
- `数据处理与评估`：数据治理、评估指标、实验管理
- `论文与资料`：论文、课程、工具链与参考资源

## 项目实践（经典 GitHub 项目地址 + 说明）

### 入门与原理

- [karpathy/micrograd](https://github.com/karpathy/micrograd)：几十行代码实现自动求导，适合理解反向传播底层机制。
- [karpathy/nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)：从零实现神经网络与语言模型的教学型项目。

### 计算机视觉

- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)：YOLO 系列官方实现，目标检测实战首选之一。
- [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2)：经典视觉任务框架，覆盖检测、分割、关键点等。

### NLP 与大模型

- [huggingface/transformers](https://github.com/huggingface/transformers)：NLP/多模态预训练模型生态核心库。
- [karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)：极简 GPT 训练代码，适合理解 LLM 训练主流程。

### 生成式模型

- [CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion)：扩散模型里程碑项目，适合学习文生图管线。
- [openai/guided-diffusion](https://github.com/openai/guided-diffusion)：扩散模型训练与采样的经典参考实现。

### 工程化与训练加速

- [Lightning-AI/pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning)：规范化训练循环，降低工程样板代码成本。
- [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed)：大模型分布式训练与推理优化框架。

## 建议学习路径

1. 先完成 `基础数学/数学速查手册.md`
2. 并行补齐 `神经网络基础` 与 `训练与优化`
3. 从 `常见模型/Transformer` 开始进入主流架构
4. 在 `项目实践` 按“读代码 -> 跑通 -> 改造 -> 复盘”闭环
5. 最后沉淀到 `工程化与部署` 与 `数据处理与评估`

## 后续维护建议

- 每个模块至少维护 1 份“核心概念速查” + 1 份“实践模板”
- 每次项目复现都记录：数据、配置、结果、踩坑、可复现命令
- 统一使用 UTF-8 编码，避免中文乱码
