第64届计算语言学协会年会（The 64th Annual Meeting of the Association for Computational Linguistics, ACL 2026）于4月7日公布论文录用结果，会议将于7月2日至7日在美国圣迭戈举办。本届ACL共收到12148份有效论文投稿，打破历史记录，最终主会录用论文2349 篇（录用率 19%），Findings录用论文2258 篇（录用率 18%）。

本文主要整理了（多模态）大语言模型幻觉检测、评估基准相关的论文，共44篇，其中25篇附arXiv预印版链接。

# 幻觉检测（纯文本）
# Hallucination Detection (Text)

1. [逻辑自洽性建模、元判断，Main] Logical Consistency as a Bridge: Improving LLM Hallucination Detection via Label Constraint Modeling between Responses and Self-Judgments
Hao Mi, Qiang Sheng, Shaofei Wang, Beizhe Hu, Yifan Sun, Zhengjia Wang, Hengqi Zeng, Yang Li, Danding Wang, Juan Cao
中国科学院计算技术研究所、中国科学院大学
https://arxiv.org/abs/2605.03971

2. [RAG幻觉、注意力结构一致性，Main] Hallucination Detection in LLMs with Topological Divergence on Attention Graphs
Alexandra Bazarova, Aleksandr Yugay, Andrey Shulga, Alina Ermilova, Andrei Volodichev, Konstantin Polev, Julia Belikova, Rauf Parchiev, Dmitry Simakov, Maxim Savchenko, Andrey Savchenko, Serguei Barannikov, Alexey Zaytsev
Applied AI Institute、SB AI Lab、法国国家科学研究中心、法国巴黎西岱大学
https://arxiv.org/abs/2504.10063

3. [RAG幻觉、置信度成分归因，Main] TPA: Next Token Probability Attribution for Detecting Hallucinations in RAG
Pengqian Lu, Jie Lu, Anjin Liu, Guangquan Zhang
澳大利亚人工智能研究所、澳大利亚悉尼科技大学
https://arxiv.org/abs/2512.07515

4. [引用幻觉、忠实性归因，Main] CiteGuard: Faithful Citation Attribution for LLMs via Retrieval-Augmented Validation
Yee Man Choi, Xuehang Guo, Yi R. Fung, Qingyun Wang
加拿大滑铁卢大学、美国威廉与玛丽学院、美国伊利诺伊大学厄巴纳-香槟分校
https://arxiv.org/abs/2510.1785

5. [置信度校准、Base模型，Main] BaseCal: Unsupervised Confidence Calibration via Base Model Signals
Hexiang Tan, Wanli Yang, Junwei Zhang, Xin Chen, Rui Tang, Du Su, Jingang Wang, Yuanzhuo Wang, Fei Sun, Xueqi Cheng
中国科学院计算技术研究所、中国科学院大学
https://arxiv.org/abs/2601.03042

6. [结构因果模型、反事实干预，Findings] CausalGaze: Unveiling Hallucinations via Counterfactual Graph Intervention in Large Language Models
Linggang Kong, Lei Wu, Yunlong Zhang, Xiaofeng Zhong, Zhen Wang, Yongjie Wang, Yao Pan
国防科技大学、中国工程物理研究院计算机应用研究所
https://arxiv.org/abs/2604.11087

7. [幻觉传递性、续写采样，Findings] Enhancing Hallucination Detection via Future Context
Joosung Lee, Cheonbok Park, Hwiyeol Jo, Jeonghoon Kim, Joonsuk Park, Kang Min Yoo
NAVER CLOUD、NAVER AI Lab、韩国科学技术院（KAIST）、美国里士满大学
https://arxiv.org/abs/2507.20546

8. [证据核查、论断与查询优化，Findings] JointCQ: Improving Factual Hallucination Detection with Joint Claim and Query Generation
Fan Xu, Huixuan Zhang, Zhenliang Zhang, Jiahao Wang, Xiaojun Wan
北京大学、华为
https://arxiv.org/abs/2510.19310

9. [忠实性幻觉、数据合成、后训练，Findings] FaithLens: Detecting and Explaining Faithfulness Hallucination
Shuzheng Si, Qingyi Wang, Haozhe Zhao, Yuzhuo Bai, Guanqiao Chen, Kangyang Luo, Gang Chen, Fanchao Qi, Minjia Zhang, Baobao Chang, Maosong Sun
清华大学、深言科技、复旦大学、美国伊利诺伊大学厄巴纳-香槟分校、北京大学
https://arxiv.org/abs/2512.20182

10. [长思维链幻觉、流式检测，Findings] Streaming Hallucination Detection in Long Chain-of-Thought Reasoning
Haolang Lu, Minghui Pan, Ripeng Li, Guoshun Nan, Jialin Zhuang, Zijie Zhao, Zhongxiang Sun, Kun Wang, Yang Liu
北京邮电大学、新加坡国立大学、西南交通大学、中国人民大学
https://arxiv.org/abs/2601.02170

11. [RAG幻觉、事实性与忠实性解耦，Findings] Faithfulness-Aware Uncertainty Quantification for Fact-Checking the Output of Retrieval-Augmented Generation
Ekaterina Fadeeva, Aleksandr Rubashevskii, Dzianis Piatrashyn, Roman Vashurin, Shehzaad Dhuliawala, Artem Shelmanov, Timothy Baldwin, Preslav Nakov, Mrinmaya Sachan, Maxim Panov
瑞士苏黎世联邦理工学院、阿联酋穆罕默德·本·扎耶德人工智能大学
https://arxiv.org/abs/2505.21072

12. [RAG幻觉、语义关系图，Findings] Detecting Hallucinations in Retrieval-Augmented Generation via Semantic-level Internal Reasoning Graph
Jianpeng Hu, Yanzeng Li, Jialun Zhong, Wenfa Qi, Lei Zou
北京大学、北京师范大学（珠海）
https://arxiv.org/abs/2601.03052

13. [RAG幻觉、注意力探针，Findings] Beyond Black-Box Interventions: Latent Probing for Faithful Retrieval-Augmented Generation
Linfeng Gao, Qinggang Zhang, Baolong Bi, Bo Zeng, Zheng Yuan, Zerui Chen, Zhimin Wei, Shenghua Liu, Linlong Xu, Longyue Wang, Weihua Luo, Jinsong Su
厦门大学、香港理工大学、中国科学院大学、阿里巴巴
https://arxiv.org/abs/2510.12460

14. [多重检验、幻觉指标聚合，Findings] Principled Detection of Hallucinations in Large Language Models via Multiple Testing
Jiawei Li, Akshayaa Magesh, Venugopal V. Veeravalli
美国伊利诺伊大学厄巴纳-香槟分校、Meta
https://arxiv.org/abs/2508.18473

15. [忠实性无源幻觉、细粒度评测，Findings] Fine-Grained Detection of Context-Grounded Hallucinations Using LLMs
Yehonatan Peisakhovsky, Zorik Gekhman, Yosi Mass, Liat Ein-Dor, Roi Reichart
以色列理工学院、IBM研究院
https://arxiv.org/abs/2509.22582

# 幻觉检测（多模态）
# Hallucination Detection (Multimodal)

16. [语音幻觉、注意力机制，Findings] Detecting Hallucinations in SpeechLLMs at Inference Time Using Attention Maps
Jonas Waldendorf, Bashar Awwad Shiekh Hasan, Evgenii Tsymbalov
英国爱丁堡大学、Amazon AGI
https://arxiv.org/abs/2604.19565


# 幻觉评估（纯文本）
# Hallucination Evaluation (Text)

17. [阶段性评估、多维度制衡，Main] PRISM: Probing Reasoning, Instruction, and Source Memory in LLM Hallucinations
Yuhe Wu, Guangyu Wang, Yuran Chen, Jiatong Zhang, Yutong Zhang, Yujie Chen, Jiaming Shang, Guang Zhang, Zhuang Liu
香港科技大学（广州）、上海纽约大学、东北财经大学、香港中文大学（深圳）、中央财经大学
https://arxiv.org/abs/2604.16909

18. [RAG幻觉、证据使用与整合，Findings] Facet-Level Tracing of Evidence Uncertainty and Hallucination in RAG
Passant Elchafei, Monorama Swain, Shahed Masoudian, Markus Schedl
计算感知研究所、奥地利林茨大学
https://arxiv.org/abs/2604.09174

19. [伊斯兰问答评估、阿拉伯语，Findings] From RAG to Agentic RAG for Faithful Islamic Question Answering
Gagan Bhatia, Hamdy Mubarak, Mustafa Jarrar, George Mikros, Fadi Zaraket, Mahmoud Alhirthani, Mutaz Al-Khatib, Logan Cochrane, Kareem Darwish, Rashid Yahiaoui, Firoj Alam
卡塔尔哈马德·本·哈利法大学、阿拉伯研究与政策中心
https://arxiv.org/abs/2601.07528

20. [反事实医学问答、上下文投毒，Findings] Faithfulness vs. Safety: Evaluating LLM Behavior Under Counterfactual Medical Evidence
Kaijie Mo, Siddhartha Venkatayogi, Chantal Shaib, Ramez Kouzy, Wei Xu, Byron C. Wallace, Junyi Jessy Li
美国德克萨斯大学奥斯汀分校、美国东北大学、MD安德森癌症中心、美国佐治亚理工学院
https://arxiv.org/abs/2601.11886

# 幻觉评估（多模态）
# Hallucination Evaluation (Multimodal)

21. [多模态检索、细粒度评估，Main] Benchmarking Deflection and Hallucination in Large Vision-Language Models
Nicholas Moratelli, Christopher Davis, Leonardo F. R. Ribeiro, Bill Byrne, Gonzalo Iglesias
意大利摩德纳雷焦艾米利亚大学、Amazon AGI、英国剑桥大学
https://arxiv.org/abs/2604.12033

22. [大规模音频幻觉评估基准，Main] HalluAudio: A Comprehensive Benchmark for Hallucination Detection in Large Audio-Language Models
Feiyu Zhao, Yiming Chen, Wenhuan Lu, Daipeng Zhang, Xianghu Yue, Jianguo Wei
天津大学、华硕智能云服务（新加坡）
https://arxiv.org/abs/2604.19300

23. [视频大模型幻觉、场景诱导，Main] INFACT: A Diagnostic Benchmark for Induced Faithfulness and Factuality Hallucinations in Video-LLMs
Junqi Yang, Yuecong Min, Jie Zhang, Shiguang Shan, Xilin Chen
中国科学院计算技术研究所、中国科学院大学
https://arxiv.org/abs/2603.11481

24. [多文化、跨语言、反事实幻觉，Findings] Once Correct, Still Wrong: Counterfactual Hallucination in Multilingual Vision-Language Models
Basel Mousi, Fahim Dalvi, Shammur Chowdhury, Firoj Alam, Nadir Durrani
卡塔尔哈马德·本·哈利法大学
https://arxiv.org/abs/2602.05437

25. [视频大模型、双向统一评估，Findings] FIFA: Unified Faithfulness Evaluation Framework for Text-to-Video and Video-to-Text Generation
Liqiang Jing, Viet Lai, Seunghyun Yoon, Trung Bui, Xinya Du
美国德克萨斯大学达拉斯分校、Adobe 研究院
https://arxiv.org/abs/2507.06523



以下论文暂无预印本链接：

- 幻觉检测（纯文本）
- Hallucination Detection (Text) - No Link

26. [Main] Logic Matters in Lightweight Hallucination Classification for RAG System

27. [Main] LAFaCT: Attribution-based Localization and Focused Sequential Analysis of Fact-Critical Tokens for Hallucination Detection

28. [Main] RFS-Guard: Detecting Reasoning Hallucinations via Cross-Phase Routing Focus in Large Reasoning Models

29. [Main] ReFL: Reflective Feedback Learning for Hallucination Detection of Large Language Models

30. [Main] The Digital Dunning-Kruger Effect: Decoupling Hallucinations via Geometric Hidden-state Observation for Semantic Truthfulness

31. [Main] RLSeek: Evidence-Grounded Reasoning for RAG Hallucination Detection

32. [Main] TrustTable: A Neuro-Symbolic Auditing Framework for Faithful Table QA

33. [Main] MARCH: Multi-Agent Reinforced Check for Hallucination

34. [Findings] NSF-CoT: Neuro-Symbolic Formal Verification of Chain-of-Thought Faithfulness in Contextual Question Answering

35. [Findings] ContextCheck: Sentence-Level Faithfulness Verification with Context-Aware Disambiguation

36. [Findings] Beyond Output Confidence: Epistemic-Aware Hallucination Detection with Entity-Level Signals

37. [Findings] Evidence-Aligned Entity Verification for Hallucination Detection in Retrieval-Augmented Generation

38. [Findings] DISF: Detecting Hallucinations in Retrieval-Augmented Generation via Dual-path Internal State Forcing Framework

39. [Findings] Efficient Hallucination Detection in Automatic Code Generation

40. [Findings] Hallucination Detection in Long-Form Text Generated by LLMs: A Benchmark and a Hyper-Relational Knowledge Graph Approach

41. [Findings] PROBE: PROcess-Based BEnchmark for Hallucination Detection


- 幻觉评估（纯文本）
- Hallucination Evaluation (Text) - No Link

42. [Main] Rethinking Evaluation for LLM Hallucination Detection: A Desiderata, A New RAG-based Benchmark, New Insights

43. [Main] HAT: Hallucination Annotation for Translation


- 幻觉评估（多模态）
- Hallucination Evaluation (Multimodal) - No Link

44. [Main] Automatic and Reliable Faithfulness Evaluation for Scientific Text-to-Image Generation with LMMs