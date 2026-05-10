第64届计算语言学协会年会（The 64th Annual Meeting of the Association for Computational Linguistics, ACL 2026）于4月7日公布论文录用结果，会议将于7月2日至7日在美国圣迭戈举办。本届ACL共收到12148份有效论文投稿，打破历史记录，最终主会录用论文2349 篇（录用率 19%），Findings录用论文2258 篇（录用率 18%）。

本文主要整理了（多模态）大语言模型幻觉减缓、机理分析与发现、调研综述相关的论文，共69篇，其中37篇附arXiv预印版链接。

# 幻觉减缓（纯文本）
# Hallucination Mitigation (Text)

1. [解释生成的忠实性、注意力干预，Main] Faithful Serum: Mitigating the Faithfulness Gap in Textual Explanations of LLM Decisions via Attribution Guidance
Bar Alon, Itamar Zimerman, Lior Wolf
以色列特拉维夫大学
https://arxiv.org/abs/2604.14325

2. [RAG的检索排列敏感性、DPO，Main] Stable-RAG: Mitigating Retrieval-Permutation-Induced Hallucinations in Retrieval-Augmented Generation
Qianchi Zhang, Hainan Zhang, Liang Pang, Hongwei Zheng, Zhiming Zheng
未来区块链与隐私计算北京高精尖创新中心、北京航空航天大学、北京微芯区块链与边缘计算研究院、中国科学院计算技术研究所
https://arxiv.org/abs/2601.02993

3. [蛋白质结构序列幻觉、DPO，Main] Physio-DPO: Aligning Large Language Models with the Protein Energy Landscape to Eliminate Structural Hallucinations
QiWei Meng
西安交通大学
https://arxiv.org/abs/2601.00647

4. [智能体的推理轨迹忠实性、自我验证，Main] Verify Before You Commit: Towards Faithful Reasoning in LLM Agents via Self-Auditing
Wenhao Yuan, Chenchen Lin, Jian Chen, Jinfeng Xu, Xuehe Wang, Edith Cheuk Han Ngai
香港大学、中山大学
https://arxiv.org/abs/2604.08401

5. [因果关系幻觉、思维链微调，Findings] Generating Effective CoT Traces for Mitigating Causal Hallucination
Yiheng Zhao, Jun Yan
加拿大康考迪亚大学
https://arxiv.org/abs/2604.12748

6. [个性化事实幻觉、引导向量，Findings] When Personalization Misleads: Understanding and Mitigating Hallucinations in Personalized LLMs
Zhongxiang Sun, Yi Zhan, Chenglei Shen, Weijie Yu, Xiao Zhang, Ming He, Jun Xu
中国人民大学、联想研究院、对外经济贸易大学
https://arxiv.org/abs/2601.11000

7. [RAG幻觉、合成数据微调，Findings] HalluGuard: Evidence-Grounded Small Reasoning Models to Mitigate Hallucinations in Retrieval-Augmented Generation
Loris Bergeron, Ioana Buhnila, Jérôme François, Radu State
卢森堡银行、朝鲜大学、法国洛林大学、卢森堡大学
https://arxiv.org/abs/2510.00880

8. [预训练数据不平衡、重塑学习分布，Findings] PretrainRL: Alleviating Factuality Hallucination of Large Language Models at the Beginning
Langming Liu, Kangtao Lv, Haibin Chen, Weidong Zhang, Yejing Wang, Shilei Liu, Xin Tong, Yujin Yuan, Yongwei Wang, Wenbo Su, Bo Zheng
阿里巴巴、浙江大学、上海人工智能实验室
https://arxiv.org/abs/2602.01875

9. [RAG幻觉、上下文选择、推理路径优化，Findings] Self-Correcting RAG: Enhancing Faithfulness via MMKP Context Selection and NLI-Guided MCTS
Shijia Xu, Zhou Wu, Xiaolong Jia, Yu Wang, Kai Liu, April Xiaowen Dong
重庆大学、英国伦敦玛丽女王大学、重庆市大数据智能与隐私计算重点实验室
https://arxiv.org/abs/2604.10734

10. [多跳推理的忠实性、过程监督奖励，Findings] Reason-KE++: Aligning the Process, Not Just the Outcome, for Faithful LLM Knowledge Editing
Yuchen Wu, Liang Ding, Li Shen, Dacheng Tao
上海交通大学、澳大利亚悉尼大学、中山大学、新加坡南洋理工大学
https://arxiv.org/abs/2511.12661

11. [多角色对话摘要生成、推理轨迹微调+GRPO，Findings] Beyond Overlap Metrics: Rewarding Reasoning and Preferences for Faithful Multi-Role Dialogue Summarization
Xiaoyong Mei, Tingting Zuo, Da Chen, Guangyu Hu, Xiangyu Wen, Chao Duan, Mingyan Zhang, Fudan Zheng
浙江师范大学、华为、香港科技大学、香港中文大学、中山大学
https://arxiv.org/abs/2604.17188

12. [科学文献测量值提取、课程奖励学习，Findings] MeasHalu: Mitigation of Scientific Measurement Hallucinations for Large Language Models with Enhanced Reasoning
Ruijun Huang, Zhiqiao Kang, Yuxuan Zhu, Junxiong Li, Jiahao Zhao, Minghuan Tan, Feng Jiang, Min Yang
中国科学院深圳先进技术研究院、深圳理工大学
https://arxiv.org/abs/2604.16929

13. [事实感知偏好优化，Findings] Reducing Hallucinations in LLMs via Factuality-Aware Preference Learning
Sindhuja Chaduvula, Ahmed Y. Radwan, Azib Farooq, Yani Ioannou, Shaina Raza
加拿大向量人工智能研究所、美国辛辛那提大学、加拿大卡尔加里大学
https://arxiv.org/abs/2601.03027

# 幻觉减缓（多模态）
# Hallucination Mitigation (Multimodal)

14. [幻觉与通用能力、语义解耦、选择性参数更新，Main] Mitigating Hallucinations in Large Vision-Language Models without Performance Degradation
Xingyu Zhu, Junfeng Fang, Shuo Wang, Beier Zhu, Zhicai Wang, Yonghui Yang, Xiangnan He
中国科学技术大学、新加坡国立大学
https://arxiv.org/abs/2604.20366

15. [注意力探针、变分信息瓶颈，Main] VIB-Probe: Detecting and Mitigating Hallucinations in Vision-Language Models via Variational Information Bottleneck
Feiran Zhang, Yixin Wu, Zhenghua Wang, Xiaohua Wang, Changze Lv, Xuanjing Huang, Xiaoqing Zheng
复旦大学
https://arxiv.org/abs/2601.05547

16. [缓解脆弱性、鲁棒抑制，Main] Beyond Superficial Unlearning: Sharpness-Aware Robust Erasure of Hallucinations in Multimodal LLMs
Xianya Fang, Feiyang Ren, Xiang Chen, Yu Tian, Zhen Bi, Haiyang Yu, Sheng-Jun Huang
南京航空航天大学、清华大学、湖州师范学院、合肥综合性国家科学中心数据空间研究院、中国科学技术大学
https://arxiv.org/abs/2601.16527

17. [语言-视觉内省、可解释双因果引导，Main] Vision-Language Introspection: Mitigating Overconfident Hallucinations in MLLMs via Interpretable Bi-Causal Steering
Shuliang Liu, Songbo Yang, Dong Fang, Sihang Jia, Yuqi Tang, Lingfeng Su, Ruoshui Peng, Yibo Yan, Xin Zou, Xuming Hu
香港科技大学（广州）、香港科技大学、 LIGHTSPEED
https://arxiv.org/abs/2601.05159

18. [细粒度视觉感知增强解码、注意力引导，Main] Through the Magnifying Glass: Adaptive Perception Magnification for Hallucination-Free VLM Decoding
Shunqi Mao, Chaoyi Zhang, Weidong Cai
澳大利亚悉尼大学
https://arxiv.org/abs/2503.10183

19. [多模态推理轨迹忠实性，Findings] Faithful-First Reasoning, Planning, and Acting for Multimodal LLMs
Junxian Li, Xinyue Xu, Sai Ma, Di Zhang, Sichao Li
上海交通大学、香港科技大学、澳大利亚国立大学、复旦大学、澳大利亚悉尼大学
https://arxiv.org/abs/2511.08409

20. [对比解码、注意力引导，Findings] Spotlight and Shadow: Attention-Guided Dual-Anchor Introspective Decoding for MLLM Hallucination Mitigation
Yebo Wu, Han Jin, Zhijiang Guo, Li Li
澳门大学、香港科技大学（广州）
https://arxiv.org/abs/2604.10071

21. [注意力动态调控、语义核心区域定位，Findings] Revealing and Enhancing Core Visual Regions: Harnessing Internal Attention Dynamics for Hallucination Mitigation in LVLMs
Guangtao Lyu, Qi Liu, Chenghao Xu, Jiexi Yan, Muli Yang, Xueting Li, Fen Fang, Cheng Deng
西安电子科技大学、河海大学、新加坡资讯通信研究院
https://arxiv.org/abs/2602.15556

22. [多模态推理、过程监督+RLVR，Findings] AutoRubric: Rubric-Based Generative Rewards for Faithful Multimodal Reasoning
Mengzhao Jia, Zhihan Zhang, Ignacio Cases, Zheyuan Liu, Meng Jiang, Peng Qi
美国圣母大学、Uniphore
https://arxiv.org/abs/2510.14738

23. [音频幻觉、偏好对齐，Findings] AHA: Aligning Large Audio-Language Models for Reasoning Hallucinations via Counterfactual Hard Negatives
Yanxi Chen, Wenhui Zhu, Xiwen Chen, Zhipeng Wang, Xin Li, Peijie Qiu, Hao Wang, Xuanzhao Dong, Yujian Xiong, Anderson Schneider, Yuriy Nevmyvaka, Yalin Wang
美国亚利桑那州立大学、美国克莱姆森大学、美国圣路易斯华盛顿大学、美国莱斯大学、摩根士丹利
https://arxiv.org/abs/2512.24052

24. [放射学医疗幻觉、对比解码，Findings] CCD: Mitigating Hallucinations in Radiology MLLMs via Clinical Contrastive Decoding
Xi Zhang, Zaiqiao Meng, Jake Lever, Edmond S. L. Ho
英国格拉斯哥大学
https://arxiv.org/abs/2509.23379

25. [医疗幻觉、多智能体，Findings] Dialectic-Med: Mitigating Diagnostic Hallucinations via Counterfactual Adversarial Multi-Agent Debate
西交利物浦大学
https://arxiv.org/abs/2604.11258

26. [文本表征优化、提升视觉感知，Findings] Towards Mitigating Hallucinations in Large Vision-Language Models by Refining Textual Embeddings
Aakriti Agrawal, Gouthaman KV, Rohith Aralikatti, Gauri Jagatap, Jiaxin Yuan, Vijay Kamarshi, Andrea Fanelli, Furong Huang
美国马里兰大学、美国杜比实验室、Hilabs、Capital One
https://arxiv.org/abs/2511.05017

27. [多模态推理忠实性、感知盲区和感知-推理脱节，Findings] SPD-Faith Bench: Diagnosing and Improving Faithfulness in Chain-of-Thought for Multimodal Large Language Models
Weijiang Lv, Yaoxuan Feng, Xiaobo Xia, Jiayu Wang, Yan Jing, Wenchao Chen, Bo Chen
西安电子科技大学、新加坡国立大学、西安交通大学
https://arxiv.org/abs/2602.07833


# 幻觉机理分析/发现（纯文本）
# Hallucination Analysis & Discovery (Text)

28. [推理能力增强导致工具幻觉加重，Main] The Reasoning Trap: How Enhancing LLM Reasoning Amplifies Tool Hallucination
Chenlong Yin, Zeyang Sha, Shiwen Cui, Changhua Meng, Zechao Li
美国宾夕法尼亚州立大学、南京理工大学
https://arxiv.org/abs/2510.22977

29. [事实编码机制、双信息通路分析，Main] Two Pathways to Truthfulness: On the Intrinsic Encoding of LLM Hallucinations
Wen Luo, Guangyue Peng, Wei Li, Shaohang Wei, Feifan Song, Liang Wang, Nan Yang, Xingxing Zhang, Jing Jin, Furu Wei, Houfeng Wang
北京大学、微软亚洲研究院
https://arxiv.org/abs/2601.07422

30. [工具调用导致推理能力退化，Main] From Proof to Program: Characterizing Tool-Induced Reasoning Hallucinations in Large Language Models
Farima Fatahi Bayat, Pouya Pezeshkpour, Estevam Hruschka
Megagon Labs
https://arxiv.org/abs/2511.10899

31. [思维链忠实性分析，Main] Is Chain-of-Thought Really Not Explainability? Chain-of-Thought Can Be Faithful without Hint Verbalization
Kerem Zaman, Shashank Srivastava
美国北卡罗来纳大学
https://arxiv.org/abs/2512.23032

32. [新知识导致的事实幻觉分析，Findings] Understanding New-Knowledge-Induced Factual Hallucinations in LLMs: Analysis and Interpretation
Renfei Dang, Peng Hu, Zhejian Lai, Changjiang Gao, Min Zhang, Shujian Huang
南京大学、华为
https://arxiv.org/abs/2511.02626

33. [扩散语言模型幻觉模式分析，Findings] Lost in Diffusion: Uncovering Hallucination Patterns and Failure Modes in Diffusion Large Language Models
Zhengnan Guo, Fei Tan
华东师范大学、浙江工业大学
https://arxiv.org/abs/2604.10556

# 幻觉机理分析/发现（多模态）
# Hallucination Analysis & Discovery (Multimodal)

34. [扩散多模态大语言模型的机制可解释性，Main] Diffusion-CAM: Faithful Visual Explanations for dMLLMs
Haomin Zuo, Yidi Li, Luoxiao Yang, Xiaofeng Zhang
上海交通大学、中山大学、西北大学、以色列理工学院
https://arxiv.org/abs/2604.11005

35. [提示诱导的幻觉机制分析，Main] Mechanisms of Prompt-Induced Hallucination in Vision–Language Models
William Rudman, Michal Golovanevsky, Dana Arad, Yonatan Belinkov, Ritambhara Singh, Carsten Eickhoff, Kyle Mahowald
美国德克萨斯大学奥斯汀分校、美国布朗大学、以色列理工学院、德国图宾根大学、美国哈佛大学
https://arxiv.org/abs/2601.05201


# 调研综述
# Survey

36. [幻觉引用统计调查，Main] HalluCitation Matters: Revealing the Impact of Hallucinated References with 300 Hallucinated Papers in ACL Conferences
Yusuke Sakai, Hidetaka Kamigaito, Taro Watanabe
日本奈良先端科学技术大学院大学（NAIST）
https://arxiv.org/abs/2601.18724

37. [视频大语言模型综述，Findings] Distorted or Fabricated? A Survey on Hallucination in Video LLMs
Yiyang Huang, Yitian Zhang, Yizhou Wang, Mingyuan Zhang, Liang Shi, Huimin Zeng, Yun Fu
美国东北大学
https://arxiv.org/abs/2604.12944



以下论文暂无预印本链接：

- 幻觉缓解（纯文本）
- Hallucination Mitigation (Text) - No Link

38. [Main] Mask-to-Correct$^+$: Leveraging Retriever Diversity for Masking-guided Faithful Fact Correction

39. [Main] Mitigating Legal Hallucinations via Symbolic Constraints and Analogical Precedents

40. [Main] Re$^3$: Relevance & Recency Retrieval for Mitigating Temporal Hallucination

41. [Main] Anchoring the Cache: Mitigating Contextual Hallucination in KV-Compressed Long-Context Summarization

42. [Main] Knowledge Injection Exists in MoE? Exploring Expert-Aware Contrast Decoding in MoE for Mitigating LLMs’ Hallucinations

43. [Main] Awakening Dormant Experts:Counterfactual Routing to Mitigate MoE Hallucinations

44. [Findings] Graph Explorer: Training Faithful KG Agents with Visibility-Grounded Supervision

45. [Findings] CoDA: Restoring Contextual Dominance via Copy-Encouraged Attention Intervention for Mitigating RAG Hallucinations

46. [Findings] Faithful Persona Steering under Incongruity via Dual-Stream Refinement

47. [Findings] Dynamic PMI-Guided Contrastive Decoding Reduces Hallucination in Large Language Models: A Unified Framework of Fine-Grained Input Transformations

48. [Findings] Thought-Action Graph Reasoning: Faithful and Efficient Reasoning of Large Language Models via Reusing Past Experience

49. [Findings] Hallucinations as Orthogonal Noise: Inference-Time Manifold Alignment via Dynamic Contextual Orthogonalization

50. [Findings] TRIDENT: Risk-Controlled Min-Cost Facet Cover for Efficient and Faithful RAG

51. [Findings] Context-Fidelity Boosting: Enhancing Faithful Generation through Watermark-Inspired Decoding

52. [Findings] Chain-of-Relations: Faithful and Efficient LLM Reasoning over Knowledge Graphs via Relation-Centric Exploration

- 幻觉缓解（多模态）
- Hallucination Mitigation (Multimodal) - No Link

53. [Main] PAR: Training-Free Positional Perturbation and Attention Recycling for Faithful OCR

54. [Main] Mitigating Action-Relation Hallucinations in LVLMs via Relation-aware Visual Enhancement

55. [Main] Latent Attention Denoising: A Training-Free Energy-Based Framework for Mitigating Hallucinations in Vision-Language Models

56. [Main] DiVE: Decoupling Intra-layer Visual Evidence for Mitigating Hallucinations in Large Vision-Language Models

57. [Main] Vocabulary Hijacking in LVLMs: Unveiling Critical Attention Heads by Excluding Inert Tokens to Mitigate Hallucination

58. [Main] CEBC: Conformal Evidence-Bounded Control for Low-Hallucination Vision–Language Generation

59. [Findings] AHEAD: Attention Head Energy-Aware Dynamics for Hallucination Mitigation in MLLMs

60. [Findings] Global Context or Local Detail? Adaptive Visual Grounding for Hallucination Mitigation

61. [Findings] Mitigating Hallucinations in VLMs: Enhancing Visual Attention via Head-Wise Perturbation

62. [Findings] FADE: Mitigating Hallucinations by Reducing Language Priors Dominance in Large Vision-Language Models

63. [Findings] Aligning with Your Own Voice: Self-Corrected Preference Learning for Hallucination Mitigation in LVLMs

64. [Findings] Inject to Heal: Alleviating hallucination in LVLMs via Context Embedding Injection

- 幻觉机理分析/发现（纯文本）
- Hallucination Analysis & Discovery (Text) - No Link

65. [Main] Beyond Noise: Characterizing Creative Potential in Unverifiable LLM Hallucinations

66. [Main] Why LLMs Hallucinate on Structured Knowledge: A Mechanistic Analysis of Reasoning over Linearized Representations

67. [Findings] The Feedback-Faithfulness Trade-off: Environment Feedback Improves Agent Performance but Is Associated with Degraded Reasoning Faithfulness

- 幻觉机理分析/发现（多模态）
- Hallucination Analysis & Discovery (Multimodal) - No Link

68. [Findings] Perceptual Hallucination in Vision–Language Models: Definition, Analysis and Verification

69. [Findings] Born Pragmatic, Trained to Hallucinate? Quantifying the Origins of Contextual Bias in LLMs via the PaCE Benchmark