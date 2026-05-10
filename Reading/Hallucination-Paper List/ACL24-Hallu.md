CCF-A类自然语言处理领域顶级会议第62届计算语言学学会年会（ACL 2024）在泰国曼谷举行。这是2018年之后第一次在亚太地区线下举行的ACL年会（原定于2021年在曼谷举办的第59届ACL因疫情改为线上举行）。

本次会议主会共录用论文841篇（其中长文772篇、短文69篇），与去年的1077篇相比明显减少；Findings共录用论文976篇，与去年的902篇相比有所增长。主会、Findings及伴随研讨会论文集见

https://aclanthology.org/events/acl-2024/

本文主要整理了大语言模型幻觉的检测与减缓方法、评估基准和两面性探讨等方面的论文，共计36篇。

# 幻觉检测相关 (Hallucination Detection)
1. [多模态、多任务；Main] Unified Hallucination Detection for Multimodal Large Language Models
Xiang Chen, Chenxi Wang, Yida Xue, Ningyu Zhang, Xiaoyan Yang, Qiang Li, Yue Shen, Lei Liang, Jinjie Gu, Huajun Chen
浙江大学、蚂蚁
https://aclanthology.org/2024.acl-long.178/

2. [置信度估计量化；Main] Factual Confidence of LLMs: on Reliability and Robustness of Current Estimators
Matéo Mahaut, Laura Aina, Paula Czarnowska, Momchil Hardalov, Thomas Müller, Lluis Marquez
庞培法布拉大学、AWS AI Labs
https://aclanthology.org/2024.acl-long.250/

3. [黑盒检测、答案反推问题+采样一致性；Main] InterrogateLLM: Zero-Resource Hallucination Detection in LLM-Generated Answers
Yakir Yehuda, Itzik Malkiel, Oren Barkan, Jonathan Weill, Royi Ronen, Noam Koenigstein
微软、以色列理工学院、英国开放大学、特拉维夫大学
https://aclanthology.org/2024.acl-long.506/

4. [离线一致性检查、探针检测；Main] Transferable and Efficient Non-Factual Content Detection via Probe Training with Offline Consistency Checking
Xiaokang Zhang, Zijun Yao, Jing Zhang, Kaifeng Yun, Jifan Yu, Juanzi Li, Jie Tang
中国人民大学、清华大学
https://aclanthology.org/2024.acl-long.668/

5. [机器翻译中的幻觉检测；Findings] OTTAWA: Optimal TransporT Adaptive Word Aligner for Hallucination and Omission Translation Errors Detection
Chenyang Huang, Abbas Ghaddar, Ivan Kobyzev, Mehdi Rezagholizadeh, Osmar Zaiane, Boxing Chen
阿尔伯塔大学、华为诺亚方舟实验室
https://aclanthology.org/2024.findings-acl.377/

6. [多模态、逻辑一致性；Findings] Logical Closed Loop: Uncovering Object Hallucinations in Large Vision-Language Models
Junfei Wu, Qiang Liu, Ding Wang, Jinghao Zhang, Shu Wu, Liang Wang, Tieniu Tan
中国科学院自动化研究所、中国科学院大学、南京大学
https://aclanthology.org/2024.findings-acl.414/

7. [词元级不确定性量化、条件概率增强；Findings] Fact-Checking the Output of Large Language Models via Token-Level Uncertainty Quantification
Ekaterina Fadeeva, Aleksandr Rubashevskii, Artem Shelmanov, Sergey Petrakov, Haonan Li, Hamdy Mubarak, Evgenii Tsymbalov, Gleb Kuzmin, Alexander Panchenko, Timothy Baldwin, Preslav Nakov, Maxim Panov
MBZUAI、AIRI、斯科尔科沃科技研究院人工智能研究中心、俄罗斯国家研究型高等经济大学、 俄罗斯科学院计算机科学与控制联邦研究中心、墨尔本大学、卡塔尔计算研究所
https://aclanthology.org/2024.findings-acl.558/

8. [内部表征检测；Findings] LLM Factoscope: Uncovering LLMs' Factual Discernment through Measuring Inner States
Jinwen He, Yujia Gong, Zijin Lin, Cheng’an Wei, Yue Zhao, Kai Chen
中国科学院信息工程研究所、中国科学院大学
https://aclanthology.org/2024.findings-acl.608/

9. [数据增强+检测器微调；Findings] Enhancing Hallucination Detection through Perturbation-Based Synthetic Data Generation in System Responses
Dongxu Zhang, Varun Gangal, Barrett Lattimer, Yi Yang
ASAPP
https://aclanthology.org/2024.findings-acl.789/

10. [内部表征检测、幻觉数据集；Findings] Unsupervised Real-Time Hallucination Detection based on the Internal States of Large Language Models
Weihang Su, Changyue Wang, Qingyao Ai, Yiran Hu, Zhijing Wu, Yujia Zhou, Yiqun Liu
清华大学、北京理工大学、中国人民大学
https://aclanthology.org/2024.findings-acl.854/

# 幻觉减缓相关 (Hallucination Mitigation)
1. [LLM自我评估；Main] Self-Alignment for Factuality: Mitigating Hallucinations in LLMs via Self-Evaluation
Xiaoying Zhang, Baolin Peng, Ye Tian, Jingyan Zhou, Lifeng Jin, Linfeng Song, Haitao Mi, Helen Meng
香港中文大学、腾讯AI Lab、香港博智感知交互研究中心
https://aclanthology.org/2024.acl-long.107/

2. [事实语义解耦、探针编辑；Main] TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space
Shaolei Zhang, Tian Yu, Yang Feng
中国科学院计算技术研究所、中国科学院大学、智能算法安全重点实验室(中国科学院)
https://aclanthology.org/2024.acl-long.483/

3. [多模态、根据EOS信号及时终止输出；Main] Less is More: Mitigating Multimodal Hallucination from an EOS Decision Perspective
Zihao Yue, Liang Zhang, Qin Jin
中国人民大学
https://aclanthology.org/2024.acl-long.633/

4. [答案引文生成、事实一致性；Main] Learning to Generate Answers with Citations via Factual Consistency Models
Rami Aly, Zhiqiang Tang, Samson Tan, George Karypis
剑桥大学、AWS
https://aclanthology.org/2024.acl-long.641/

5. [多模态对话中的幻觉滚雪球、残差视觉解码；Main] Investigating and Mitigating the Multimodal Hallucination Snowballing in Large Vision-Language Models
Weihong Zhong, Xiaocheng Feng, Liang Zhao, Qiming Li, Lei Huang, Yuxuan Gu, Weitao Ma, Yuan Xu, Bing Qin
哈尔滨工业大学、鹏城实验室
https://aclanthology.org/2024.acl-long.648/

6. [多模型协作；Main] Don’t Hallucinate, Abstain: Identifying LLM Knowledge Gaps via Multi-LLM Collaboration
Shangbin Feng, Weijia Shi, Yike Wang, Wenxuan Ding, Vidhisha Balachandran, Yulia Tsvetkov
华盛顿大学、加州大学伯克利分校、香港科技大学、卡内基梅隆大学
https://arxiv.org/pdf/2402.00367

7. [同声传译中的幻觉；Main(Short)] On the Hallucination in Simultaneous Machine Translation
Meizhi Zhong, Kehai Chen, Zhengshan Xue, Lemao Liu, Mingming Yang, Min Zhang
哈尔滨工业大学（深圳）、天津大学
https://aclanthology.org/2024.acl-short.66/

8. [临床文本摘要、生成后校正；Findings] Better Late Than Never: Model-Agnostic Hallucination Post-Processing Framework Towards Clinical Text Summarization
Songda Li, Yunqi Zhang, Chunyuan Deng, Yake Niu, Hui Zhao
华东师范大学、佐治亚理工学院、上海市高可信计算重点实验室
https://aclanthology.org/2024.findings-acl.59/

9. [事实验证链、回答一致性；Findings] Chain-of-Verification Reduces Hallucination in Large Language Models
Shehzaad Dhuliawala, Mojtaba Komeili, Jing Xu, Roberta Raileanu, Xian Li, Asli Celikyilmaz, Jason Weston
Meta AI、苏黎世联邦理工学院
https://aclanthology.org/2024.findings-acl.212/

10. [文本到SQL、任务对齐；Findings] Before Generation, Align it! A Novel and Effective Strategy for Mitigating Hallucinations in Text-to-SQL Generation
Ge Qu, Jinyang Li, Bowen Li, Bowen Qin, Nan Huo, Chenhao Ma, Reynold Cheng
香港大学，上海人工智能实验室、北京智源人工智能研究院、香港中文大学（深圳）
https://aclanthology.org/2024.findings-acl.324/

11. [多模态、语言模型对比解码；Findings] Mitigating Hallucinations in Large Vision-Language Models (LVLMs) via Language-Contrastive Decoding (LCD)
Avshalom Manevich, Reut Tsarfaty
巴伊兰大学
https://aclanthology.org/2024.findings-acl.359/

12. [置信度校准、分步推理+自我反思；Findings] Fact-and-Reflection (FaR) Improves Confidence Calibration of Large Language Models
Xinran Zhao, Hongming Zhang, Xiaoman Pan, Wenlin Yao, Dong Yu, Tongshuang Wu, Jianshu Chen
腾讯AI Lab、卡内基梅隆大学
https://aclanthology.org/2024.findings-acl.515/

13. [选取有效上下文、过滤误导信息；Findings] Truth-Aware Context Selection: Mitigating Hallucinations of Large Language Models Being Misled by Untruthful Contexts
Tian Yu, Shaolei Zhang, Yang Feng
中国科学院计算技术研究所、中国科学院大学、智能算法安全重点实验室(中国科学院)
https://aclanthology.org/2024.findings-acl.645/

14. [逻辑运算符表征、推理幻觉；Findings] Strong hallucinations from negation and how to fix them
Swarnadeep Bhar, Nicholas Asher
法国国家科学研究中心、法国图卢兹信息研究所、保罗萨巴蒂尔大学
https://aclanthology.org/2024.findings-acl.752/

15. [多模态、事实增强RLHF；Findings] Aligning Large Multimodal Models with Factually Augmented RLHF
Zhiqing Sun, Sheng Shen, Shengcao Cao, Haotian Liu, Chunyuan Li, Yikang Shen, Chuang Gan, Liangyan Gui, Yu-Xiong Wang, Yiming Yang, Kurt Keutzer, Trevor Darrell
加州大学伯克利分校、卡内基梅隆大学、威斯康辛大学麦迪逊分校、马萨诸塞大学阿默斯特分校、微软研究院、MIT-IBM 沃森人工智能实验室
https://aclanthology.org/2024.findings-acl.775/

16. [多模态、指令对比解码；Findings] Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding
Xintong Wang, Jingheng Pan, Liang Ding, Chris Biemann
汉堡大学、悉尼大学
https://aclanthology.org/2024.findings-acl.937/

# 幻觉评估相关 (Hallucination Evaluation)
1. [中文、无约束续写；Main] UHGEval: Benchmarking the Hallucination of Chinese Large Language Models via Unconstrained Generation
Xun Liang, Shichao Song, Simin Niu, Zhiyu Li, Feiyu Xiong, Bo Tang, Yezhaohui Wang, Dawei He, Cheng Peng, Zhonghao Wang, Haiying Deng
中国人民大学、上海算法创新研究院、新华社媒体融合生产技术与系统国家重点实验室
https://aclanthology.org/2024.acl-long.288/

2. [细粒度评估、幻觉注释器；Main] ANAH: Analytical Annotation of Hallucinations in Large Language Models
Ziwei Ji, Yuzhe Gu, Wenwei Zhang, Chengqi Lyu, Dahua Lin, Kai Chen
上海人工智能实验室、香港科技大学、香港中文大学
https://aclanthology.org/2024.acl-long.442/

3. [RAG响应的词级幻觉，检测方法评估；Main] RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models
Cheng Niu, Yuanhao Wu, Juno Zhu, Siliang Xu, KaShun Shum, Randy Zhong, Juntong Song, Tong Zhang
NewsBreak、伊利诺伊大学厄巴纳-香槟分校
https://aclanthology.org/2024.acl-long.585/

4. [评测基准、机理分析、缓解等系统性研究；Main] The Dawn After the Dark: An Empirical Study on Factuality Hallucination in Large Language Models
Junyi Li, Jie Chen, Ruiyang Ren, Xiaoxue Cheng, Xin Zhao, Jian-Yun Nie, Ji-Rong Wen
中国人民大学、蒙特利尔大学
https://aclanthology.org/2024.acl-long.586/

5. [多模态、场景一致性+多轮VQA；Main] VisDiaHalBench: A Visual Dialogue Benchmark For Diagnosing Hallucination in Large Vision-Language Models
Qingxing Cao, Junhao Cheng, Xiaodan Liang, Liang Lin
中山大学、MBZUAI、DarkMatter AI Research
https://aclanthology.org/2024.acl-long.658/

6. [对话摘要的忠实性幻觉评估；Main] Analyzing LLM Behavior in Dialogue Summarization: Unveiling Circumstantial Hallucination Trends
Sanjana Ramprasad, Elisa Ferracane, Zachary Lipton
美国东北大学、Abridge AI
https://aclanthology.org/2024.acl-long.677/

7. [角色扮演中的即时角色幻觉评估；Findings] TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models
Jaewoo Ahn, Taehyun Lee, Junyoung Lim, Jin-Hwa Kim, Sangdoo Yun, Hwaran Lee, Gunhee Kim
首尔大学、NAVER AI Lab
https://aclanthology.org/2024.findings-acl.197/

8. [多模态、数据集扩充；Findings] Visual Hallucinations of Multi-modal Large Language Models
Wen Huang, Hongbin Liu, Minxin Guo, Neil Gong
中国科学技术大学、杜克大学、香港大学
https://aclanthology.org/2024.findings-acl.573/

9. [摘要幻觉、原子事实评估；Findings] ACUEval: Fine-grained Hallucination Evaluation and Correction for Abstractive Summarization
David Wan, Koustuv Sinha, Srini Iyer, Asli Celikyilmaz, Mohit Bansal, Ramakanth Pasunuru
北卡罗来纳大学教堂山分校、FAIR at Meta
https://aclanthology.org/2024.findings-acl.597/

# 幻觉的两面性探讨 (Discussion)
1. [更强的叙述性和语义连贯性；Main] Confabulation: The Surprising Value of Large Language Model Hallucinations
Peiqi Sui, Eamon Duede, Sophie Wu, Richard So
麦吉尔大学、哈佛大学
https://aclanthology.org/2024.acl-long.770/