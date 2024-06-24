# LLM101n: 让我们一起创造一个会讲故事的人

![LLM101n header image](llm101n.jpg)

>  凡我不能创造的，我就不能理解。 -理查德·费曼

在本课程中，我们将构建一个讲故事的 AI 大型语言模型 (LLM)。通过手把手的教学，您将能够使用 AI 创建、完善和插图小故事（参考[故事](https://huggingface.co/datasets/roneneldan/TinyStories)）。我们将从基础开始，端到端地构建所有内容，最终开发出一个类似于 ChatGPT 的功能性 Web 应用程序，使用 Python、C 和 CUDA 编写，且计算机科学的先决知识要求较低。到课程结束时，您将对 AI、LLM 和深度学习有相对深入的理解。

**课程大纲**

- [第一章](bigram/README.md) **二元语言模型**（语言建模）
- [第二章](micrograd/README.md) **Micrograd**（机器学习，反向传播）
- [第三章](mlp/README.md) **N元模型**（多层感知器，矩阵乘法，GELU）
- [第四章](attention/README.md) **注意力机制**（注意力机制，Softmax，位置编码器）
- [第五章](transformer/README.md) **Transformer**（Transformer，残差连接，LayerNorm，GPT-2）
- [第六章](tokenization/README.md) **分词**（最小BPE，字节对编码）
- [第七章](optimization/README.md) **优化**（初始化，优化，AdamW）
- [第八章](device/README.md) **速度需求I：设备**（设备，CPU，GPU，...）
- [第九章](precision/README.md) **速度需求II：精度**（混合精度训练，fp16，bf16，fp8，...）
- [第十章](distributed/README.md) **速度需求III：分布式**（分布式优化，DDP，ZeRO）
- [第十一章](datasets/README.md) **数据集**（数据集，数据加载，合成数据生成）
- [第十二章](inference/README.md) **推理I：kv缓存**（kv缓存）
- [第十三章](quantization/README.md) **推理II：量化**（量化）
- [第十四章](sft/README.md) **微调I：SFT**（监督微调SFT，PEFT，LoRA，chat）
- [第十五章](rl/README.md) **微调II：强化学习**（强化学习，RLHF，PPO，DPO）
- [第十六章](deployment/README.md) **部署**（API，网络应用）
- [第十七章](multimodal/README.md) **多模态**（VQVAE，扩散Transformer）

**附录**

进一步研究的主题：

- 编程语言：汇编，C，Python
- 数据类型：整数，浮点数，字符串（ASCII，Unicode，UTF-8）
- 张量：形状，视图，步幅，连续性，...
- 深度学习框架：PyTorch，JAX
- 神经网络架构：GPT（1, 2, 3, 4），Llama（RoPE，RMSNorm，GQA），MoE，...
- 多模态：图像，音频，视频，VQVAE，VQGAN，扩散模型

