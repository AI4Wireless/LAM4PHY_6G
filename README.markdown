# Large AI Models for Wireless Physical Layer

A collection of paper on Large AI Models (LAMs) for wireless physical layer applications, extended from the overview paper by Jiajia Guo et al. (xxxx).

(Contributors：[Jiajia Guo](https://jiajiaguo.github.io/), [Yiming Cui](https://scholar.google.com/citations?hl=zh-CN&user=ZaKiYC8AAAAJ), [Tianyue Zheng](https://scholar.google.com/citations?user=A_Xk7NIAAAAJ&hl=zh-CN))

If there are any omissions in the collection of the papers, please feel free to contact [Yiming Cui](https://scholar.google.com/citations?hl=zh-CN&user=ZaKiYC8AAAAJ) at cuiyiming@seu.edu.cn.

## Table of Contents
- [Introduction](#introduction)
- [Overview](#overview)
- [Pre-trained LAMs](#pre-trained-lams)
- [Native LAMs](#native-lams)
- [Special Issue](#special-issue)
- [Note](#note)
- [License](#license)

## Introduction
This repository is based on the survey paper by Guo et al., which reviews the application of Large AI Models (LAMs) in wireless physical layer tasks. LAMs, including LLMs, LVMs, and LMMs, offer robust generalization, multitask processing, and multimodal capabilities for tasks like channel prediction, beamforming, and CSI feedback. This collection lists key models, frameworks, and datasets, with a focus on pre-trained and native LAMs.

## Overview
Key challenges and opportunities for LAMs in wireless physical layer applications:

- **[Large Language Models for Wireless Communications: From Adaptation to Autonomy](https://arxiv.org/abs/2507.21524)** (June 2025): Le Liang, Hao Ye, Yucheng Sheng, Ouya Wang, Jiacheng Wang, Shi Jin, and Geoffrey Ye Li.
- **[From Large AI Models to Agentic AI: A Tutorial on Future Intelligent Communications](https://arxiv.org/abs/2505.22311)** (May 2025): Feibo Jiang, Cunhua Pan, Li Dong, Kezhi Wang, Octavia A. Dobre, and Merouane Debbah.
- **[A Comprehensive Survey of Large AI Models for Future Communications: Foundations, Applications and Challenges](https://arxiv.org/abs/2505.03556)** (May 2025):Feibo Jiang, Cunhua Pan, Li Dong, Kezhi Wang, Merouane Debbah, Dusit Niyato, and Zhu Han.
- **[Wireless Large AI Model: Shaping the AI-Native Future of 6G and Beyond](https://arxiv.org/abs/2504.14653)** (Apr 2025): Fenghao Zhu, Xinquan Wang, Xinyi Li, et al.
- **[Towards Wireless Native Big AI Model: The Mission and Approach Differ From Large Language Model](https://arxiv.org/abs/2412.09041)** (Dec 2024): Zirui Chen, Zhaoyang Zhang, Chenyu Liu, Ziqing Xing. 
- **[Big AI Models for 6G Wireless Networks: Opportunities, Challenges, and Research Directions](https://arxiv.org/abs/2308.06250)** (Aug 2023): Zirui Chen, Zhaoyang Zhang, Zhaohui Yang.

  
## Pre-trained LAMs
Pre-trained LAMs, adapted from NLP and CV, are applied to physical layer tasks through preprocessing, fine-tuning, and output alignment. Key applications include:

- **[LLM4feedback+MoA](https://www.techrxiv.org/doi/full/10.36227/techrxiv.175289012.28506097)** (Jul 2025): LLM + Mixture-of-Agents (MoA) for CSI feedback.
 
  Paper Title: `Leveraging Pre-Trained Large Language Models for CSI Feedback in Massive MIMO Systems`

- **[LVM4CSI](https://arxiv.org/abs/2507.05121)** (Jul 2025): ConvNeXt/DINO-X for CSI tasks including channel estimation, user localization, and sensing.
 
  Paper Title: `LVM4CSI: Enabling Direct Application of Pre-Trained Large Vision Models for Wireless Channel Tasks`
- **[M2BeamLLM](https://arxiv.org/abs/2506.14532)** (Jun 2025): Multimodal beam prediction with sensor data fusion.
 
  Paper Title: `M2BeamLLM: Multimodal Sensing-empowered mmWave Beam Prediction with Large Language Models`
- **[LLM4SG](https://arxiv.org/abs/2505.17879)** (May 2025): GPT-2 for LIDAR-to-scatterer mapping.
 
  Paper Title: `LLM4SG: Large Language Models for Scatterer Generation via Synesthesia of Machines`
- **[2DLAM](https://openreview.net/forum?id=AbmUZ4oJoP)** (Mar 2025): ImageGPT for joint delay-Doppler estimation.
 
  Paper Title: `2DLAM: Joint Delay-Doppler Estimation in UAV mmWave System via Large AI Model`
- **[LLM4feedback](https://arxiv.org/abs/2501.10630)** (Jan 2025): GPT-2 for CSI feedback.
 
  Paper Title: `Exploring the Potential of Large Language Models for Massive MIMO CSI Feedback`
- **[Multi-task LLM](https://arxiv.org/abs/2412.20772)** (Dec 2024): LLaMA2 for signal detection and channel prediction.
 
  Paper Title: `Large Language Model Enabled Multi-Task Physical Layer Network`
- **[BP-LLM](https://arxiv.org/abs/2408.08707)** (Aug 2024): GPT-2 for beam prediction with Prototype-as-Preds mechanism.
 
  Paper Title: `Beam Prediction based on Large Language Models`
- **[LLM4CP](https://arxiv.org/abs/2406.14440)** (Jun 2024): GPT-2 for channel prediction with uplink-downlink CSI mapping.

  Paper Title: `LLM4CP: Adapting Large Language Models for Channel Prediction`
 
## Native LAMs
Native LAMs are built from scratch for wireless physical layer tasks, using extensive wireless datasets and Transformer architectures. Key examples include:

- **[Prompt-Enabled LAM](https://arxiv.org/abs/2501.10629)** (Apr 2025): Transformer-based LAM for CSI feedback with expert knowledge prompts.
- **[LWM](https://arxiv.org/abs/2411.08872)** (Apr 2025): Universal feature extractor for beam prediction and LoS/NLoS classification.
- **[WirelessGPT](https://ieeexplore.ieee.org/document/XXXXXXX)** (2025): Multi-task model for communication and sensing.
- **[BERT+MIMO](https://arxiv.org/abs/2501.10629)** (Mar 2025): Foundation model for MIMO systems.


## Special Issue
- **[Large AI Models for Large AI Models for Communications](https://www.comsoc.org/publications/magazines/ieee-communications-magazine/cfp/large-ai-models-communications)** (Deadline: 31 July 2025):  IEEE Communications Magazine. Guest editors: Kezhi Wang, Feibo Jiang, Merouane Debbah, and Zhu Han.
- **[Large AI Models for Future Wireless Communication Systems](https://www.comsoc.org/publications/journals/ieee-jsac/cfp/large-ai-models-future-wireless-communication-systems)** (Deadline: 15 May 2025): IEEE Journal on Selected Areas in Communications. Guest editors: Cunhua Pan, Feibo Jiang, Kezhi Wang, Pietro Michiardi, Octavia A. Dobre, Peiying Zhu, and Merouane Debbah.

## Note
 
If there are any omissions in the collection of the above papers, please feel free to contact [Yiming Cui](https://scholar.google.com/citations?hl=zh-CN&user=ZaKiYC8AAAAJ) at cuiyiming@seu.edu.cn, with a copy to [Jiajia Guo](https://jiajiaguo.github.io/) at jiajiaguo@seu.edu.cn.

## License
This project is licensed under the MIT License.
