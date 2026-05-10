2025年5月29日，第63届国际计算语言学学会年会（Annual Meeting of the Association for Computational Linguistics，ACL 2025）公布了主会及Findings录用的论文清单。会议将于7月27日至8月1日在奥地利维也纳举行。 完整清单见

https://2025.aclweb.org/program/main_papers/
https://2025.aclweb.org/program/find_papers/
https://2025.aclweb.org/program/demo_papers/
https://2025.aclweb.org/program/ind_papers/

本文主要整理了（含多模态）大语言模型幻觉的检测与减缓方法、评估基准和探讨调研等方面的论文，共计31篇（部分附预印本链接）。


# 幻觉检测相关 (Hallucination Detection)

1. [表征空间动态建模，神经微分方程；Main] HD-NDEs: Neural Differential Equations for Hallucination Detection in LLMs
Qing Li, Jiahui Geng, Zongxiong Chen, Derui Zhu, Yuxia Wang, Congbo Ma, Chenyang Lyu, Fakhri Karray
MBZUAI、弗劳恩霍夫开放通信系统研究所（FOKUS）、德国慕尼黑工业大学、纽约大学阿布扎比分校
https://arxiv.org/pdf/2506.00088v1

2. [表征动态追踪；Main] ICR Probe: Tracking Hidden State Dynamics for Reliable Hallucination Detection in LLMs
Zhenliang Zhang, Xinyu Hu, Huixuan Zhang, Junzhe Zhang, Xiaojun Wan
北京大学

3. [表征空间对齐，Prompt引导，跨数据集泛化；Main] Prompt-Guided Internal States for Hallucination Detection of Large Language Models
Fujie Zhang, Peiqi Yu, Biao Yi, Baolei Zhang, Tong Li, Zheli Liu
南开大学
https://arxiv.org/pdf/2411.04847

4. [代码幻觉，实体追踪；Main] ETF: An Entity Tracing Framework for Hallucination Detection in Code Summaries
Kishan Maharaj, Vitobha Munigala, Srikanth G. Tamilselvam, Prince Kumar, Sayandeep Sen, Palani Kodeswaran, Abhijit Mishra, Pushpak Bhattacharyya
印度孟买理工学院、IBM印度研究院、美国德克萨斯大学奥斯汀分校
https://arxiv.org/pdf/2410.14748

5. [长文本幻觉，辅助任务微调；Main] Learning Auxiliary Tasks Improves Reference-Free Hallucination Detection in Open-Domain Long-Form Generation
Chengwei Qin, Wenxuan Zhou, Karthik Abinav Sankararaman, Nanshu Wang, Tengyu Xu, Alexander Radovic, Eryk Helenowski, Arya Talebzadeh, Aditya Tayade, Sinong Wang, Shafiq Joty, Han Fang, Hao Ma
香港科技大学（广州）、新加坡南洋理工大学、Meta
https://arxiv.org/pdf/2505.12265

6. [不确定性校准，模型辅助；Main] Towards Harmonized Uncertainty Estimation for Large Language Models
Rui Li, Jing Long, Muge Qi, Heming Xia, Lei Sha, Peiyi Wang, Zhifang Sui
北京大学、香港理工大学、北京航空航天大学
https://arxiv.org/pdf/2505.19073

7. [长文本幻觉，自我反思；Findings] Long-form Hallucination Detection with Self-elicitation
Zihang Liu, Jiawei Guo, Hao Zhang, Hongyang Chen, Jiajun Bu, Haishuai Wang
浙江大学
https://openreview.net/pdf?id=r9mYbs8RTH

8. [多模态，MLLM as a judge；Findings] MHALO: Evaluating MLLMs as Fine-grained Hallucination Detectors
Yishuo Cai, Renjie Gu, Jiaxu Li, Xuancheng Huang, Junzhe Chen, Xiaotao Gu, Minlie Huang
中南大学、清华大学
https://openreview.net/pdf?id=t1W8txNm7K

9. [多模态，注意力图，序列建模；Findings] VADE: Visual Attention Guided Hallucination Detection and Elimination
Vishnu Prabhakaran, Purav Aggarwal, Vinay Kumar Verma, Gokul Swamy, Anoop Saladi
亚马逊
https://assets.amazon.science/1b/68/7bd75757469285de97284a19f1e9/vade-visual-attention-guided-hallucination-detection-and-elimination.pdf

10. [混合情境幻觉，摘要任务，LLM as a judge；Findings] Evaluating LLMs’ Assessment of Mixed-Context Hallucination Through the Lens of Summarization
Siya Qi, RUI CAO, Yulan He, Zheng Yuan
英国伦敦国王学院、英国剑桥大学、英国艾伦·图灵研究所
https://arxiv.org/pdf/2503.01670

11. [不确定性估计，语义熵增强；Findings] Beyond Semantic Entropy: Boosting LLM Uncertainty Quantification with Pairwise Semantic Similarity
Dang Nguyen, Ali Payani, Baharan Mirzasoleiman
美国加州大学洛杉矶分校、美国思科系统公司
https://arxiv.org/pdf/2506.00245



# 幻觉减缓相关 (Hallucination Mitigation)

1. [多模态，视觉感知注意力头；Main] Cracking the Code of Hallucination in LVLMs with Vision-aware Head Divergence
Jinghan He, Kuan Zhu, Haiyun Guo, Junfeng Fang, Zhenglin Hua, Yuheng Jia, Ming Tang, Tat-Seng Chua, Jinqiao Wang
中国科学院自动化研究所、中国科学院大学、新加坡国立大学、东南大学、武汉人工智能研究院
https://arxiv.org/pdf/2412.13949v3

2. [多模态，视觉证据提示；Main] Visual Evidence Prompting Mitigates Hallucinations in Large Vision-Language Models
Wei Li, Zhen Huang, Houqiang Li, Le Lu, Yang Lu, Xinmei Tian, Xu Shen, Jieping Ye
中国科学技术大学、阿里巴巴
https://openreview.net/pdf?id=xh3XUaB8M9

3. [训练过程追踪与优化；Main] Hallucination Detox: Sensitivity Dropout (SenD) for Large Language Model Training
Shahrad Mohammadzadeh, Juan David Guerra, Marco Bonizzato, Reihaneh Rabbany, Golnoosh Farnadi
加拿大麦吉尔大学、加拿大蒙特利尔大学、Mila-魁北克AI研究所
https://arxiv.org/pdf/2410.15460

4. [RAG蒸馏，知识图谱；Main] DRAG: Distilling RAG for SLMs from LLMs to Transfer Knowledge and Mitigate Hallucination via Evidence and Graph-based Distillation
Jennifer Chen, Aidar Myrzakhan, Yaxin Luo, Hassaan Muhammad Khan, Sondos Mahmoud Bsharat, Zhiqiang Shen
MBZUAI、加拿大麦吉尔大学、巴基斯坦国立科技大学
https://arxiv.org/pdf/2506.01954v1

5. [多模态，内部表征干预；Main] Activation Steering Decoding: Mitigating Hallucination in Large Vision-Language Models through Bidirectional Hidden State Intervention
Jingran Su, Jingfan Chen, Hongxin Li, Yuntao Chen, Li Qing, Zhaoxiang Zhang
中国科学院自动化研究所、中国科学院大学
https://openreview.net/pdf?id=XfvmkVvnCq

6. [多模态，多语言，激活引导；Main] CLAIM: Mitigating Multilingual Object Hallucination in Large Vision-Language Models with Cross-Lingual Attention Intervention
Zekai Ye, Qiming Li, Xiaocheng Feng, Libo Qin, Yichong Huang, Baohang Li, Kui Jiang, Yang Xiang, Zhirui Zhang, Yunfei Lu, Duyu Tang, Dandan Tu, Bing Qin
哈尔滨工业大学
https://openreview.net/pdf?id=y8aqFe7sPB

7. [RAG幻觉，多智能体辩论；Main] Removal of Hallucination on Hallucination: Debate-Augmented RAG
Wentao Hu, Wengyu Zhang, Yiyang Jiang, Chen Jason Zhang, Xiaoyong Wei, Li Qing
香港理工大学、四川大学
https://arxiv.org/pdf/2505.18581

8. [微调数据筛选，知识熟悉度评估；Main] Aligning Large Language Models to Follow Instructions and Hallucinate Less via Effective Data Filtering
Shuzheng Si, Haozhe Zhao, Gang Chen, Cheng Gao, Yuzhuo Bai, Zhitong Wang, Kaikai An, Kangyang Luo, Chen Qian, Fanchao Qi, Baobao Chang, Maosong Sun
清华大学、北京大学、深言科技
https://arxiv.org/pdf/2502.07340

9. [知识错位，选择性弃权学习；Main] Alleviating Hallucinations from Knowledge Misalignment in Large Language Models via Selective Abstention Learning
Lei Huang, Xiaocheng Feng, Weitao Ma, Yuchun Fan, Xiachong Feng, Yuxuan Gu, Yangfan Ye, Liang Zhao, Weihong Zhong, Baoxin Wang, Dayong Wu, Guoping Hu, Lingpeng Kong, Tong Xiao, Ting Liu, Bing Qin
哈尔滨工业大学

10. [不确定性估计，事实对齐；Main] UAlign: Leveraging Uncertainty Estimations for Factuality Alignment on Large Language Models
Boyang XUE, Fei Mi, Qi Zhu, Hongru WANG, Rui Wang, Sheng Wang, Erxin Yu, Xuming Hu, Kam-Fai Wong
香港中文大学、华为、香港大学、香港理工大学、香港科技大学（广州）等
https://arxiv.org/pdf/2412.11803

11. [不确定性估计，拒答优化；Main] Do not Abstain! Identify and Solve the Uncertainty
Jingyu Liu, JingquanPeng, xiaopeng Wu, Xubin Li, Tiezheng Ge, Bo Zheng, Yong Liu
中国人民大学、阿里巴巴等
https://arxiv.org/pdf/2506.00780

12. [RAG策略优化，实时记忆；Main] Improving Factuality with Explicit Working Memory
Mingda Chen, Yang Li, Karthik Padthe, Rulin Shao, Alicia Yi Sun, Luke Zettlemoyer, Gargi Ghosh, Wen-tau Yih
Meta
https://arxiv.org/pdf/2412.18069

13. [动态焦点解码，事实性与多样性权衡；Main] Odysseus Navigates the Sirens’ Song: Dynamic Focus Decoding for Factual and Diverse Open-Ended Text Generation
Wen Luo, Feifan Song, Wei Li, Guangyue Peng, Shaohang Wei, Houfeng Wang
北京大学
https://arxiv.org/pdf/2503.08057

14. [事实性Lora微调；Findings] Alleviating Hallucinations in Large Language Models via Truthfulness-driven Rank-adaptive LoRA
Jiahao Li, Zhendong Mao, Quan Wang
中国科学技术大学、北京邮电大学

15. [上下文忠实性幻觉，注意力解码；Findings] Dynamic Attention-Guided Context Decoding for Mitigating Context Faithfulness Hallucinations in Large Language Models
Yanwen Huang, Yong Zhang, Ning Cheng, Zhitao Li, Shaojun Wang, Jing Xiao
平安科技、电子科技大学
https://arxiv.org/pdf/2501.01059

16. [在线强化学习，知识反馈；Findings] On-Policy Self-Alignment with Fine-grained Knowledge Feedback for Hallucination Mitigation
Xueru Wen, Jie Lou, Xinyu Lu, Yuqiu Ji, Xinyan Guan, Yaojie Lu, Hongyu Lin, Ben He, Xianpei Han, Debing Zhang, Le Sun
中国科学院软件研究所、中国科学院大学、小红书
https://arxiv.org/pdf/2406.12221

17. [幻觉诱导，对比解码；Findings] HICD: Hallucination-Inducing via Attention Dispersion for Contrastive Decoding to Mitigate Hallucinations in Large Language Models
Xinyan Jiang, Hang Ye, Yongxin Zhu, Xiaoying Zheng, Zikang Chen, Jun Gong
中国科学院上海高等研究院、中国科学院大学
https://arxiv.org/abs/2503.12908

18. [快慢思考结合；Findings] Think More, Hallucinate Less: Mitigating Hallucinations via Dual Process of Fast and Slow Thinking
Xiaoxue Cheng, Junyi Li, Xin Zhao, Ji-Rong Wen
中国人民大学、新加坡国立大学
https://arxiv.org/pdf/2501.01306

19. [多模态，检索视觉对比解码；Findings] Retrieval Visual Contrastive Decoding to Mitigate Object Hallucinations in Large Vision-Language Models
Jihoon Lee, Min Song
韩国延世大学、Onoma AI
https://arxiv.org/pdf/2505.20569

20. [多模态，混合解码策略；Findings] Mixture of Decoding: An Attention-Inspired Adaptive Decoding Strategy to Mitigate Hallucinations in Large Vision-Language Models
Xinlong Chen, Yuanxing Zhang, Qiang Liu, Junfei Wu, Fuzheng Zhang, Tieniu Tan
中国科学院自动化研究所、中国科学院大学、快手、南京大学
https://arxiv.org/pdf/2505.17061

21. [生成过程监控，树解码；Findings] Monitoring Decoding: Mitigating Hallucination via Evaluating the Factuality of Partial Response during Generation
Yurui Chang, Bochuan Cao, Lu Lin
美国宾夕法尼亚州立大学
https://arxiv.org/pdf/2503.03106

22. [先验证查询，后响应；Findings] Lightweight Query Checkpoint: Classifying Faulty User Queries to Mitigate Hallucinations in Large Language Model Question Answering
Jonghak Jang, Minjoo Son, Misuk Kim
韩国汉阳大学
https://openreview.net/pdf?id=n9C8u6tpT4

23. [多模态，直接偏好优化；Findings] Mitigating Hallucination in Multimodal Large Language Model via Hallucination-targeted Direct Preference Optimization
Yuhan Fu, Ruobing Xie, Xingwu Sun, Zhanhui Kang, Xirong Li
中国人民大学、腾讯
https://arxiv.org/pdf/2411.10436

24. [知识掩盖；Findings] The Law of Knowledge Overshadowing: Towards Understanding, Predicting and Preventing LLM Hallucination
Yuji Zhang, Sha Li, Cheng Qian, Jiateng Liu, Pengfei Yu, Chi Han, Yi R. Fung, Kathleen McKeown, ChengXiang Zhai, Manling Li, Heng Ji
美国伊利诺伊大学香槟分校、美国哥伦比亚大学、美国西北大学、美国斯坦福大学
https://arxiv.org/pdf/2502.16143

25. [不确定性微调，知识边界；Findings] Know the Unknown: An Uncertainty-Sensitive Method for LLM Instruction Tuning
Jiaqi Li, Yixuan Tang, Yi Yang
香港科技大学
https://arxiv.org/pdf/2406.10099



# 幻觉评估相关 (Hallucination Evaluation) 

1. [数据层溯因；Main] HALoGEN: Fantastic LLM Hallucinations and Where to Find Them
Abhilasha Ravichander, Shrusti Ghela, David Wadden, Yejin Choi
美国华盛顿大学、谷歌、英伟达
https://arxiv.org/pdf/2501.08292

2. [意图幻觉，多条件查询；Main] Beyond Facts: Evaluating Intent Hallucination in Large Language Models
Yijie Hao, Haofei Yu, Jiaxuan You
美国埃默里大学、美国伊利诺伊大学香槟分校
https://arxiv.org/pdf/2506.06539

3. [内外幻觉全面基准，动态测试集生成；Main] HalluLens: LLM Hallucination Benchmark
Yejin Bang, Ziwei Ji, Alan Schelten, Anthony Hartshorn, Tara Fowler, Cheng Zhang, Nicola Cancedda, Pascale Fung
Meta、香港科技大学
https://arxiv.org/pdf/2504.17550

4. [无解数学题，推理评估；Main] TreeCut: A Synthetic Unanswerable Math Word Problem Dataset for LLM Hallucination Evaluation
Jialin Ouyang
哥伦比亚大学
https://arxiv.org/pdf/2502.13442

5. [跨语言-多模态联合场景评估；Main] CCHall: A Novel Benchmark for Joint Cross-Lingual and Cross-Modal Hallucinations Detection in Large Language ModelsHallucination Evaluation
Yongheng Zhang, Xu Liu, Ruoxi Zhou, Qiguang Chen, Hao Fei, Wenpeng Lu, Libo Qin
中南大学、苏州大学、新加坡国立大学、齐鲁工业大学（山东省科学院）
https://arxiv.org/pdf/2505.19108

6. [不确定性估计，语言置信度评估；Main] Revisiting Epistemic Markers in Confidence Estimation: Can Markers Accurately Reflect Large Language Models’ Uncertainty?
Jiayu Liu, Qing Zong, Weiqi Wang, Yangqiu Song
香港科技大学
https://arxiv.org/pdf/2505.24778

7. [不确定性估计，自适应检索评估；Main] Adaptive Retrieval Without Self-Knowledge? Bringing Uncertainty Back Home
Viktor Moskvoretskii, Maria Marina, Mikhail Salnikov, Nikolay Ivanov, Sergey Pletenev, Daria Galimzianova, Nikita Krayko, Vasily Konovalov, Irina Nikishina, Alexander Panchenko
俄罗斯斯科尔科沃科学技术研究院、俄罗斯国家研究型高等经济大学、莫斯科物理技术学院、德国汉堡大学等
https://arxiv.org/pdf/2501.12835

8. [长文本不确定性，原子事实微调；Main] LoGU: Long-form Generation with Uncertainty Expressions
Ruihan Yang, Caiqi Zhang, Zhisong Zhang, Xinting Huang, Sen Yang, Nigel Collier, Dong Yu, Deqing Yang
复旦大学、剑桥大学、腾讯AI Lab、香港中文大学
https://arxiv.org/pdf/2410.14309

9. [中文事实性评估；Main] Chinese SimpleQA: A Chinese Factuality Evaluation for Large Language Models
Yancheng He, Shilong Li, Jiaheng Liu, Yingshui Tan, Weixun Wang, Hui Huang, Xingyuan Bu, Hangyu Guo, Chengwei Hu, Boren Zheng, Zhuoran Lin, Dekai Sun, Zhicheng Zheng, Wenbo Su, Bo Zheng
阿里巴巴
https://arxiv.org/pdf/2411.07140

10. [不确定性表达评估；Main] Representations of Fact, Fiction and Forecast in Large Language Models: Epistemics and Attitudes
Meng Li, Michael Vrazitulis, David Schlangen
德国波茨坦大学
https://arxiv.org/pdf/2506.01512

11. [动态评估；Main] FactBench: A Dynamic Benchmark for In-the-Wild Language Model Factuality Evaluation
Farima Fatahi Bayat, Lechen Zhang, Sheza Munir, Lu Wang
密歇根大学安娜堡分校
https://arxiv.org/pdf/2410.22257

12. [角色扮演，立场迁移，交互幻觉；Findings] SHARP: Unlocking Interactive Hallucination via Stance Transfer in Role-Playing LLMs
Chuyi Kong, Ziyang Luo, Hongzhan Lin, Zhiyuan Fan, Yaxin Fan, Yuxi Sun, Jing Ma
香港浸会大学、苏州大学、香港科技大学
https://arxiv.org/pdf/2411.07965

13. [多模态，关系幻觉；Findings] Reefknot: A Comprehensive Benchmark for Relation Hallucination Evaluation, Analysis and Mitigation in Multimodal Large Language Models
Kening Zheng, Junkai Chen, Yibo Yan, Xin Zou, Huiyu Zhou, Xuming Hu
香港科技大学（广州）、广西壮族自治区大数据研究院、香港科技大学
https://arxiv.org/pdf/2408.09429

14. [多模态，自主评估，戴维森场景图；Findings] FIHA: Automated Fine-grained Hallucinations Evaluations in Large Vision Language Models with Davidson Scene Graphs
Bowen Yan, Zhengsong Zhang, Liqiang Jing, Eftekhar Hossain, Xinya Du
美国德克萨斯大学达拉斯分校
https://arxiv.org/pdf/2409.13612v2


# 幻觉的相关探讨/机理解释/综述 (Discussion, Mechanism, and Survey)

1. [上下文误导，幻觉与泛化，机制解释；Main] Stochastic Chameleons: Irrelevant Context Hallucinations Reveal Class-Based (Mis)Generalization in LLMs
Ziling Cheng, Meng Cao, Marc-Antoine Rondeau, Jackie CK Cheung
Mila-魁北克AI研究所、加拿大麦吉尔大学
https://arxiv.org/pdf/2505.22630

2. [不确定性估计的有效性评估；Main] Reconsidering LLM Uncertainty Estimation Methods in the Wild
Duygu Nur Yaldiz, Yavuz Faruk Bakman, Sungmin Kang, Tuo Zhang, Baturalp Buyukates, Sai Praneeth Karimireddy, Salman Avestimehr
美国南加州大学、英国伯明翰大学
https://arxiv.org/pdf/2506.01114

3. [事实知识回溯机制；Main] Tracing and Dissecting How LLMs Recall Factual Knowledge for Real World Questions
Yiqun Wang, Chaoqun Wan, Sile Hu, Yonggang Zhang, Xiang Tian, Yaowu Chen, Xu Shen, Jieping Ye
浙江大学、阿里巴巴
https://openreview.net/pdf?id=I2zujS4yZD

4. [模型架构对幻觉的影响；Main] Do Robot Snakes Dream like Electric Sheep? Investigating the Effects of Architectural Inductive Biases on Hallucination
Jerry Huang, Prasanna Parthasarathi, Mehdi Rezagholizadeh, Boxing Chen, Sarath Chandar
Mila、加拿大蒙特利尔大学、华为诺亚方舟实验室、AMD
https://arxiv.org/pdf/2410.17477

5. [不确定性估计综述；Findings] A Survey of Uncertainty Estimation Methods on Large Language Models
Zhiqiu Xia, JINXUAN XU, Yuqian Zhang, Hang Liu
美国罗格斯大学
https://arxiv.org/pdf/2503.00172

