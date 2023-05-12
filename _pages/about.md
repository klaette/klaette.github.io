---
permalink: /
title: ""
excerpt: ""
ref: publications
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

  秦浩翔，男，1997年生于山东聊城，分别于2020年及2023年获得了聊城大学软件工程专业的学士学位与硕士学位，目前正在华南理工大学软件学院攻读博士学位。读研期间师从韩玉艳与王玉亭，读博期间师从向毅。

 本人目前的研究兴趣包括智能制造、智能车间与智能计算、智能电网、迭代贪婪算法、多目标优化算法、进化算法和强化学习。 已在《IEEE Transactions on Emerging Topics in Computational Intelligence》、《Swarm and Evolutionary Computation》、《Expert Systems with Applications》、《knowledge-based systems》等多个国际著名期刊发表学术论文9篇，详情可查看我的<a href='https://scholar.google.com/citations?user=TaClukkAAAAJ'>谷歌学术</a>，或通过引用量徽章查看（<a href='https://scholar.google.com/citations?user=TaClukkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>)）。

# ✨ News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- 2023年6月 ~ 2027年9月, 华南理工大学软件学院，软件工程理论与方法，工学博士在读 
- 2020年6月 ~ 2023年9月, 聊城大学计算机学院，智能优化算法及其应用，工学硕士 
- 2016年6月 ~ 2020年9月, 聊城大学计算机学院，软件工程，工学学士

# 📝 发表论文 
  jpubs:
    - title:   "Intelligent Optimization Under Blocking Constraints: A Novel Iterated Greedy Algorithm for the Hybrid Flow-Shop Group Scheduling Problems"
      authors:
        - name: "Haoxiang Qin"  
        - name: "Yuyan Han*"  
        - name: "Yuting Wang*"
        - name: "Yiping Liu"
        - name: "Junqing Li"
        - name: "Quanke Pan"
      cauthor: 1
      journal: "knowledge-based systems"
      year:    "2022"
      volume:  "258"
      number:  "109962"
      page:    "1-24"
      doi:     "10.1016/j.knosys.2022.109962"
      impact:  "影响因子: 8.139, 中科院SCI一区"
      pdf:     "/pdf/DBHFSP_KBS.pdf"    
    
    - title:   "A collaborative iterative greedy algorithm for the scheduling of distributed heterogeneous hybrid flow shop with blocking constraints"
      authors:
        - name: "Haoxiang Qin"  
        - name: "Yuyan Han*"  
        - name: "Yiping Liu"
        - name: "Junqing Li"
        - name: "Quanke Pan"
        - name: "Xue Han"
      cauthor: 1
      journal: "Expert Systems with Applications"
      year:    "2022"
      volume:  "201"
      number:  "117256"
      page:    "1-15"
      doi:     "10.1016/j.eswa.2022.117256"
      impact:  "影响因子: 8.665, 中科院SCI一区"
      pdf:     "/pdf/DBHFSP_ESWA.pdf"
 
    - title:   "An improved iterated greedy algorithm for the energy-efficient blocking hybrid flow shop scheduling problem"
      authors:
        - name: "Haoxiang Qin"  
        - name: "Yuyan Han*"  
        - name: "Biao Zhang"
        - name: "Leilei Meng"
        - name: "Yiping Liu"
        - name: "Quanke Pan"
        - name: "Dunwei Gong"
      cauthor: 1
      journal: "Swarm and Evolutionary Computation"
      year:    "2021"
      volume:  "69"
      number:  "100992"
      page:    "1-18"
      doi:     "10.1016/j.swevo.2021.100992"
      impact:  "影响因子: 10.267, 中科院SCI一区"
      pdf:     "/pdf/BHFSP_SWEVO.pdf"
      
    - title:   "求解阻塞混合流水车间调度的双层变异迭代贪婪算法"
      authors:
        - name: "秦浩翔"  
        - name: "韩玉艳*"  
        - name: "陈庆达"
        - name: "李俊青"
        - name: "桑红燕"
      cauthor: 1
      journal: "控制与决策"
      year:    "2021"
      volume:  "37"
      number:  "9"
      page:    "2323-2332"
      doi:     "10.13195/j.kzyjc.2021.0607"
      impact:  "EI, 北大核心, 中文权威期刊"
      pdf:     "/pdf/BHFSP_CAD.pdf"

    - title: "An effective local search algorithm with restart strategy for energy-efficient distributed blocking flowshop scheduling problem with setup times"
      authors:
      - name: "Xue Han"
      - name: "Yuyan Han*"
      - name: "Biao Zhang"
      - name: "Haoxiang Qin"
      - name: "Junqing Li"
      - name: "Yiping Liu"
      - name: "Dunwei Gong"
      cauthor: 1
      journal: "Applied soft computing"
      year:    "2022"
      volume:  "129"
      number:  "109502"
      page:    "2323-2332"
      doi:     "10.1016/j.asoc.2022.109502"
      impact:  "影响因子: 8.263, 中科院SCI二区"
      pdf:     "/pdf/DBFSP_ASOC.pdf"
      
cpubs:
 
    - title:   "Adapting a reinforcement learning method for the distributed blocking hybrid flow shop scheduling problem"
      authors:  
        - name: "Haoxiang Qin"
        - name: "Yuting Wang*"
        - name: "Yuyan Han*"
        - name: "Qingda Chen"
        - name: "Junqing Li"      
      cauthor:
      conference: "The 5th Asian Conference on Artificial Intelligence Technology"
      year:    "2022"
      organization: "IEEE"
      abbr:    "ACAIT"

    - title:   "A quick and effective iterated greedy algorithm for energy-efficient hybrid flow shop scheduling problem with blocking constraint"
      authors:
        - name: "Haoxiang Qin"
        - name: "Yuyan Han*"
        - name: "Junqing Li"
        - name: "Hongyan Sang"
        - name: "Qingda Chen"
      cauthor:
      conference: "2021 11th International Conference on Information Science and Technology"
      year:    "2021"
      organization: "IEEE"
      abbr:    "ICIST"

    - title:   "An improved iterated greedy algorithm for the distributed flow shop scheduling problem with sequence-dependent setup times"
      authors:  
        - name: "Xue Han"
        - name: "Yuyan Han*"
        - name: "Yiping Liu"
        - name: "Quanke Pan"
        - name: "Haoxiang Qin"
        - name: "Junqing Li" 
      cauthor:
      conference: "2021 11th International Conference on Information Science and Technology"
      year:    "2021"
      organization: "IEEE"
      abbr:    "ICIST"

---

在<a href="https://scholar.google.com/citations?user=2eX_3XEAAAAJ&hl"><U>Google Scholar</U></a>浏览.<br />
从<a href="https://github.com/klaette"><U>GitHub</U></a>下载代码.<br />


### 期刊论文

('*'表示通信作者)

{% for pub in page.jpubs %}

<table cellpadding="6px">
  <tr valign="top">
    <td>[J{{forloop.index}}]</td>

    <td>
    <font color="#922B21"><b>{{pub.title}}</b></font><br />

    {% for author in pub.authors  %}
    {% if author.name == "Haoxiang Qin"%}
    <b>{{author.name}}</b>{% if pub.cauthor %}<b></b>{% endif %}{% else %}{%if author.name == "秦浩翔"%}<b>{{author.name}}</b>{% if pub.cauthor %}<b></b>{% endif %}{% else %}{{author.name}}{% endif %}{% endif %}{% if forloop.last %}{% else %},{% endif %}{% endfor %}<br />
    <i>{{pub.journal}}</i>,
    {% if pub.volume %}
    vol.{{pub.volume}}, no. {{pub.number}}, pp.{{pub.page}}, {{pub.year}}.
    {% else %}
    {% if pub.doi %}
    {{pub.year}} [Online].
    {% else %}
    {{pub.year}} [Accepted].
    {% endif %}
    {% endif %}
    <br />
    {% if pub.doi %}
    <a href="https://doi.org/{{pub.doi}}">[DOI: {{pub.doi}}]</a>
    {% endif %}
    {% if pub.pdf %}
    <a href="{{pub.pdf}}">[PDF]</a>
    {% endif %}
    {% if pub.code %}
    <a href="{{pub.code}}">[Code]</a>
    {% endif %}
    {% if pub.supplement %}
    <a href="{{pub.supplement}}">[Supplement]</a>
    {% endif %}
    {% if pub.code%}
    <br />
    {% else %}
    {% if pub.doi%}
    <br />
    {% else %}
    {% if pub.pdf%}
    <br />
    {% else %}
    {% if pub.supplement%}
    <br />
    {% endif %}
    {% endif %}
    {% endif %}
    {% endif %}
    {% if pub.impact %}
    <font color="#1F618D">{{pub.impact}}</font>
    {% endif %}
    </td>
  </tr>
</table>
{% endfor %}
      
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 💬 学术会议
- 
-  
- 

# 🎖️ 获奖情况
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- 

# 📚 项目经历 
- 
-  
-

# 👀 研究兴趣
- 
-  
- 

# 🏨 学术活动
- 


# 👥 合作成员
- 
-  

# 💻 工作实习
- 暂无
