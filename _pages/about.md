---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Senior Principal Research Manager at Microsoft AI (_Microsoft Superintelligence_), working on large-scale machine learning system optimization through innovative kernel, algorithm, scheduling, and compiler technologies.
Previously, I was a Staff Research Engineer at Alibaba Cloud, where I led the development of optimizing compilers for GPU-based machine learning and spearheaded research on inference optimization for the _Platform of Artificial Intelligence_ (_PAI_)—Alibaba Cloud's premier SaaS/PaaS solution for end-to-end machine learning.
Before Alibaba, I earned my Ph.D. in Computer Science from Tsinghua University in 2019, co-advised by [Prof. Wenguang Chen](https://pacman.cs.tsinghua.edu.cn/~cwg/) and [Prof. Jidong Zhai](https://pacman.cs.tsinghua.edu.cn/~zjd/).
In 2018, I was a visiting scholar at North Carolina State University under the supervision of [Prof. Xipeng Shen](https://research.csc.ncsu.edu/picture/xshen5/index.htm).

My research interests span machine learning algorithm-system co-design, high-performance computing, and heterogeneous computing.
Please feel free to contact me regarding potential research collaborations.

**🔥We are hiring! We have world-class LLM industry scenarios and scientific research topics. Together we can make outstanding contributions to the development of AI technology and thereby contribute to human progress.**


<!-- [Projects](#projects)
======

**Machine Learning Optimizing Compiler**
- [BladeDISC](https://github.com/alibaba/BladeDISC). The state-of-the-art optimizing compiler for end-to-end dynamic shape machine learning programs with advanced fusion and code generation optimization on multiple hardware backends ([AStitch](https://dl.acm.org/doi/10.1145/3503222.3507723) techniques).
- [RECom](https://github.com/AlibabaResearch/recom). An optimizing compiler that aims to accelerate the expensive embedding column processing during the inference of deep recommendation models on the GPU.
- [MonoNN](https://github.com/AlibabaResearch/mononn). An optimizing compiler that can accommodate an entire neural network into a single GPU kernel, drastically reducing non-computation overhead and providing further fine-grained optimization opportunities from the newly formed monolithic optimization space.
(code will be released soon)

**Machine Learning Kernel Library**
- [Flash-LLM](https://github.com/AlibabaResearch/flash-llm). A large language model (LLM) inference acceleration library for unstructured model pruning.
- [Quant-LLM/FP6-LLM](https://github.com/usyd-fsalab/fp6_llm). An efficient GPU support for LLM inference with FP6 quantization (end-to-end: [DeepSpeed-FP6](https://github.com/microsoft/DeepSpeed/tree/master/blogs/deepspeed-fp6/03-05-2024)).

**Heterogeneous Computing**
- [VersaPipe](https://github.com/JamesTheZ/VersaPipe). A framework for pipelined computing on GPU. -->


[Publications](#publications)
======

\[MLSys'26 (_to appear_)\]
"**FlashAgents: Accelerating Multi-Agent LLM Systems via Streaming Prefill Overlap**".
Taosong Fang, **Zhen Zheng**, Zhengzhao Ma, Yaojie Lu, Hongyu Lin, Xianpei Han, Le Sun.

\[MLSys'26 (_to appear_)\]
"**Kitty: Accurate and Efficient 2-bit KV Cache Quantization with Dynamic Channel-wise Precision Boost**".
Haojun Xia, Xiaoxia Wu, Jisen Li, Robert Wu, Junxiong Wang, Jue Wang, Chenxi Li, Aman Singhal, Alay Dilipbhai Shah, Alpay Ariyak, Donglin Zhuang, Zhongzhu Zhou, Ben Athiwaratkun, **Zhen Zheng**†, Shuaiwen Leon Song†.
\[[PDF](https://arxiv.org/pdf/2511.18643) | [Code](https://github.com/Summer-Summer/Kitty)\]
(† Corresponding author)

\[MLSys'26 (_to appear_)\]
"**MixLLM: LLM Quantization with Global Mixed-precision between Output-features and Highly-efficient System Design**".
**Zhen Zheng**, Xiaonan Song, Chuanjie Liu.
\[[PDF](https://arxiv.org/pdf/2412.14590)\]

\[MLSys'26 (_to appear_)\]
"**BatchLLM: Optimizing Large Batched LLM Inference with Global Prefix Sharing and Throughput-oriented Token Batching**".
**Zhen Zheng**, Xin Ji, Taosong Fang, Fanghao Zhou, Chuanjie Liu, Gang Peng.
\[[PDF](https://arxiv.org/pdf/2412.03594)\]

\[FCS'26\]
"**A Comprehensive Taxonomy of Prompt Engineering Techniques for Large Language Models**".
Yaoyang Liu, Zhen Zheng, Feng Zhang, Jincheng Feng, Yiyang Fu, Jidong Zhai, Bingsheng He, Xiao Zhang, Xiaoyong Du.
\[[PDF](/files/liu-fcs26.pdf)\]

\[ATC'25\]
"**PluS: Highly Efficient and Expandable ML Compiler with Pluggable Graph Schedules**".
Ruofan Wu, **Zhen Zheng**, Feng Zhang, Chuanjie Liu, Zaifeng Pan, Jidong Zhai, Xiaoyong Du.
\[[PDF](/files/plus-atc25.pdf)\]

\[EuroSys'25\]
"**Improving GPU Sharing Performance through Adaptive Bubbleless Spatial-Temporal Sharing**".
Shulai Zhang, Quan Chen, Weihao Cui, Han Zhao, Chunyu Xue, **Zhen Zheng**, Wei Lin, Minyi Guo.
\[[PDF](/files/bless-eurosys25.pdf)\]

\[Preprint'24\]
"**ZeroQuant(4+2): Redefining LLMs Quantization with a New FP6-Centric Strategy for Diverse Generative Tasks**".
Xiaoxia Wu, Haojun Xia, Stephen Youn, **Zhen Zheng**, Shiyang Chen, Arash Bakhtiari, Michael Wyatt, Yuxiong He, Olatunji Ruwase, Leon Song, Zhewei Yao.
\[[PDF](https://arxiv.org/pdf/2312.08583)\]

\[SC'24\]
"**RecFlex: Enabling Feature Heterogeneity-Aware Optimization for Deep Recommendation Models with Flexible Schedules**".
Zaifeng Pan, **Zhen Zheng**, Feng Zhang, Bing Xie, Ruofan Wu, Shaden Smith, Chuanjie Liu, Olatunji Ruwase, Xiaoyong Du, Yufei Ding.
\[[PDF](/files/recflex-sc24.pdf) | [Code](https://github.com/PanZaifeng/RecFlex)\]

\[ATC'24\]
"**Quant-LLM: Accelerating the Serving of Large Language Models via FP6-Centric Algorithm-System Co-Design on Modern GPUs**".
Haojun Xia, **Zhen Zheng**, Xiaoxia Wu, Shiyang Chen, Zhewei Yao, Stephen Youn, Arash Bakhtiari, Michael Wyatt, Donglin Zhuang, Zhongzhu Zhou, Olatunji Ruwase, Yuxiong He, Shuaiwen Leon Song.
(**integrated in torch.ao, previous preprint: [_FP6-LLM_](https://arxiv.org/pdf/2401.14112)**)
\[[PDF](/files/quantllm-atc24.pdf) | [Code](https://github.com/usyd-fsalab/fp6_llm) | [E2E](https://github.com/microsoft/DeepSpeed/pull/5234)\]

\[EuroSys'24\]
"**WiseGraph: Optimizing GNN with Joint Workload Partition of Graph and Operations**".
Kezhao Huang, Jidong Zhai, Liyan Zheng, Haojie Wang, Yuyang Jin, Qihao Zhang, Runqing Zhang, **Zhen Zheng**, Youngmin Yi, Xipeng Shen.
\[[PDF](/files/wisegraph-eurosys24.pdf) | [Code](https://github.com/xxcclong/CxGNN-Compute)\]

\[OSDI'24\]
"**MonoNN: Enabling a New Monolithic Optimization Space for Neural Network Inference Tasks on Modern GPU-Centric Architectures**".
Donglin Zhuang\*, **Zhen Zheng**\*, Haojun Xia, Xiafei Qiu, Junjie Bai, Wei Lin, Shuaiwen Leon Song.
(revise-and-resubmitted in OSDI'23 and accepted in OSDI'24)
\[[PDF](/files/mononn-osdi24.pdf) | [Code](https://github.com/AlibabaResearch/mononn)\]
(\* Equal contribution)

\[VLDB'24 (PVLDB'23)\]
"**Flash-LLM: Enabling Cost-Effective and Highly-Efficient Large Generative Model Inference with Unstructured Sparsity**".
Haojun Xia\*, **Zhen Zheng**\*, Yuchao Li, Donglin Zhuang, Zhongzhu Zhou, Xiafei Qiu, Yong Li, Wei Lin, Shuaiwen Leon Song.
\[[PDF](/files/flashllm-vldb24.pdf) | [Code](https://github.com/AlibabaResearch/flash-llm)\]
(\* Equal contribution)

\[SIGMOD'24 (PACMMOD'23)\]
"**BladeDISC: Optimizing Dynamic Shape Machine Learning Workloads via Compiler Approach**".
**Zhen Zheng**, Zaifeng Pan, Dalin Wang, Kai Zhu, Wenyi Zhao, Tianyou Guo, Xiafei Qiu, Minmin Sun, Junjie Bai, Feng Zhang, Xiaoyong Du, Jidong Zhai, Wei Lin.
\[[PDF](/files/bladedisc-sigmod24.pdf) | [Code](https://github.com/alibaba/BladeDISC)\]

\[ASPLOS'23\]
"**RECom: A Compiler Approach to Accelerating Recommendation Model Inference with Massive Embedding Columns**".
Zaifeng Pan, **Zhen Zheng**, Feng Zhang, Ruofan Wu, Hao Liang, Dalin Wang, Xiafei Qiu, Junjie Bai, Wei Lin, Xiaoyong Du.
\[[PDF](/files/recom-asplos23.pdf) | [Code](https://github.com/AlibabaResearch/recom)\]

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
