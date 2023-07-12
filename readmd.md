
# HuanTong 还童
目的：少量参数训练，取得全量参数效果。并且以DPO替代PPO-PTX，适合通常简易场景。可能是最容易的全流程RLHF大模型流程。

背景：大模型训练时候，如果全部参数训练成本高昂，peft少量参数更新可以取得全量参数更新接近的效果，成本低，适用于小规模微调。


## DPO
DPO替代PPO-PTX，DPO同步更新基干和偏好模型，应用通常简易场景。

## 预训练
引自    MedicalGPT

## 指令微调
引自    MedicalGPT

## 强化反馈
采用DPO，同步反馈，适合大多数简易场景
引自 Anima

## 数据
* 指令格式 采用BELLE


## 计划
自动还童
自适应约束策略

## 参考
* pretrain,sft codes   https://github.com/shibing624/MedicalGPT
* dpo codes, https://github.com/lyogavin/Anima/tree/main/rlhf
* data format, https://github.com/LianjiaTech/BELLE
* DPO（Direct Preference Optimization)，https://arxiv.org/abs/2305.18290
* LoRA, https://openreview.net/forum?id=nZeVKeeFYf9