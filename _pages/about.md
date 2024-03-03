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

刘成龙，男，副教授，同济大学交通科学与技术研究院副院长。入选上海市启明星科技人才、中国公路学会青年托举人才、上海35人青年科技引领计划等。担任联合国亚太经济社会组织（ESCAP）咨询专家、世界交通运输大会(WTC)数字化运维技术委员会秘术委员 、上海市公路学会养护与管理专委会委员等。主要从事道路工程与信息工程交叉方向研究，建立了路面行驶质量轻量化检测技术与高频多维的道路服役状态精细化评价方法，提出了基于细粒度时空数据的道路基础设施管养优化理论，推动了以“轻量化快速巡检”为特征的道路设施数字化管养技术转型。研究成果在AIC、Transport Res. C、IEEE Trans. ITS、中国公路学报等高水平期刊发表研究论文50余篇，多项研究成果相继被遴选为IEEE ITSM封面论文、ESI高被引论文/热点论文、中国公路学报年度优秀论文、交通部重大科技成果(论文类)、COTA Best Presentation Award等。相关成果获授权中国、美国、英国、国际专利30余项，荣获中国专利优秀奖、上海市百强高价值专利等，并实现了产业化应用，覆盖全国二十余省份应用里程超40万公里。作为主要完成人获得上海市科技进步一等奖、中国公路学会科学技术特等奖/一等奖、中国交通运输协会科学进步一等奖、中国发明协会发明创新一等奖等9项。

# 📖 Educations
- *2010.09 - 2014.06*, [同济大学](https://www.tongji.edu.cn/), 交通工程, 学士.
- *2017.09 - 2018.09*, [华盛顿大学](https://www.washington.edu/), 土木环境工程, 联合培养博士.
- *2014.09 - 2019.06*, [同济大学](https://www.tongji.edu.cn/), 交通运输工程, 博士.

# 💻 Professional Experiences
- *2019.12 - 2022.12*, [同济大学](https://www.tongji.edu.cn/), 交通运输工程学院, 博士后.
- *2021.05 - 至今*,    [同济大学](https://www.tongji.edu.cn/), 交通科学与技术研究院, 副教授.
- *2023.02 - 至今*   , [同济大学](https://www.tongji.edu.cn/), 交通运输工程学院, 副教授.
- *2024.01 - 至今* ,   [同济大学](https://www.tongji.edu.cn/), 交通运输工程学院, 副院长.

# 🔍 Projects

# 📝 Publications 
📃 Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Cross-scene pavement distress detection by a novel transfer learning framework](https://onlinelibrary.wiley.com/doi/abs/10.1111/mice.12674)

Yishun Li, Pengyu Che, **Chenglong Liu**, Difei Wu, Yuchuan Du

We presents a framework for the cross-scenedeployment of distress detection models based on TL anda GAN. This framework dramatically assists deep learn-ing distress detection models deployed in new scenarioswithout degrading prediction performance. With the sameaccuracy, this method reduced the need for training databy at least 25%. Using the same amount of training data,this method also improved the mAP by about 26.55%.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Large-scale pavement roughness measurements with vehicle crowdsourced data using semi-supervised learning](https://www.sciencedirect.com/science/article/pii/S0968090X21000784)

**Chenglong Liu**, Difei Wu, Yishun Li, Yuchuan Du

We proposed an SSL model to rapidly evaluate large-scale pavement roughness based on crowdsourced data of multiple vehicles. The relationship between pavement roughness and in-car vibrations was mathematically derived using a PSD analysis and an LTI system. Based on the multi-vehicle vibration data, a self-training algorithm was devised that used both labeled and unlabeled data to comprehensively evaluate the IRIs. The confidences of the vehicular parameters and the IRI estimations were considered to ensure that we obtained the most reliable results in each iteration. A full-car simulation environment with eight degrees-of-freedom was constructed to verify the effectiveness of the proposed model. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='images/3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Comfortable and energy-efficient speed control of autonomous vehicles on rough pavements using deep reinforcement learning](https://www.sciencedirect.com/science/article/pii/S0968090X21004757)

Yuchuan Du, Jing Chen, Cong Zhao, **Chenglong Liu**, Feixiong Liao, Ching-Yao Chan

We proposed a speed control framework on rough pavement based on the crowdsourced data. We suggest the concept of the maximum comfortable speed to represent the vertical ride comfort of the oncoming road in this framework. A speed control model based on deep reinforcement learning was designed, trained, and tested with the real-world rough pavements in Shanghai, China. To balance driving efficiency, ride comfort, and energy efficiency requirements, the reward function is designed with the consideration of speed, vertical vibration, longitudinal jerk, longitudinal acceleration, and vehicle-specific power.
</div>
</div>

- ``International Journal of Pavement Engineering 2024`` Fast calibration for vibration-based pavement roughness measurement based on model updating of vehicle dynamics, Difei Wu, **Chenglong Liu**, Bohao Qin, Sheng Zhong, Xiaoming Zhang, Yuchuan Du
- ``Automation in Construction 2024`` Advances in automatic identification of road subsurface distress using ground penetrating radar: State of the art and future trends, **Chenglong Liu**, Yuchuan Du, Guanghua Yue, Yishun Li, Difei Wu, Feng Li
- ``IEEE transactions on intelligent transportation systems 2023`` Fine-Grained Pavement Performance Prediction Based on Causal-Temporal Graph Convolution Networks, Wenyuan Cai, Andi Song, Yuchuan Du, **Chenglong Liu**, Difei Wu, Feng Li
- ``Applied Sciences 2023`` Differences evaluation of pavement roughness distribution based on light detection and ranging data, Qian Gao,Lei Fan,Siyu Wei,Yishun Li,Yuchuan Du, **Chenglong Liu**
- ``交通运输研究 2023`` 基于LiDAR三维数据的路面平整度横向分布差异特性评估方法, **刘成龙**, 魏斯瑀, 高倩, 吴荻非, 曹静, 杜豫川
- ``Automation in Construction 2023`` Modeling automatic pavement crack object detection and pixel-level segmentation, Yuchuan Du, Shan Zhong, Hongyuan Fang, Niannian Wang, **Chenglong Liu**, Difei Wu, Yan Sun, Mang Xiang
- ``IJTST 2023`` Enabling Edge Computing Ability in View-Independent Vehicle Model Recognition, **Chenglong Liu**, Ziyuan Pu, Yishun Li, Ying Jiang, Yinhai Wang, Yuchuan Du
- ``中国公路学报 2023`` 探地雷达多特征融合的城市空洞自动识别方法研究, 杜豫川, 岳光华, **刘成龙**, 李峰, 蔡文才

# 📚 Patents
- 一种基于三维纹理特征的沥青路面混合料级配预估方法(ZL202110211816.9)
- 一种基于实时需求的无人驾驶公交派车方法(ZL202010755992.4)
- 一种基于关联规则分析的道路深层病害预警方法(ZL202110215728.6)
- A method for leakage detection of underground corridor based on static infrared thermal image processing(GB2569751)
- Comfort-based self-driving planning method(US 11,447,150 B2)
- Method of controlling automated driving speed based on comfort level(WO/2018/122586)

# 🏆 Honors and Awards
🏅 Honors
- 🔥`New！`*2023* 中国交通协会科技进步一等奖 高速公路数智养护与决策平台建设关键技术研究及开发
- 🔥`New！`*2023* 中国交通协会科技进步二等奖 北部湾湿热地区沥青路面病害智能识别与功能提升关键技术及应用
- 🔥`New！`*2023* 《中国公路学报》年度优秀论文二等奖
- 🔥`New！`*2023* 联合国报告证明 Supporting the policies on green and resilient transport infrastructure along the Asian Highway Network
- 🔥`New！`*2023* 高PCSI、高被引、高下载论文 新一代智慧高速公路系统架构设计
- *2023* 同济大学研究生先生精品课程 交通数据分析与应用
- *2023* 上海产学研合作优秀项目奖三等奖 道路多维高频检测装备和智能养护技术及应用
- *2023* 中国公路学会科学技术奖特等奖 长距离高速公路智能建造与运维关键技术研究及应用
- *2023* 上海市公路学会科技进步奖二等奖

📚 Foundations
- 🔥*2023* 上海市科技创新行动计划-道路基础设施多维体征的数字化感知与评价方法研究
- 🔥*2023* 国家重点研发计划-智能网联道路交通系统的能源自洽技术
- 🔥*2023* 同济大学交叉学科项目-知识-数据协同驱动的精细化道路养护策略生成方法
- *2021* 国家自然基金青年项目-众筹数据驱动的城市路网平整度感知方法研究

# 💼 Societies
- *2023*, 上海青年科技启明星
- *2022*, 中国公路学会青年托举人才
- *2019*, 上海市超级博士后
- 联合国亚太经济社会组织咨询专家（Transport Division）
- 世界交通运输大会数字化运维技术委员会 秘术委员
- 上海市公路学会公路养护与运行专委会委员

