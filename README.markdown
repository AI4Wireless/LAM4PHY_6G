# Large AI Models for Wireless Physical Layer

A collection of paper on Large AI Models (LAMs) for wireless physical layer applications, extended from the overview paper by [Jiajia Guo et al.](https://arxiv.org/abs/2508.02314).  on going......

Contributors：[Jiajia Guo](https://jiajiaguo.github.io/), [Yiming Cui](https://scholar.google.com/citations?hl=zh-CN&user=ZaKiYC8AAAAJ), [Tianyue Zheng](https://scholar.google.com/citations?user=A_Xk7NIAAAAJ&hl=zh-CN).
If there are any omissions in the collection of the papers, please feel free to contact [Yiming Cui](https://scholar.google.com/citations?hl=zh-CN&user=ZaKiYC8AAAAJ) at cuiyiming@seu.edu.cn.

## Table of Contents
- [Overview](#overview)
- [Pre-trained LAMs](#pre-trained-lams)
- [Native LAMs](#native-lams)
- [Special Issues](#special-issues)
- [Note](#note)
- [License](#license)


## Overview
- **[Large AI Models for Wireless Physical Layer](https://arxiv.org/abs/2508.02314)** (Aug 2025): Jiajia Guo, Yiming Cui, Shi Jin, and Jun Zhang.
- **[Large Language Models for Wireless Communications: From Adaptation to Autonomy](https://arxiv.org/abs/2507.21524)** (Jul 2025): Le Liang, Hao Ye, Yucheng Sheng, Ouya Wang, Jiacheng Wang, Shi Jin, and Geoffrey Ye Li.
- **[From Large AI Models to Agentic AI: A Tutorial on Future Intelligent Communications](https://arxiv.org/abs/2505.22311)** (May 2025): Feibo Jiang, Cunhua Pan, Li Dong, Kezhi Wang, Octavia A. Dobre, and Merouane Debbah.
- **[A Comprehensive Survey of Large AI Models for Future Communications: Foundations, Applications and Challenges](https://arxiv.org/abs/2505.03556)** (May 2025):Feibo Jiang, Cunhua Pan, Li Dong, Kezhi Wang, Merouane Debbah, Dusit Niyato, and Zhu Han.
- **[Wireless Large AI Model: Shaping the AI-Native Future of 6G and Beyond](https://arxiv.org/abs/2504.14653)** (Apr 2025): Fenghao Zhu, Xinquan Wang, Xinyi Li, et al.
- **[Towards Wireless Native Big AI Model: The Mission and Approach Differ From Large Language Model](https://arxiv.org/abs/2412.09041)** (Dec 2024): Zirui Chen, Zhaoyang Zhang, Chenyu Liu, Ziqing Xing.
- **[AI and Deep Learning for Terahertz Ultra-Massive MIMO: From Model-Driven Approaches to Foundation Models](https://arxiv.org/abs/2412.09839)** (Dec 2024): Wentao Yu, Hengtao He, Shenghui Song, Jun Zhang, Linglong Dai, Lizhong Zheng, Khaled B. Letaief.  
- **[Big AI Models for 6G Wireless Networks: Opportunities, Challenges, and Research Directions](https://arxiv.org/abs/2308.06250)** (Aug 2023): Zirui Chen, Zhaoyang Zhang, Zhaohui Yang.

  
## Pre-trained LAMs
Pre-trained LAMs, adapted from NLP and CV, are applied to physical layer tasks through preprocessing, fine-tuning, and output alignment. Key applications include:

- **[LLM4feedback+MoA](https://www.techrxiv.org/doi/full/10.36227/techrxiv.175289012.28506097)** (Jul 2025): LLM + Mixture-of-Agents (MoA) for CSI feedback.
 
  Paper Title: `Leveraging Pre-Trained Large Language Models for CSI Feedback in Massive MIMO Systems`

  Paper Authors: `Yiming Cui,Jiajia Guo,Chao-Kai Wen,Shi Jin, and En Tong`

- **[LVM4CSI](https://arxiv.org/abs/2507.05121)** (Jul 2025): ConvNeXt/DINO-X for CSI tasks including channel estimation, user localization, and sensing.
 
  Paper Title: `LVM4CSI: Enabling Direct Application of Pre-Trained Large Vision Models for Wireless Channel Tasks`

  Paper Authors: `Jiajia Guo, Peiwen Jiang, Chao-Kai Wen, Shi Jin, and Jun Zhang`
- **[M2BeamLLM](https://arxiv.org/abs/2506.14532)** (Jun 2025): Multimodal beam prediction with sensor data fusion.
 
  Paper Title: `M2BeamLLM: Multimodal Sensing-empowered mmWave Beam Prediction with Large Language Models`

  Paper Authors: `Can Zheng, Jiguang He, Chung G. Kang, Guofa Cai, Zitong Yu, Merouane Debbah`
  
- **[LLM4SG](https://arxiv.org/abs/2505.17879)** (May 2025): GPT-2 for LIDAR-to-scatterer mapping.
 
  Paper Title: `LLM4SG: Large Language Models for Scatterer Generation via Synesthesia of Machines`

  Paper Authors: `Zengrui Han, Lu Bai, Ziwei Huang, and Xiang Cheng`
  
- **[2DLAM](https://openreview.net/forum?id=AbmUZ4oJoP)** (Mar 2025): ImageGPT for joint delay-Doppler estimation.
 
  Paper Title: `2DLAM: Joint Delay-Doppler Estimation in UAV mmWave System via Large AI Model`

  Paper Authors: `Daixin Xie, Chenxi Liu, Wei Wang, Fengxian Guo, and Xiaoling Hu`

  
- **[LLM4feedback](https://arxiv.org/abs/2501.10630)** (Jan 2025): GPT-2 for CSI feedback.
 
  Paper Title: `Exploring the Potential of Large Language Models for Massive MIMO CSI Feedback`

  Paper Authors: `Yiming Cui,Jiajia Guo,Chao-Kai Wen,Shi Jin, and En Tong`
  
- **[Multi-task LLM](https://arxiv.org/abs/2412.20772)** (Dec 2024): LLaMA2 for signal detection and channel prediction.
 
  Paper Title: `Large Language Model Enabled Multi-Task Physical Layer Network`

  Paper Authors: `Tianyue Zheng and Linglong Dai`
  
- **[BP-LLM](https://arxiv.org/abs/2408.08707)** (Aug 2024): GPT-2 for beam prediction with Prompt-as-prefix mechanism.  [Source code](https://github.com/le-liang/Beam-prediction-LLM)
 
  Paper Title: `Beam Prediction based on Large Language Models`

  Paper Authors: `Yucheng Sheng, Kai Huang, Le Liang, Peng Liu, Shi Jin, Geoffrey Ye Li`
  
- **[LLM4CP](https://arxiv.org/abs/2406.14440)** (Jun 2024): GPT-2 for channel prediction with uplink-downlink CSI mapping. [Source code](https://github.com/liuboxun/LLM4CP)

  Paper Title: `LLM4CP: Adapting Large Language Models for Channel Prediction`

  Paper Authors: `Boxun Liu, Xuanyu Liu, Shijian Gao, Xiang Cheng, Liuqing Yang`
 
## Native LAMs
Native LAMs are built from scratch for wireless physical layer tasks, using extensive wireless datasets and Transformer architectures. Key examples include:

- **[Prompt-Enabled LAM](https://arxiv.org/abs/2501.10629)** (Apr 2025): Transformer-based LAM for CSI feedback with expert knowledge prompts.

  Paper Title: `Prompt-Enabled Large AI Models for CSI Feedback`

  Paper Authors: `Jiajia Guo, Yiming Cui, Chao-Kai Wen, Shi Jin`
  
- **[LWM](https://arxiv.org/abs/2411.08872)** (Apr 2025): Universal feature extractor for beam prediction and LoS/NLoS classification.

  Paper Title: `Large Wireless Model (LWM): A Foundation Model for Wireless Channels`

  Paper Authors: `Sadjad Alikhani, Gouranga Charan, Ahmed Alkhateeb`
  
- **[WirelessGPT](https://ieeexplore.ieee.org/document/XXXXXXX)** (2025): Multi-task model for communication and sensing.
- **[BERT+MIMO](https://arxiv.org/abs/2501.10629)** (Mar 2025): Foundation model for MIMO systems.


## Special Issues


- **[Integrating Large Models and Edge Sensing in Next Generation Networks](https://www.springeropen.com/collections/imen)** (Deadline: 31 December 2025): EURASIP Journal on Wireless Communications and Networking. Guest editors: Peiyan Yuan, Tarik Taleb, Chenyang Wang, Chuan Sun, Xiaoqiang Zhu, and Xiaoyan Zha.

- **[Edge-Enabled Collaboration Between Large-scale and Lightweight Models in Sensor-Cloud Networks](https://www.comsoc.org/publications/magazines/ieee-network/cfp/edge-enabled-collaboration-between-large-scale-and)** (Deadline: 1 October 2025): IEEE Network. Guest editors:Tian Wang, Yao Liu, Geyong Min,
Nektarios Georgalas, and Yan Zhang.

- **[Large AI Models for the Internet of Everything](https://www.comsoc.org/publications/magazines/ieee-network/cfp/large-ai-models-internet-everything)** (Deadline: 1 September 2025): IEEE Network. Guest editors: Feibo Jiang, Kezhi Wang, Xingqin Lin, Merouane Debbah, and Zhu Han.
 
- **[Large AI Models for Communications](https://www.comsoc.org/publications/magazines/ieee-communications-magazine/cfp/large-ai-models-communications)** (Deadline: 31 July 2025): IEEE Communications Magazine. Guest editors: Kezhi Wang, Feibo Jiang, Merouane Debbah, and Zhu Han.
 
- **[Large AI Models for Future Wireless Communication Systems](https://www.comsoc.org/publications/journals/ieee-jsac/cfp/large-ai-models-future-wireless-communication-systems)** (Deadline: 15 May 2025): IEEE Journal on Selected Areas in Communications. Guest editors: Cunhua Pan, Feibo Jiang, Kezhi Wang, Pietro Michiardi, Octavia A. Dobre, Peiying Zhu, and Merouane Debbah.
 
- **[Generative AI and Large Language Models Enhanced 6G Wireless Communication and Sensing](https://www.comsoc.org/publications/journals/ieee-ojcoms/cfp/generative-ai-and-large-language-models-enhanced-6g-wireless)** (Deadline: 28 February 2025): IEEE Open Journal of the Communications Society. Guest editors: Jiacheng Wang, Geng Sun, Dusit Niyato, Hina Tabassum, Gabriel-Miro Muntean, and Nelson Fonseca.
 
- **[6G in the Era of Large Models: Design, Applications and Beyond](https://www.keaipublishing.com/en/journals/digital-communications-and-networks/call-for-papers/special-issue-on-6g-in-the-era-of-large-models-design-applications-and-beyond/)** (Deadline: 31 October 2024): Digital Communications and Networks. Guest editors: Jianhui Lv, Byung-Gyu Kim, Keqin Li, Adam Slowik, and Yuhui Shi.

 - **[Empowering Future Mobile Networks with Large Models](https://www.comsoc.org/publications/magazines/ieee-network/cfp/empowering-future-mobile-networks-large-models)** (Deadline: 10 September 2024): IEEE Network. Guest editors: Yin Zhang, Xueli An, Maziar Nekovee, Jia Liu, Chau Yuen, and Yan Zhang.
   
- **[Edge Learning and Big AI Model in Wireless Communication and Networking](https://www.mdpi.com/journal/electronics/special_issues/Wireless_Communication_Networking)** (Deadline: 15 July 2024): Electronics . Guest editors: Zhaohui Yang, Zhiyang Li, and Wanli Ni.

 


## Note
 
If there are any omissions in the collection of the above papers, please feel free to contact [Yiming Cui](https://scholar.google.com/citations?hl=zh-CN&user=ZaKiYC8AAAAJ) at cuiyiming@seu.edu.cn, with a copy to [Jiajia Guo](https://jiajiaguo.github.io/) at jiajiaguo@seu.edu.cn.

## License
This project is licensed under the MIT License.
