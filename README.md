## [Paper List] LLM4DB

A collection of papers and resources related to applying LLM techniques in data management (e.g., data processing, data optimization, and data analysis)

Kindly let us know if we have missed any great papers. Thank you!

Table of Contents
=================

* [0. System and Review](#0-system-and-review)
* [1. LLM for Data Processing](#1-llm-for-data-processing)
  * [1.1 Data Cleaning](#11-data-cleaning)
  * [1.2 Entity Matching](#12-entity-matching)
  * [1.3 Schema Matching](#13-schema-matching)
  * [1.4 Data Discovery](#14-data-discovery)
* [2. LLM for Database Optimization](#2-llm-for-database-optimization)
  * [2.1 Knob Tuning](#21-knob-tuning)
  * [2.2 Database Diagnosis](#22-database-diagnosis)
* [3. LLM for Data Analysis](#3-llm-for-data-analysis)
  * [3.1 NL2SQL](#31-nl2sql)
  * [3.2 Data Exploration](#32-data-exploration)
  * [3.3 Data Visualization](#33-data-visualization)
* [4. Data Management for LLM](#4-data-management-for-llm)

## 0. System and Review

**How Large Language Models Will Disrupt Data Management**

*Raul Castro Fernandez, Aaron J. Elmore, Michael J. Franklin, Sanjay Krishnan, Chenhao Tan. VLDB 2023.* [[pdf](https://www.vldb.org/pvldb/vol16/p3302-fernandez.pdf)]

**From Large Language Models to Databases and Back: A Discussion on Research and Education**

*Sihem Amer-Yahia, Angela Bonifati, Lei Chen, Guoliang Li, Kyuseok Shim, Jianliang Xu, Xiaochun Yang. SIGMOD Record.* [[pdf](https://sigmodrecord.org/publications/sigmodRecord/2309/pdfs/09_OpenForum_AmerYahia.pdf)]

**DB-GPT: Large Language Model Meets Database**

*Xuanhe Zhou, Zhaoyan Sun, Guoliang Li. Data Science and Engineering 2023.* [[pdf](http://dbgroup.cs.tsinghua.edu.cn/ligl/papers/dbgpt-dse.pdf)]

**LLM-Enhanced Data Management**

*Xuanhe Zhou, Xinyang Zhao, Guoliang Li. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2402.02643)]

**Can Foundation Models Wrangle Your Data?**

*Avanika Narayan, Ines Chami, Laurel J. Orr, Christopher Ré. VLDB 2022.* [[pdf](https://www.vldb.org/pvldb/vol16/p738-narayan.pdf)]

**LLM for Data Management**

*Guoliang Li, Xuanhe Zhou, Xinyang Zhao. VLDB 2024 Tutorial.* [[pdf](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/p2031-li-vldb2024.pdf)]

**Data Management For Training Large Language Models: A Survey**

*Zige Wang, Wanjun Zhong, Yufei Wang, Qi Zhu, Fei Mi, Baojun Wang, Lifeng Shang, Xin Jiang, Qun Liu. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2312.01700)]

**When Large Language Models Meet Vector Databases: A Survey**

*Zhi Jing, Yongye Su, Yikun Han, Bo Yuan, Haiyun Xu, Chunjiang Liu, Kehai Chen, Min Zhang. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2402.01763)]

**From BERT to GPT-3 Codex: Harnessing the Potential of Very Large Language Models for Data Management**

*Immanuel Trummer. VLDB 2023.* [[pdf](https://www.vldb.org/pvldb/vol15/p3770-trummer.pdf)]

## 1. LLM for Data Processing

### 1.1 Data Cleaning

**Jellyfish: A Large Language Model for Data Preprocessing.**

*Haochen Zhang, Yuyang Dong, Chuan Xiao, Masafumi Oyamada. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2312.01678)]

**LLMs with User-defined Prompts as Generic Data Operators for Reliable Data Processing**

*Luyi Ma, Nikhil Thakurdesai, Jiao Chen, Jianpeng Xu, Evren Körpeoglu, Sushant Kumar, Kannan Achan. IEEE Big Data 2023.* [[pdf](https://arxiv.org/pdf/2312.16351)]

**CleanAgent: Automating Data Standardization with LLM-based Agents**

*Danrui Qi, Jiannan Wang. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2403.08291)]

**LLMClean: Context-Aware Tabular Data Cleaning via LLM-Generated OFDs**

*Fabian Biester, Mohamed Abdelaal, Daniel Del Gaudio. arxiv 2024.* [[pdf](https://arxiv.org/abs/2404.18681)]

**SEED: Domain-Specific Data Curation With Large Language Models**

*Zui Chen, Lei Cao, Sam Madden, Tim Kraska, Zeyuan Shang, Ju Fan, Nan Tang, Zihui Gu, Chunwei Liu, Michael Cafarella. arxiv 2023.* [[pdf](https://arxiv.org/pdf/2310.00749)]

**Large Language Models as Data Preprocessors**

*Haochen Zhang, Yuyang Dong, Chuan Xiao, Masafumi Oyamada. arxiv 2023.* [[pdf](https://arxiv.org/pdf/2308.16361)]


### 1.2 Entity Matching

**Cost-Effective In-Context Learning for Entity Resolution: A Design Space Exploration**

*Meihao Fan, Xiaoyue Han, Ju Fan, Chengliang Chai, Nan Tang, Guoliang Li, Xiaoyong Du. ICDE 2024.* [[pdf](https://arxiv.org/pdf/2312.03987)]

**Match, Compare, or Select? An Investigation of Large Language Models for Entity Matching**

*Tianshu Wang, Hongyu Lin, Xiaoyang Chen, Xianpei Han, Hao Wang, Zhenyu Zeng, Le Sun. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2405.16884)]

**Unicorn: A Unified Multi-tasking Model for Supporting Matching Tasks in Data Integration**

*Jianhong Tu, Ju Fan, Nan Tang, Peng Wang, Guoliang Li, Xiaoyong Du. SIGMOD 2023.* [[pdf](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/Unicorn_PACMMOD.pdf)]

**Entity matching using large language models**

*Ralph Peeters, Christian Bizer. arxiv 2023.* [[pdf](https://arxiv.org/pdf/2310.11244)]

**Deep Entity Matching with Pre-Trained Language Models**

*Yuliang Li, Jinfeng Li, Yoshihiko Suhara, AnHai Doan, Wang-Chiew Tan. VLDB 2021.* [[pdf](https://www.vldb.org/pvldb/vol14/p50-li.pdf)]

**Dual-Objective Fine-Tuning of BERT for Entity Matching**

*Ralph Peeters, Christian Bizer. VLDB 2021.* [[pdf](https://madoc.bib.uni-mannheim.de/59958/1/p1913-peeters.pdf)]

### 1.3 Schema Matching

**Schema Matching with Large Language Models: an Experimental Study**

*Marcel Parciak, Brecht Vandevoort, Frank Neven, Liesbet M. Peeters, Stijn Vansummeren. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2407.11852)]

**Schema Matching using Pre-Trained Language Models**

*Yunjia Zhang, Avrilia Floratou, Joyce Cahoon, Subru Krishnan, Andreas C. Müller, Dalitso Banda, Fotis Psallidas, Jignesh M. Patel. ICDE 2023.* [[pdf](https://ieeexplore.ieee.org/document/10184612)]

### 1.4 Data Discovery

**CHORUS: Foundation Models for Unified Data Discovery and Exploration**

*Moe Kayali, Anton Lykov, Ilias Fountalis, Nikolaos Vasiloglou, Dan Olteanu, Dan Suciu. VLDB 2024.* [[pdf](https://www.vldb.org/pvldb/vol17/p2104-kayali.pdf)]

**Language Models Enable Simple Systems for Generating Structured Views of Heterogeneous Data Lakes**

*Simran Arora, Brandon Yang, Sabri Eyuboglu, Avanika Narayan, Andrew Hojel, Immanuel Trummer, Christopher Ré. VLDB 2024.* [[pdf](https://www.vldb.org/pvldb/vol17/p92-arora.pdf)]

**DeepJoin: Joinable Table Discovery with Pre-trained Language Models**

*Yuyang Dong, Chuan Xiao, Takuma Nozawa, Masafumi Enomoto, Masafumi Oyamada. VLDB 2023.* [[pdf](https://www.vldb.org/pvldb/vol16/p2458-dong.pdf)]


## 2. LLM for Database Optimization

### 2.1 Knob Tuning

**Is Large Language Model Good at Database Knob Tuning? A Comprehensive Experimental Evaluation**

*Yiyan Li, Haoyang Li, Zhao Pu, Jing Zhang, Xinyi Zhang, Tao Ji, Luming Sun, Cuiping Li, Hong Chen*. [[pdf](https://arxiv.org/abs/2408.02213)]

**GPTuner: A Manual-Reading Database Tuning System via GPT-Guided Bayesian Optimization**

*Jiale Lao, Yibo Wang, Yufei Li, Jianping Wang, Yunjia Zhang, Zhiyuan Cheng, Wanghu Chen, Mingjie Tang, Jianguo Wang. VLDB 2024.* [[pdf](https://dl.acm.org/doi/10.14778/3659437.3659449)]

**DB-BERT: a Database Tuning Tool that “Reads the Manual”**

*Immanuel Trummer. SIGMOD 2022.* [[pdf](https://dl.acm.org/doi/10.1145/3514221.3520171)]


### 2.2 Database Diagnosis

**Panda: Performance debugging for databases using LLM agents**

*Vikramank Singh, Kapil Eknath Vaidya, ..., Tim Kraska. CIDR 2024*. [[pdf](https://www.amazon.science/publications/panda-performance-debugging-for-databases-using-llm-agents)]

**LLM As DBA**

*Xuanhe Zhou, Guoliang Li, Zhiyuan Liu. arXiv 2023*. [[pdf](https://arxiv.org/abs/2308.05481)]

**D-Bot: Database Diagnosis System using Large Language Models** 

*Xuanhe Zhou, Guoliang Li, Zhaoyan Sun, Zhiyuan Liu, Weize Chen, et al. VLDB 2024.* [[pdf](https://arxiv.org/pdf/2312.01454.pdf)] [[code](https://github.com/TsinghuaDatabaseGroup/DB-GPT)]  

## 3. LLM for Data Analysis

### 3.1 NL2SQL

**The Dawn of Natural Language to SQL: Are We Fully Ready?**

*Boyan Li, Yuyu Luo, Chengliang Chai, Guoliang Li, Nan Tang. VLDB 2024* [[pdf](https://arxiv.org/pdf/2406.01265)]

**From BERT to GPT-3 Codex: Harnessing the Potential of Very Large Language Models for Data Management**

*Immanuel Trummer. VLDB 2022.* [[pdf](https://www.vldb.org/pvldb/vol15/p3770-trummer.pdf)]

**Few-shot Text-to-SQL Translation using Structure and Content Prompt Learning**

*Zihui Gu, Ju Fan, Nan Tang, et al. SIGMOD 2023.* [[pdf](http://iir.ruc.edu.cn/~fanj/papers/sigmod2023-scprompt.pdf)]


### 3.2 Data Exploration

**Db-gpt: Empowering database interactions with private large language models**

*Siqiao Xue, Caigao Jiang, Wenhui Shi, Fangyin Cheng, Keting Chen, Hongjun Yang, Zhiping Zhang, Jianshan He, Hongyang Zhang, Ganglin Wei, Wang Zhao, Fan Zhou, Danrui Qi, Hong Yi, Shaodong Liu, Faqiang Chen. arxiv 2023.* [[pdf](https://arxiv.org/pdf/2312.17449)]

### 3.3 Data Visualization

**LLM4Vis: Explainable Visualization Recommendation using ChatGPT**

*Lei Wang, Songheng Zhang, Yun Wang, Ee-Peng Lim, Yong Wang. EMNLP 2023.* [[pdf](https://aclanthology.org/2023.emnlp-industry.64.pdf)]

## 4. Data Management for LLM

**Data-Juicer: A One-Stop Data Processing System for Large Language Models**

*Daoyuan Chen, Yilun Huang, Zhijian Ma, Hesen Chen, Xuchen Pan, Ce Ge, Dawei Gao, Yuexiang Xie, Zhaoyang Liu, Jinyang Gao, Yaliang Li, Bolin Ding, Jingren Zhou. SIGMOD 2024.* [[pdf](https://arxiv.org/pdf/2309.02033)]

**Relational Database Augmented Large Language Model**

*Zongyue Qin, Chen Luo, Zhengyang Wang, Haoming Jiang, Yizhou Sun. arxiv 2024.* [[pdf](https://arxiv.org/pdf/2407.15071)]

**Survey of Vector Database Management Systems**

*James Jie Pan, Jianguo Wang, Guoliang Li. arxiv 2023.* [[pdf](https://arxiv.org/pdf/2310.14021)]
