---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Principal Research Engineer at Microsoft, working on large-scale machine learning system optimization through innovative kernel, compiler, compression, and scheduling technologies ([deepspeed.ai](https://www.deepspeed.ai)).
Prior to that, I was a Staff Research Engineer at Alibaba Cloud, overseeing the optimizing compilers for machine learning on GPUs and leading the research on machine learning inference optimization at *Platform of Artificial Intelligence* (PAI, Alibaba Cloud's ONLY SAAS/PAAS for machine learning end-to-end).
Before Alibaba, I obtained my Ph.D. in Computer Science from Tsinghua University in 2019, co-advised by [Prof. Wenguang Chen](https://pacman.cs.tsinghua.edu.cn/~cwg/) and [Prof. Jidong Zhai](https://pacman.cs.tsinghua.edu.cn/~zjd/).
I served as a visiting scholar under the supervision of [Prof. Xipeng Shen](https://research.csc.ncsu.edu/picture/xshen5/index.htm) at North Carolina State University in 2018.

My interests include machine learning systems, high-performance computing and heterogeneous computing.

**🔥We are hiring! We have world-class LLM industry scenarios and scientific research topics. Together we can make outstanding contributions to the development of AI technology and thereby contribute to human progress. Welcome to contact me.**


[Projects](#projects)
======

**Machine Learning Optimizing Compiler**
- [BladeDISC](https://github.com/alibaba/BladeDISC). The state-of-the-art optimizing compiler for end-to-end dynamic shape machine learning programs with advanced fusion and code generation optimization on multiple hardware backends ([AStitch](https://dl.acm.org/doi/10.1145/3503222.3507723) techniques).
- [RECom](https://github.com/AlibabaResearch/recom). An optimizing compiler that aims to accelerate the expensive embedding column processing during the inference of deep recommendation models on the GPU.
- [MonoNN](https://github.com/AlibabaResearch/mononn). An optimizing compiler that can accommodate an entire neural network into a single GPU kernel, drastically reducing non-computation overhead and providing further fine-grained optimization opportunities from the newly formed monolithic optimization space.
(code will be released soon)

**Machine Learning Kernel Library**
- [Flash-LLM](https://github.com/AlibabaResearch/flash-llm). A large language model (LLM) inference acceleration library for unstructured model pruning.

**Heterogeneous Computing**
- [VersaPipe](https://github.com/JamesTheZ/VersaPipe). A framework for pipelined computing on GPU.


[Publications](#publications)
======

\[EuroSys'24\]
"**Optimizing GNN with Joint Workload Partition of Graph and Operations**".
Kezhao Huang, Jidong Zhai, Liyan Zheng, Haojie Wang, Yuyang Jin, Qihao Zhang, Runqing Zhang, **Zhen Zheng**, Youngmin Yi, Xipeng Shen.

\[OSDI'24\]
"**MonoNN: Enabling a New Monolithic Optimization Space for Neural Network Inference Tasks on Modern GPU-Centric Architectures**".
Donglin Zhuang*, **Zhen Zheng**\*, Haojun Xia, Xiafei Qiu, Junjie Bai, Wei Lin, Shuaiwen Leon Song.
(revise-and-resubmitted in OSDI'23 and accepted in OSDI'24)

\[SIGMOD'24\]
"**BladeDISC: Optimizing Dynamic Shape Machine Learning Workloads via Compiler Approach**".
**Zhen Zheng**, Zaifeng Pan, Dalin Wang, Kai Zhu, Wenyi Zhao, Tianyou Guo, Xiafei Qiu, Minmin Sun, Junjie Bai, Feng Zhang, Xiaoyong Du, Jidong Zhai, Wei Lin.
\[[PDF](/files/bladedisc-sigmod24.pdf) | [Code](https://github.com/alibaba/BladeDISC)\]

\[VLDB'24\]
"**Flash-LLM: Enabling Cost-Effective and Highly-Efficient Large Generative Model Inference with Unstructured Sparsity**".
Haojun Xia\*, **Zhen Zheng**\*, Yuchao Li, Donglin Zhuang, Zhongzhu Zhou, Xiafei Qiu, Yong Li, Wei Lin, Shuaiwen Leon Song.
\[[PDF](/files/flashllm-vldb24.pdf) | [Code](https://github.com/AlibabaResearch/flash-llm)\]

\[ASPLOS'24\]
"**RECom: A Compiler Approach to Accelerating Recommendation Model Inference with Massive Embedding Columns**".
Zaifeng Pan, **Zhen Zheng**, Feng Zhang, Ruofan Wu, Hao Liang, Dalin Wang, Xiafei Qiu, Junjie Bai, Wei Lin, Xiaoyong Du.
\[[Code](https://github.com/AlibabaResearch/recom)\]

\[TKDE'23\]
"**Expanding the Edge: Enabling Efficient Winograd CNN Inference With Deep Reuse on Edge Device**".
Feng Zhang, Ruofan Wu, Jiawei Guan, **Zhen Zheng**, Xiaoguang Guo, Xiao Zhang, Xiaoyong Du, Xipeng Shen.
\[[PDF](/files/zhang-tkde23.pdf)\]

\[ASPLOS'22\]
"**AStitch: Enabling a New Multi-dimensional Optimization Space for Memory-intensive ML Training and Inference on Modern SIMT Architectures**".
**Zhen Zheng**, Xuanda Yang, Pengzhan Zhao, Guoping Long, Kai Zhu, Feiwen Zhu, Wenyi Zhao, Xiaoyong Liu, Jun Yang, Jidong Zhai, Shuaiwen Leon Song, Wei Lin.
\[[PDF](/files/astitch-asplos22.pdf)\]

\[ATC'22\]
"**Whale: Efficient Giant Model Training over Heterogeneous GPUs**".
Xianyan Jia, Le Jiang, Ang Wang, Wencong Xiao, Ziji Shi, Jie Zhang, Xinyuan Li, Langshi Chen, Yong Li, **Zhen Zheng**, Xiaoyong Liu, Wei Lin.
\[[PDF](/files/whale-atc22.pdf) | [Code](https://github.com/alibaba/EasyParallelLibrary)\]

\[WWW'22\]
"**DREW: Efficient Winograd CNN Inference with Deep Reuse**".
Ruofan Wu, Feng Zhang, Jiawei Guan, **Zhen Zheng**, Xiaoyong Du, Xipeng Shen.
\[[PDF](/files/drew-www22.pdf)\]

\[TPDS'22\]
"**Optimizing DNN Compilation for Distributed Training With Joint OP and Tensor Fusion**".
Xiaodong Yi, Shiwei Zhang, Lansong Diao, Chuan Wu, **Zhen Zheng**, Shiqing Fan, Siyu Wang, Jun Yang, Wei Lin.
\[[PDF](/files/disco-tpds22.pdf)\]

\[PPoPP'21\]
"**Understanding and Bridging the Gaps in Current GNN Performance Optimizations**".
Kezhao Huang, Jidong Zhai, **Zhen Zheng**, Youngmin Yi, Xipeng Shen.
\[[PDF](/files/huang-ppopp21.pdf)\]

\[PPoPP'21\]
"**DAPPLE: A Pipelined Data Parallel Approach for Training Large Models**".
Shiqing Fan, Yi Rong, Chen Meng, Zongyan Cao, Siyu Wang, **Zhen Zheng**, Chuan Wu, Guoping Long, Jun Yang, Lixue Xia, Lansong Diao, Xiaoyong Liu, Wei Lin.
\[[PDF](/files/dapple-ppopp21.pdf) | [Code](https://github.com/AlibabaPAI/DAPPLE)\]

\[CoNEXT'20\]
"**Optimizing Distributed Training Deployment in Heterogeneous GPU Clusters**".
Xiaodong Yi, Shiwei Zhang, Ziyue Luo, Guoping Long, Lansong Diao, Chuan Wu, **Zhen Zheng**, Jun Yang, Wei Lin.
\[[PDF](/files/heterog-conext20.pdf)\]

\[PACT'20\]
"**GOPipe: A Granularity-oblivious Programming Framework for Pipelined Stencil Executions on GPU**".
Chanyoung Oh, **Zhen Zheng**, Xipeng Shen, Jidong Zhai, Youngmin Yi.
\[[PDF](/files/gopipe-pact20.pdf)\]

\[ASPLOS'19\]
"**HiWayLib: A Software Framework for Enabling High Performance Communications for Heterogeneous Pipeline Computations**".
**Zhen Zheng**, Chanyoung Oh, Jidong Zhai, Xipeng Shen, Youngmin Yi, Wenguang Chen.
\[[PDF](/files/hiwaylib-asplos19.pdf)\]

\[MICRO'17\]
"**VersaPipe: A Versatile Programming Famework for Pipelined Computing on GPU**".
**Zhen Zheng**, Chanyoung Oh, Jidong Zhai, Xipeng Shen, Youngmin Yi, Wenguang Chen.
\[[PDF](/files/versapipe-micro17.pdf) | [Code](https://github.com/JamesTheZ/VersaPipe)\]

\[SC'16\]
"**Refactoring and Optimizing the Community Atmosphere Model (CAM) on the Sunway Taihulight Supercomputer**".
Haohuan Fu, Junfeng Liao, Wei Xue, Lanning Wang, Dexun Chen, Long Gu, Jinxiu Xu, Nan Ding, Xinliang Wang, Conghui He, Shizhen Xu, Yishuang Liang, Jiarui Fang, Yuanchao Xu, Weijie Zheng, Jingheng Xu, **Zhen Zheng**, Wanjing Wei, Xu Ji, He Zhang, Bingwei Chen, Kaiwei Li, Xiaomeng Huang, Wenguang Chen, Guangwen Yang.
\[[PDF](/files/fu-sc16.pdf)\]
