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

刘成龙，同济大学副教授，上海市启明星科技人才，中国公路学会青年托举人才，上海市公路学会养护与管理专委会委员。主要从事道路工程与信息工程交叉方向研究，建立了路面行驶质量轻量化检测技术与高频多维的道路服役状态精细化评价方法，提出了基于细粒度时空数据的道路基础设施管养优化理论，推动了以“轻量化快速巡检”为特征的道路设施数字化管养技术转型。研究成果在Transport Res. C、IEEE Trans. ITS、CACAIE、中国公路学报等高水平期刊发表研究论文50余篇，多篇论文入选ESI高被引论文、IEEE ITSM封面论文、中国公路学报热点论文、交通部重大科技创新成果、COTA Best Presentation Award等。相关成果获中国、美国、英国、国际专利PCT20余项，核心专利获中国专利优秀奖、上海市百强高价值专利。多项成果实现了产业化应用，覆盖全国二十余省份应用里程超15万公里。作为主要完成人获得上海市科技进步一等奖、中国公路学会科学技术一等奖、中国发明协会发明创新一等奖、江西公路科技进步一等奖等科技奖项。

# 📖 Educations
- *2010.09 - 2014.06*, [同济大学](https://www.tongji.edu.cn/), 交通工程, 学士
- *2017.09 - 2018.09*, [华盛顿大学](https://www.washington.edu/), 土木环境工程, 联合培养博士
- *2014.09 - 2019.06*, [同济大学](https://www.tongji.edu.cn/), 交通运输工程, 博士.

# 💻 Professional Experiences
- *2019.12 - 2022.12*, [同济大学](https://www.tongji.edu.cn/), 交通运输工程学院, 博士后.
- *2023.02 - 至今*   , [同济大学](https://www.tongji.edu.cn/), 交通运输工程学院, 副教授.

# 🔍 Projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Deep learning has achieved promising results in pavement distress detection.However, the training model’s effectiveness varies according to the data and scenarios acquired by different camera types and their installation positions. It is time consuming and labor intensive to recollect labeled data and retrain a new model every time the scene changes. In this paper, we propose a transfer learning pipeline to address this problem, which enables a distress detection model to be applied to other untrained scenarios. The framework consists of two main components: data transfer and model transfer. The former trains a generative adversarial network to transfer existing image data into a new scene style. Then, attentive CutMix and image melding are applied to insert distress annotations to synthesize the new scene’s labeled data. After data expansion, the latter step transfers the feature extracted by the existing model to the detection application of the new scene through domain adaptation. The effects of varying degrees of knowledge transfer are also discussed. The proposedmethod is evaluated on two data sets from two different scenes with more than 40,000 images totally. This method can reduce the demand for training data by at least 25% when the model is applied in a new scene. With the same number of training images, the proposed method can improve the model accuracy by 26.55%.
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Rapid measurements of large-scale pavement roughness have long been a hot topic in pavement condition evaluation and maintenance. Most traditional methods rely on dedicated devices, such as laser, Lidar and so on, which should be set up on customized vehicles. With the rapid development of sensing technology, vehicles owned by the general public are empowered with the ability to collect vibration measurements themselves. This crowdsourced dataset is convenient, extensive coverage, inexpensive, and has high sampling frequency, making it a suitable source for large-scale pavement roughness evaluation. However, vehicle information is missing for these data due to privacy protection, which renders them quite difficult to directly use with traditional model-based methods. Thus, in this paper, we propose a semi-supervised learning (SSL) model to deal with the problem of incomplete data and multi-vehicle data fusion. A mathematical derivation of the ‘international roughness index’ (IRI) using in-car vibrations is established. Furthermore, given the multi-vehicle scenario, a self-training model is designed to iteratively estimate IRIs in a roadway network. Both the confidences of the vehicle parameters and IRI estimation are considered in the algorithm to improve its reliability and robustness. A full-car simulation model is constructed to verify the effectiveness of the proposed model. The results show that the overall relative error is less than 10% for 50 road sections in the network, which is a significant improvement compared to traditional multi-vehicle average models. The errors of the SSL model are found to be significantly dependent on the iteration order. Based on the proposed model, the coupled impact of the sampling rate and vehicle quantity on the model’s accuracy is further discussed. The proposed approach provides new insights into large-scale pavement roughness measurements.
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='images/3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Rough pavements cause ride discomfort and energy inefficiency for road vehicles. Existing methods to address these problems are time-consuming and not adaptive to changing driving conditions on rough pavements. With the development of sensor and communication technologies, crowdsourced road and dynamic traffic information become available for enhancing driving performance, particularly addressing the discomfort and inefficiency issues by controlling driving speeds. This study proposes a speed control framework on rough pavements, envisioning the operation of autonomous vehicles based on the crowdsourced data. We suggest the concept of ‘maximum comfortable speed’ for representing the vertical ride comfort of oncoming roads. A deep reinforcement learning (DRL) algorithm is designed to learn comfortable and energy-efficient speed control strategies. The DRL-based speed control model is trained using real-world rough pavement data in Shanghai, China. The experimental results show that the vertical ride comfort, energy efficiency, and computation efficiency increase by 8.22%, 24.37%, and 94.38%, respectively, compared to an optimization-based speed control model. The results indicate that the proposed framework is effective for real-time speed controls of autonomous vehicles on rough pavements.
</div>
</div>

# 📝 Publications 
📃 Papers
- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">International Journal of Pavement Engineering 2024</div></div></div></div>
Fast calibration for vibration-based pavement roughness measurement based on model updating of vehicle dynamics, Difei Wu, **Chenglong Liu**, Bohao Qin, Sheng Zhong, Xiaoming Zhang, Yuchuan Du
- Advances in automatic identification of road subsurface distress using ground penetrating radar: State of the art and future trends, **Chenglong Liu**, Yuchuan Du, Guanghua Yue, Yishun Li, Difei Wu, Feng Li, **Automation in Construction**
- Fine-Grained Pavement Performance Prediction Based on Causal-Temporal Graph Convolution Networks, Wenyuan Cai, Andi Song, Yuchuan Du, **Chenglong Liu**, Difei Wu, Feng Li, **IEEE transactions on intelligent transportation systems**
- Differences evaluation of pavement roughness distribution based on light detection and ranging data, Qian Gao,Lei Fan,Siyu Wei,Yishun Li,Yuchuan Du, **Chenglong Liu**, **Applied Sciences**
- 基于LiDAR三维数据的路面平整度横向分布差异特性评估方法, **刘成龙**, 魏斯瑀, 高倩, 吴荻非, 曹静, 杜豫川, **交通运输研究**
- Modeling automatic pavement crack object detection and pixel-level segmentation, Yuchuan Du, Shan Zhong, Hongyuan Fang, Niannian Wang, **Chenglong Liu**, Difei Wu, Yan Sun, Mang Xiang, **Automation in Construction**
- Enabling Edge Computing Ability in View-Independent Vehicle Model Recognition, **Chenglong Liu**, Ziyuan Pu, Yishun Li, Ying Jiang, Yinhai Wang, Yuchuan Du, **IJTST**
- 探地雷达多特征融合的城市空洞自动识别方法研究, 杜豫川, 岳光华, **刘成龙**, 李峰, 蔡文才, **中国公路学报**

# 📚 Patents
- 一种基于三维纹理特征的沥青路面混合料级配预估方法(ZL202110211816.9)
- 一种基于实时需求的无人驾驶公交派车方法(ZL202010755992.4)
- 一种基于关联规则分析的道路深层病害预警方法(ZL202110215728.6)
- A method for leakage detection of underground corridor based on static infrared thermal image processing(GB2569751)
- Comfort-based self-driving planning method(US 11,447,150 B2)
- Method of controlling automated driving speed based on comfort level(WO/2018/122586)

# 🏆 Honors and Awards
🏅 Honors
- *2023* 中国交通协会科技进步奖
- *2023* 中国交通协会科技进步奖
- *2023* 《中国公路学报》年度优秀论文
- *2023* 联合国报告证明
- *2023* 高PCSI、高被引、高下载论文

🎏 Foundations
- *2023* 上海市科技创新行动计划-道路基础设施多维体征的数字化感知与评价方法研究
- *2022* 国家重点研发计划-智能网联道路交通系统的能源自洽技术
- *2023* 同济大学交叉学科项目-知识-数据协同驱动的精细化道路养护策略生成方法
- *2023* 国家自然基金青年项目-众筹数据驱动的城市路网平整度感知方法研究

# 💼 Societies
- *2023*, 上海青年科技启明星
- *2022*, 中国公路学会青年托举人才
- *2019*, 上海市超级博士后
- 联合国亚太经济社会组织咨询专家（Transport Division）
- 世界交通运输大会数字化运维技术委员会 秘术委员
- 上海市公路学会公路养护与运行专委会委员

