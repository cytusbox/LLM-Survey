# LLM-Survey

[TOC]

## LLM 微调方法

- PEFT
- LoRA
- DeepSpeed
- vLLM

### PEFT



**参考资料**

[大模型参数高效微调技术实战(一)-PEFT概述](https://zhuanlan.zhihu.com/p/651744834)

[大模型参数高效微调技术原理综述(一)-背景、参数高效微调简介](https://zhuanlan.zhihu.com/p/635152813)
## LLM 显存用量

**参考资料**

[LLM基础资料整理：推理所需显存与速度](https://techdiylife.github.io/blog/topic.html?category2=t08&blogid=0058)

## LLM 实战经验

[llm-action](https://github.com/liguodongiot/llm-action)

[专题：大模型训练入门实战](https://techdiylife.github.io/blog/topic.html?category2=t01#3-chatgpt%E6%A8%A1%E5%9E%8B%E8%AE%AD%E7%BB%83%E5%9F%BA%E6%9C%AC%E6%B5%81%E7%A8%8B)

ChatGPT 的训练过程共分为四个步骤：

1. 训练预训练模型，如 GPT-3.5 或 GPT-4;
2. 监督微调(SFT：supervised finetuning)(对应 DS-Chat 中的 Step1);
3. 奖励模型微调(RM：Reward model finetuning)(对应 DS-Chat 中的 Step2);
4. 基于人类反馈的强化学习(RLHF：Reinforcement learning with human feedback)(对应 DS-Chat 中的 Step3)。