2024年9月24日，CCF-B类自然语言处理领域知名会议2024年自然语言处理实证方法会议（EMNLP 2024）公布了主会及Findings录用的论文清单。会议将于11月12日至16日在美国迈阿密举行。完整清单见

https://2024.emnlp.org/program/accepted_main_conference/
https://2024.emnlp.org/program/accepted_findings/
https://2024.emnlp.org/program/demo/
https://2024.emnlp.org/program/industry/

本文主要整理了（含多模态）大语言模型幻觉的检测与减缓方法、评估基准和探讨调研等方面的论文，共计58篇（部分附预印本链接）。

# 幻觉检测相关 (Hallucination Detection)

1. [上下文忠实性幻觉、注意力权重分配；Main] Lookback Lens: Detecting and Mitigating Contextual Hallucinations in Large Language Models Using Only Attention Maps
Yung-Sung Chuang, Linlu Qiu, Cheng-Yu Hsieh, Ranjay Krishna, Yoon Kim, James R. Glass
麻省理工学院、华盛顿大学
https://arxiv.org/pdf/2407.07071

2. [LLM智能体、工具调用；Main] Small Agent Can Also Rock! Empowering Small Language Models as Hallucination Detector
Xiaoxue Cheng, Junyi Li, Xin Zhao, Hongzhi Zhang, Fuzheng Zhang, Di ZHANG, Kun Gai, Ji-Rong Wen
中国人民大学、蒙特利尔大学、快手
https://arxiv.org/pdf/2406.11277

3. [摘要幻觉、原子事实核查；Main] FIZZ: Factual Inconsistency Detection by Zoom-in Summary and Zoom-out Document
Joonho Yang, Seunghyun Yoon, ByeongJeong Kim, Hwanhee Lee
韩国中央大学、Adobe Research
https://arxiv.org/pdf/2404.11184

4. [多模态RAG、医疗大模型；Main] RULE: Reliable Multimodal RAG for Factuality in Medical Vision Language Models
Peng Xia, Kangyu Zhu, Haoran Li, Hongtu Zhu, Yun Li, Gang Li, Linjun Zhang, Huaxiu Yao
北卡罗来纳大学教堂山分校、布朗大学、香港理工大学、罗格斯大学、莫纳什大学
https://arxiv.org/pdf/2407.05131

5. [基于证据的高效LLM生成内容核查；Main] MiniCheck: Efficient Fact-Checking of LLMs on Grounding Documents
Liyan Tang, Philippe Laban, Greg Durrett
德克萨斯大学奥斯汀分校、Salesforce AI Research
https://arxiv.org/pdf/2404.10774

6. [白盒检测、词嵌入与梯度；Main] Embedding and Gradient Say Wrong: A White-Box Method for Hallucination Detection
Xiaomeng Hu, Yiming Zhang, Ru Peng, Haozhe Zhang, Chenwei Wu, Gang Chen, Junbo Zhao

7. [以知识为中心的幻觉检测；Main] Knowledge-Centric Hallucination Detection
Xiangkun Hu, Dongyu Ru, Lin Qiu, Qipeng Guo, Tianhang Zhang, Yang Xu, Yun Luo, Pengfei Liu, Yue Zhang, Zheng Zhang
亚马逊 AWS AI、上海人工智能实验室、上海交通大学、西湖大学
https://arxiv.org/abs/2405.14486

8. [机器翻译幻觉、多检测器集成；Main(Short)] Enhanced Hallucination Detection in Neural Machine Translation through Simple Detector Aggregation
Anas Himmi, Guillaume Staerman, Marine Picot, Pierre Colombo, Nuno M Guerreiro
巴黎萨克雷大学、葡萄牙里斯本电信研究所、里斯本大学等
https://arxiv.org/pdf/2402.13331

9. [新闻标题幻觉、多语言；Findings] Multilingual Fine-Grained News Headline Hallucination Detection
Jiaming Shen, Tianqi Liu, Jialu Liu, Zhen Qin, Jay Pavagadhi, Simon Baumgartner, Michael Bendersky
Google Research、Google
https://arxiv.org/pdf/2407.15975

10. [机器翻译幻觉、高低资源语言；Findings] Machine Translation Hallucination Detection for Low and High Resource Languages using Large Language Models
Kenza Benkirane, Laura Gongas, Shahar Pelles, Naomi Fuchs, Joshua Darmon, Pontus Stenetorp, David Ifeoluwa Adelani, Eduardo Sánchez
伦敦大学学院、Meta
https://arxiv.org/pdf/2407.16470

11. [多模态、概率不确定性、采样一致性、内部表征；Findings] Reference-free Hallucination Detection for Large Vision-Language Models
Qing Li, Jiahui Geng, Chenyang Lyu, Derui Zhu, Maxim Panov, Fakhri Karray
MBZUAI、慕尼黑工业大学
https://arxiv.org/pdf/2408.05767

12. [检测粒度校准、去语境化、分子事实；Findings] Molecular Facts: Desiderata for Decontextualization in LLM Fact Verification
Anisha Gunjal, Greg Durrett
德克萨斯大学奥斯汀分校
https://arxiv.org/pdf/2406.20079

13. [嵌入差异；Findings] CED: Comparing Embedding Differences for Detecting Out-of-Distribution and Hallucinated Text
Hakyung Lee, Keon-Hee Park, Hoyoon Byun, Jeyoon Yeom, Jihee Kim, Gyeong-Moon Park, Kyungwoo Song
韩国延世大学、庆熙大学

14. [多源证据融合；Demo] Medico: Towards Hallucination Detection and Correction with Multi-source Evidence Fusion
Xinping Zhao, Jindi Yu, zhenyu liu, Jifang Wang, Dongfang Li, Yibin Chen, Baotian Hu, Min zhang
哈尔滨工业大学（深圳）、华为
https://arxiv.org/pdf/2410.10408

15. [双层编码器、RAG；Industry] Two-tiered Encoder-based Hallucination Detection for Retrieval-Augmented Generation in the Wild
Ilana Zimmerman, Jadin Tredup, Ethan Selfridge, Joseph Bradley
LivePerson Inc.

16. [幻觉感知微调、RAG；Industry] RAG-HAT: A Hallucination-Aware Tuning Pipeline for LLM in Retrieval-Augmented Generation
Juntong Song, Xingguang Wang, Juno Zhu, Yuanhao Wu, Xuxin Cheng, Randy Zhong, Cheng Niu
NewsBreak

17. [轻量级核查器、RAG；Industry] Provenance: A Light-weight Fact-checker for Retrieval Augmented LLM Generation Output
Mohammed Nasheed Yasin, Hithesh Sankararaman, Andreas Stolcke
Uniphore


# 幻觉减缓相关 (Hallucination Mitigation)

1. [知识一致对齐、知识边界探索；Main] Knowledge Verification to Nip Hallucination in the Bud
Fanqi Wan, Xinting Huang, Leyang Cui, Xiaojun Quan, Wei Bi, Shuming Shi
中山大学、腾讯AI Lab
https://arxiv.org/pdf/2401.10768

2. [知识边界探索、拒答策略；Main] Learn to Refuse: Making Large Language Models More Controllable and Reliable through Knowledge Scope Limitation and Refusal Mechanism
Lang Cao
伊利诺伊大学厄巴纳-香槟分校
https://arxiv.org/pdf/2311.01041

3. [错误前提幻觉、注意力头约束；Main] Whispers that Shake Foundations: Analyzing and Mitigating False Premise Hallucinations in Large Language Models
Hongbang Yuan, Pengfei Cao, Zhuoran Jin, Yubo Chen, Daojian Zeng, Kang Liu, Jun Zhao
中国科学院自动化研究所、中国科学院大学、湖南师范大学
https://arxiv.org/pdf/2402.19103

4. [基于激活的置信度校准、置信度引导解码；Main] Enhancing Language Model Factuality via Activation-Based Confidence Calibration and Guided Decoding
Xin Liu, Farima Fatahi Bayat, Lu Wang
密歇根大学安娜堡分校
https://arxiv.org/pdf/2406.13230

5. [多模态、遗忘学习；Main] EFUF: Efficient Fine-Grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models
Shangyu Xing, Fei Zhao, Zhen Wu, Tuo An, Weihao Chen, Chunhui Li, Jianbing Zhang, Xinyu Dai
南京大学
https://arxiv.org/pdf/2402.09801

6. [多模态、视觉增强惩罚解码；Main] HELPD: Mitigating Hallucination of LVLMs by Hierarchical Feedback Learning with Vision-enhanced Penalty Decoding
Fan Yuan, Chi Qin, Xiaogang Xu, Piji Li
南京航空航天大学、香港中文大学
https://arxiv.org/pdf/2409.20429

7. [多模态、图像注意力调控；Main] DAMRO: Dive into the Attention Mechanism of LVLM to Reduce Object Hallucination
Xuan Gong, Tianshi Ming, Xinpeng Wang, Zhihua Wei
同济大学
https://arxiv.org/pdf/2410.04514

8. [多模态、声明分解、程序验证PoT；Main] Pelican: Correcting Hallucination in Vision-LLMs via Claim Decomposition and Program of Thought Verification
Pritish Sahu, Karan Sikka, Ajay Divakaran
SRI International
https://arxiv.org/pdf/2407.02352

9. [多模态、CLIP组件的物体幻觉、反事实数据增强；Main] Investigating and Mitigating Object Hallucinations in Pretrained Vision-Language (CLIP) Models
Yufang Liu, Tao Ji, Changzhi Sun, Yuanbin Wu, Aimin Zhou
华东师范大学、复旦大学、琶洲实验室（黄埔）
https://arxiv.org/pdf/2410.03176

10. [多模态、开放词汇环境；Main] Mitigating Open-Vocabulary Caption Hallucinations
Assaf Ben-Kish, Moran Yanuka, Morris Alper, Raja Giryes, Hadar Averbuch-Elor
以色列特拉维夫大学
https://arxiv.org/pdf/2312.03631

11. [多模态、视图树、博弈论；Main] Game on Tree: Visual Hallucination Mitigation via Coarse-to-Fine View Tree and Game Theory
Xianwei Zhuang, Zhihong Zhu, Zhanpeng Chen, Yuxin Xie, Liming Liang, Yuexian Zou
北京大学

12. [医学信息提取、交替对比解码；Findings] Mitigating Hallucinations of Large Language Models in Medical Domain via Contrastive Decoding
Derong Xu, Ziheng Zhang, Zhihong Zhu, Zhenxi Lin, Qidong Liu, Xian Wu, Tong Xu, Xiangyu Zhao, Yefeng Zheng, Enhong Chen
中国科学技术大学
https://openreview.net/pdf?id=dt0WRSK6cL

13. [幻觉的机制解释、内部表征操控；Findings] Mechanistic Understanding and Mitigation of Language Model Non-Factual Hallucinations
Lei Yu, Meng Cao, Jackie CK Cheung, Yue Dong
多伦多大学、麦吉尔大学、Mila-魁北克AI研究所、加州大学河滨分校
https://arxiv.org/pdf/2403.18167

14. [忠实性幻觉、概率加权损失；Findings] Pre-trained Language Models Return Distinguishable Probability Distributions to Unfaithfully Hallucinated Texts
Taehun Cha, Donghun Lee
韩国高丽大学
https://arxiv.org/pdf/2409.16658

15. [多模态、反事实思维；Findings] What if…?: Thinking Counterfactual Keywords Helps to Mitigate Hallucination in Large Multi-modal Models
Junho Kim, Yeonju Kim, Yong Man Ro
KAIST
https://arxiv.org/pdf/2403.13513

16. [多模态、GUI理解任务；Findings] VGA: Vision GUI Assistant - Minimizing Hallucinations through Image-Centric Fine-Tuning
Ziyang Meng, Yu Dai, Zezheng Gong, Shaoxiong Guo, Minglong Tang, Tongquan Wei
华东师范大学
https://arxiv.org/pdf/2406.14056

17. [多模态、视觉引导DPO、减轻文本依赖；Findings] V-DPO: Mitigating Hallucination in Large Vision Language Models via Vision-Guided Direct Preference Optimization
Yuxi Xie, Guanzhen Li, Xiao Xu, Min-Yen Kan
新加坡国立大学
https://openreview.net/pdf?id=6v0aNxTXuG

18. [角色扮演幻觉、置信度校准；Findings] Mitigating Hallucination in Fictional Character Role-Play
Nafis Sadeq, Zhouhang Xie, Byungkyu Kang, Prarit Lamba, Xiang Gao, Julian McAuley
加州大学圣地亚哥分校、Intuit
https://arxiv.org/pdf/2406.17260

19. [概念熟悉度评估、拒答策略；Findings] Zero-Resource Hallucination Prevention for Large Language Models
Junyu Luo, Cao Xiao, Fenglong Ma
宾夕法尼亚州立大学、GE HealthCare
https://arxiv.org/pdf/2309.02654v3

20. [新闻摘要幻觉、对比偏好优化；Findings] Improving Factual Consistency of News Summarization by Contrastive Preference Optimization
Huawen Feng, Yan Fan, Xiong Liu, Ting-En Lin, ZekunYao, Yuchuan Wu, Fei Huang, Yongbin Li, Qianli Ma
华南理工大学、阿里巴巴
https://openreview.net/pdf?id=eVEAO0MHP4

21. [长篇幅事实对齐；Findings] FactAlign: Long-form Factuality Alignment of Large Language Models
Chao-Wei Huang, Yun-Nung Chen
台湾大学
https://arxiv.org/pdf/2410.01691

22. [RAG风险控制、反事实置信度预测；Findings] Controlling Risk of Retrieval-augmented Generation: A Counterfactual Prompting Framework
Lu Chen, Ruqing Zhang, Jiafeng Guo, Yixing Fan, Xueqi Cheng
中国科学院计算技术研究所、中国科学院大学
https://arxiv.org/pdf/2409.16146


# 幻觉评估相关 (Hallucination Evaluation)   

1. [多模态；开放式生成评估；Main] Does Object Grounding Really Reduce Hallucination of Large Vision-Language Models?
Gregor Geigle, Radu Timofte, Goran Glavaš
维尔茨堡大学
https://arxiv.org/pdf/2406.14492

2. [多模态、虚假图片输入导致的幻觉；Main] The Instinctive Bias: Spurious Images lead to Hallucination in MLLMs
Tianyang Han, Qing LIAN, Rui Pan, Renjie Pi, Jipeng Zhang, Shizhe Diao, Yong Lin, Tong Zhang
香港科技大学、伊利诺伊大学厄巴纳-香槟分校、香港理工大学、NVIDIA
https://arxiv.org/pdf/2402.03757

3. [多模态-文生图、多样性与事实性权衡；Main] The Factuality Tax of Diversity-Intervened Text-to-Image Generation: Benchmark and Fact-Augmented Intervention
Yixin Wan, Di Wu, Haoran Wang, Kai-Wei Chang
加州大学洛杉矶分校
https://arxiv.org/pdf/2407.00377

4. [工具增强LLM的幻觉评估；Main] ToolBeHonest: A Multi-level Hallucination Diagnostic Benchmark for Tool-Augmented Large Language Models
Yuxiang Zhang, Jing Chen, Junjie Wang, Yaxin Liu, Cheng Yang, Chufan Shi, Xinyu Zhu, Zihao Lin, Hanwen WAN, Yujiu Yang, Tetsuya Sakai, Tian Feng, Hayato Yamana
早稻田大学、浙江大学、清华大学、香港中文大学、弗吉尼亚理工大学、香港中文大学（深圳）
https://arxiv.org/pdf/2406.20015

5. [细粒度评估、思维链；Main] HalluMeasure: Fine-grained Hallucination Measurement Using Chain-of-Thought Reasoning
Shayan Ali Akbar, Md Mosharaf Hossain, Tess Wood, Si-Chi Chin, Victor Alvarez, Erica M Salinas, Erwin Cornejo

6. [多轮对话级幻觉评估；Findings] DiaHalu: A Dialogue-level Hallucination Evaluation Benchmark for Large Language Models
Kedi Chen, Qin Chen, Jie Zhou, Yishen He, Liang He
华东师范大学
https://arxiv.org/pdf/2403.00896

7. [多模态、自动生成基准；Findings] AUTOHALLUSION: Automatic Generation of Hallucination Benchmarks for Vision-Language Models
Xiyang Wu, Tianrui Guan, Dianqi Li, Shuaiyi Huang, Xiaoyu Liu, Xijun Wang, Ruiqi Xian, Abhinav Shrivastava, Furong Huang, Jordan Lee Boyd-Graber, Tianyi Zhou, Dinesh Manocha
马里兰大学帕克分校
https://arxiv.org/pdf/2406.10900

8. [多模态、原子事实评估；Findings] FaithScore: Fine-grained Evaluations of Hallucinations in Large Vision-Language Models
Liqiang Jing, Ruosen Li, Yunmo Chen, Xinya Du
德克萨斯大学达拉斯分校、约翰霍普金斯大学
https://arxiv.org/pdf/2311.01477

9. [时间敏感性知识评估；Findings] DyKnow: Dynamically Verifying Time-Sensitive Factual Knowledge in LLMs
Seyed Mahed Mousavi, Simone Alghisi, Giuseppe Riccardi
意大利特伦托大学
https://arxiv.org/pdf/2404.08700

10. [长文本事实评估、事实密度差异；Findings] VeriScore: Evaluating the factuality of verifiable claims in long-form text generation
Yixiao Song, Yekyung Kim, Mohit Iyyer
马萨诸塞大学阿默斯特分校
https://arxiv.org/pdf/2406.19276


# 幻觉的相关探讨/调研/综述/两面性 (Discussion, Survey, Review, and Dual Nature)   

1. [幻觉定义的探讨、幻觉影响的调研；Main] An Audit on the Perspectives and Challenges of Hallucinations in NLP
Pranav Narayanan Venkit, Tatiana Chakravorti, Vipul Gupta, Heidi Biggs, Mukund Srinath, Koustava Goswami, Sarah Rajtmajer, Shomir Wilson
宾夕法尼亚州立大学、Adobe Research、佐治亚理工学院
https://arxiv.org/pdf/2404.07461v2

2. [大语言模型事实性综述；Main] Factuality of Large Language Models in the Year 2024
Yuxia Wang, Minghan Wang, Muhammad Arslan Manzoor, Fei Liu, Georgi Nenkov Georgiev, Rocktim Jyoti Das, Preslav Nakov
MBZUAI、莫纳什大学、LibrAI、谷歌、索菲亚大学
https://arxiv.org/pdf/2402.02420

3. [新知识微调对幻觉倾向的影响；Main] Does Fine-Tuning LLMs on New Knowledge Encourage Hallucinations?
Zorik Gekhman, Gal Yona, Roee Aharoni, Matan Eyal, Amir Feder, Roi Reichart, Jonathan Herzig
以色列理工学院、Google Research
https://arxiv.org/pdf/2405.05904

4. [空样本提示对幻觉倾向的影响；Main] Null-Shot Prompting: Rethinking Prompting Large Language Models With Hallucination
Pittawat Taveekitworachai, Febri Abdullah, Ruck Thawonmas
日本立命馆大学
https://openreview.net/pdf?id=xC8KTvexaJ

5. [模型编辑对无偏性和事实性的负面影响；Main] “Flex Tape Can’t Fix That”: Bias and Misinformation in Edited Language Models
Karina H Halevy, Anna Sotnikova, Badr AlKhamissi, Syrielle Montariol, Antoine Bosselut
洛桑联邦理工学院、卡耐基梅隆大学、马里兰大学帕克分校
https://arxiv.org/pdf/2403.00180

6. [多语言版本的FActScore分析；Main] An Analysis of Multilingual FActScore
Vu Trong Kim, Michael Krumdick, Varshini Reddy, Franck Dernoncourt, Viet Dac Lai
KAIST、Kensho Technologies、Adobe Research
https://arxiv.org/pdf/2406.19415

7. [视频理解、幻觉对模型推理的正向作用；Findings] Navigating Hallucinations for Reasoning of Unintentional Activities
Shresth Grover, Vibhav Vineet, Yogesh S Rawat
印度理工学院坎普尔分校、Microsoft Research、中佛罗里达大学
https://arxiv.org/pdf/2402.19405

8. [多模态的幻觉综述；Findings] Unveiling Hallucination in Text, Image, Video, and Audio Foundation Models: A Comprehensive Review
Pranab Sahoo, Prabhash Meharia, Akash Ghosh, Sriparna Saha, Vinija Jain, Aman Chadha
印度理工学院巴特那分校、斯坦福大学、Amazon GenAI
https://arxiv.org/pdf/2405.09589v4

9. [LLM事实记忆的缩放定律；Findings] Scaling Laws for Fact Memorization of Large Language Models
Xingyu Lu, Xiaonan Li, Qinyuan Cheng, Kai Ding, Xipeng Qiu
复旦大学、INTSIG
https://arxiv.org/pdf/2406.15720