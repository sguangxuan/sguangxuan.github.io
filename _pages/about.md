---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


Thank you for visiting my website! I'm always happy to connect—feel free to reach out.

My research interests lie at the intersection of knowledge graphs and large language models, particularly in their application to scientific data analysis in materials science. I also have a growing interest in exploring how these technologies can support medical research. I am currently pursuing my Ph.D. under the supervision of Prof. Dongmei Fu and the co-supervision of Prof. Dawei Zhang at the University of Science and Technology Beijing (USTB).

A guiding principle I live by is: **Do good work, and don’t worry too much about the outcome. (但行好事，莫问前程。)** I believe that focusing on meaningful efforts will naturally lead to meaningful results.


<!-- # 🔥 News -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/NRKG-500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bridging the Semantic-Numerical Gap: A Numerical Reasoning Method of Cross-modal Knowledge Graph for Material Property Prediction](https://arxiv.org/abs/2312.09744)

**Guangxuan Song**, Dongmei Fu, Zhongwei Qiu, Zijiang Yang, Jiaxin Dai, Lingwei Ma, and Dawei Zhang

[**Code and Dataset**](https://github.com/MatrixBrain/NR-KG) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We proposed NR-KG, a cross-modal knowledge graph framework that jointly models semantic and numerical information for material property prediction.
- By addressing the challenges of small-sample scientific data, NR-KG achieves significant improvements over state-of-the-art methods and contributes new benchmark datasets to the field.
</div>
</div>

<!-- ######################################## -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/TSNet-500x300.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Taylor-Sensus Network: Embracing Noise to Enlighten Uncertainty for Scientific Data](https://arxiv.org/abs/2409.07942)

**Guangxuan Song**, Dongmei Fu, Zhongwei Qiu, Jintao Meng, and Dawei Zhang

<!-- [**Code and Dataset**](https://github.com/MatrixBrain/NR-KG) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We proposed TSNet, a novel Taylor series-based network that explicitly models heteroscedastic noise and estimates both aleatoric and epistemic uncertainty in scientific data.
- TSNet demonstrates superior robustness and predictive performance across various benchmarks, offering a principled approach to uncertainty modeling in AI for Science.
</div>
</div>


<!-- ######################################## -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AECE 2025</div><img src='images/AECE-500x300.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Message Passing Neural Network Framework with Learnable PageRank for Author Impact Assessment](https://aece.ro/abstractplus.php?year=2025&number=1&article=2)

**Guangxuan Song**, Dongmei Fu, and Xiaomeng Wu

<!-- [**Code and Dataset**](https://github.com/MatrixBrain/NR-KG) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We developed NPRNet, a neural-enhanced PageRank framework that integrates graph topology with spatial and attribute information to assess author influence more effectively.
- Our method improves computational efficiency and better reflects current research dynamics, offering a data-driven tool for scholarly evaluation.
</div>
</div>

- [From Knowledge Graph Development to Serving Industrial Knowledge Automation: A Review](https://ieeexplore.ieee.org/abstract/document/9901564/)
  
  **Guangxuan Song**, Dongmei Fu, and Dawei Zhang
  
  **2022 41st Chinese Control Conference (CCC)**

---

- Corrosion Resistant Performance Prediction in High-Entropy Alloys: A Framework for Model, Interpretation and Multi-Dimensional Visualization
  
  **Guangxuan Song**, Dongmei Fu, Weiwei Chang, Zhongheng Fu, Lingwei Ma, and Dawei Zhang
  
  **Corrosion Science (under review)**

---

- Corrosion Resistance Prediction of High-entropy Alloys: Framework and Knowledge Graph-Drive
  
  **Guangxuan Song**, Dongmei Fu, Yongjie Lin, Lingwei Ma, and Dawei Zhang
  
  **npj Materials Degradation (under review)**

---

- [Cross-category prediction of corrosion inhibitor performance based on molecular graph structures via a three-level message passing neural network model](https://www.sciencedirect.com/science/article/abs/pii/S0010938X22006989)
  
  Jiaxin Dai, Dongmei Fu, **Guangxuan Song**, Lingwei Ma, Xin Guo, Arjan Mol, Ivan Cole, and Dawei Zhang
  
  **Corrosion Science 2023**

---

- [A Data-Driven Hybrid Machine Learning and Transfer Learning Algorithm for Long Consecutive Atmospheric Environment Missing Data Imputation](https://ieeexplore.ieee.org/abstract/document/10662572)
  
  Hao Meng, Lizhen Shao, Dongmei Fu, **Guangxuan Song**, and Jintao Meng
  
  **2024 43st Chinese Control Conference (CCC)**

---

- [Extraction of Key Environmental Factors and Construction of the Data-Driven Model for Atmospheric Aging of Polyurethane Coatings](https://ieeexplore.ieee.org/abstract/document/10239958/)
  
  Zhijian Bai, Dongmei Fu, **Guangxuan Song**, Lizheng Shao, and Dawei Zhang
  
  **2023 42st Chinese Control Conference (CCC)**

---

- [A Named Entity Extraction Method for Commonly Used Steel Knowledge Graph](https://link.springer.com/chapter/10.1007/978-981-16-6320-8_74)
  
  Zeqi Ma, Lingwei Ma, Dongmei Fu, Guangxuan Song, and Dawei Zhang
  
  **2021 Chinese Intelligent Systems Conference**

# 🎖 Honors and Awards
- *2020*, First Prize, **International Contest of innovAtioN (iCAN)**, *Calmspoon Stabilizing Tableware*
- *2020*, Gold Award, **“Challenge Cup” Capital College Student Entrepreneurship Competition**, *Calmspoon Stabilizing Tableware* (“挑战杯”省赛金奖)
- *2020*, National Second Prize, **4th “Changfeng Cup” National College Student Big Data Competition**, *Customer profiling for logistics data using knowledge graphs*
- *2021*, Second Prize, **“Maker Beijing” Regional Innovation and Entrepreneurship Competition** – Urban Big Data Track, *Calmspoon Stabilizing Tableware*
- *2024*, Third Prize, **China International College Students Innovation Competition** – Beijing Regional, “YiWenZhi” AI-powered medical assistant for clinical documentation*
- *2024*, Top 100 Teams, **“Jingcai Dachuang” Beijing College Student Innovation and Entrepreneurship Competition** – Healthcare Track, *“YiWenZhi” Intelligent Medical Assistant*

---

- *2021*, **Outstanding Graduate Student Leader**, USTB
- *2022*, **National Scholarship for Doctoral Students**
- *2022*, **“Top 100 Youth in the Communist Youth League”**, Science Star Award, USTB
- *2025*, **May Fourth Youth Medal**, USTB (highest honor of the Communist Youth League at USTB)

# 🧾 Patents

- *2020*, **Electronic Anti-Shake Tableware** (一种电子防抖餐具), Granted, CN110584428B
- *2021*, **Entity Label Clustering Method for Materials Knowledge Graph** (一种材料领域知识图谱的实体标签聚类方法及装置), Under Substantive Examination, CN202111258392.8
- *2022*, **Construction Method for Metallurgical Materials Knowledge Graph** (一种钢铁材料学知识图谱构建方法及系统), Under Substantive Examination, CN202210921904.2
- *2022*, **Method and System for Operating a Materials Data Processing Platform** (一种材料数据处理平台的搭建、运行方法及系统), Under Substantive Examination, CN202211072133.0
- *2022*, **Inference Method for Potential Knowledge in Steel Knowledge Graph** (一种基于钢材知识图谱的钢材潜在知识推理方法及系统), Under Substantive Examination, CN202210611454.7

# 💻 Software Copyrights

- *2022*, **Book Knowledge Extraction Annotation Software** V1.0 (书籍知识抽取标注软件), 2022SR1352750
- *2024*, **Parkinson’s Disease Diagnosis and Medical QA System Based on Knowledge Graph** V1.0 (基于知识图谱的帕金森病诊断与医疗问答系统), 2024SR062116
- *2024*, **Parkinson’s Disease Medical QA Android App** V1.0 (基于知识图谱的帕金森病诊断与医疗问答APP软件), 2024SR0419077
- *2024*, **Materials Corrosion Database Query Software** V1.0 (材料腐蚀数据库数据检索查询软件), 2024SR0704988
- *2024*, **Web-Based Sharing Platform for Corrosion Data Dashboard** V1.0 (材料腐蚀数据库和信息资源网络化共享平台数据大屏网站), 2024SR0750810
- *2024*, **Client Software for Materials Corrosion Data Platform** V1.0 (材料腐蚀数据库和信息资源网络化共享平台网站客户端软件), 2024SR0703838
- *2024*, **Integrated Algorithms for Intelligent Corrosion Data Processing** V1.0 (材料腐蚀数据智能处理算法集成软件), 2024SR0703369
- *2024*, **Medical Risk Assessment System Based on KG and LLMs** V1.0 (基于知识图谱和大语言模型的病历风险评估系统), 2024SR0600394
- *2024*, **Medical Decision Explanation System Based on KG and LLMs** V1.0 (基于知识图谱和大语言模型的医疗决策解释系统), 2024SR0632941

# 📖 Educations
- *2020.09 - Now*, Ph.D in University of Science and Technology Beijing. 
- *2016.09 - 2020.06*, B.S. in University of Science and Technology Beijing.

# 💬 Invited Talks

- *Oct. 2020*, **Entrepreneurial Journey: Bringing Warmth to Innovation**, *iCAN Science Innovation Festival*, Qingdao, China \| [\[video\]](https://www.bilibili.com/video/BV1L54y1r7bc/)
- *Jul. 2022*, **From Knowledge Graphs to Industrial Knowledge Automation: A Survey**, *Chinese Control Conference*, Hefei, China (online presentation)
- *Sep. 2024*, **Knowledge Graphs and Deep Learning in Corrosion Science Data Research**, *9th Scientific Data Conference*, Chengdu, China
- *Oct. 2024*, **Knowledge and Data-driven Framework for Multi-principal Element Alloys: Automated Knowledge Acquisition, Representation, and Rediscovery**, *22nd International Corrosion Congress*, Xi’an, China

# 🔗 Links

I am fortunate to collaborate closely with the following research partners:

- [Zhongwei Qiu](https://ericzw.github.io/). My senior colleague and research mentor, working on human-centric visual perception, multimodal learning, and generative models with applications in healthcare and science.

- [Meijun Wang](https://wmj142326.github.io/). My partner working on autonomous driving and computer vision, with a focus on human pose estimation and pedestrian safety.

- [Xin Qin](https://qinxin97.github.io/). My partner working on industrial process fault diagnosis and optimization.

<div style="text-align: center; margin: 0 auto; width: 200px; display: block;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=G9buaHAOshkl4VxMI_Ns2MdKNcMwxY1ZHk2sxPobsJw"></script>
</div>