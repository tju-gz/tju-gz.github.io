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

# 🙋‍♂️ About Me 关于我
Hi! I am Zheng Gong, an Associate Researcher at the [College of Intelligence and Computing](https://cic.tju.edu.cn/) at [Tianjin University](https://www.tju.edu.cn/). I am also a researcher at [TANKLab](https://tj.teacher.360eol.com/teacherBasic/preview?teacherId=12111)), led by [Prof. Keqiu Li](https://cic.tju.edu.cn/faculty/likeqiu/), IEEE Fellow. I received my Ph.D. degree in Computer Science at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/en/)🇭🇰 in February 2025, supervised by [Dr. Lei Yang](https://www4.comp.polyu.edu.hk/~csyanglei/#/pages/profile/about). My research spans the fields of low-power communication and sensing systems. 

I have published full research papers on all CCF A conferences in computer networks and the Internet of Things, including ACM SIGCOMM, ACM MobiCom, USENIX NSDI, and IEEE INFOCOM. My work has been awarded the Best Demo Award Runner-up at ACM MobiCom 2022. 

<!-- **<span style="color:red">I am currently on the job market and actively exploring opportunities for postdoctoral research or industry roles.</span>** -->


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

🎯**<span style="color:red">学生招募</span>**: 我一直招募优秀的博士生、硕士生和本科生和我合作🤝，研究方向为智慧物联网，属于EE和CS的交叉方向，十分鼓励EE背景和CS背景的学生踊跃申请。EE背景的学生需要掌握电磁场和电磁波、通信原理、数字/模拟电路设计、天线仿真和设计、复变函数等相关课程。CS背景的同学则需熟练使用Python、C++、Matlab等编程语言，同时对信号处理、深度学习、图像识别等技术有初步了解。对物联网、通信、感知有兴趣，或者参加过类似科研、竞赛项目是加分项🤔。有兴趣的同学请将简历和其他个人说明材料发送至gongzheng (at) tju.edu.cn。


# 🔥 News 新闻
<span id="news"></span>
- *2025.05*: &nbsp;🎉🎉 I have officially joined Tianjin University as an Associate Researcher.
- *2025.03*: &nbsp;🎉🎉 Our paper on edge-assisted robot swarm intelligence has been accepted for publication in *IEEE TMC*.  
- *2024.04*: &nbsp;🎉🎉 We are delighted to share that our paper on RFID inventory systems has been accepted at *USENIX NSDI 2024*.  
- *2024.02*: &nbsp;🎉🎉 Thrilled to announce that our paper on cross-medium communication systems has been accepted at *ACM MobiCom 2024*.  


# 📝 Publications 论文
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NSDI 2024</div><img src='../images/RFID-NDSI.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<sup>‡</sup>These authors contributed equally to this work. <sup>#</sup> Students advised by me.


### Conference Papers 会议论文
1. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">MobiCom 2024</span> Enabling Cross-Medium Wireless Networks with Miniature Mechanical Antennas

    **<u>Zheng Gong</u>**, Zhenlin An, Donghui Dai, Jingyu Tong, Shuijie Long, Lei Yang

    In Proc. of *ACM MobiCom*, Washington DC, USA, Nov 17-21, 2024. <span style="color: red;">(CCF-A Conference)</span>

    [[**Paper**](https://dl.acm.org/doi/10.1145/3636534.3649387)]

2. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">SIGCOMM 2022</span> Empowering Smart Buildings with Self-Sensing Concrete for  Structural Health Monitoring

    **<u>Zheng Gong</u><sup>‡</sup>**, Lubing Han<sup>‡</sup>, Zhenlin An, Lei Yang, Siqi Ding, Yu Xiang

    In Proc. of *ACM SIGCOMM*, Amsterdam, Netherlands, Aug 22-26, 2022. <span style="color: red;">(CCF-A Conference)</span>

    [[**Paper**](https://dl.acm.org/doi/abs/10.1145/3544216.3544270)] [[**Video**](https://www.bilibili.com/video/BV1Cg411S7R8/)]

3. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">MobiCom 2022 Demo</span> Constructing Smart Buildings with In-concrete Backscatter Networks

    **<u>Zheng Gong</u>**, Zhenlin An, Jingyu Tong, Donghui Dai, Lei Yang

    In Proc. of *ACM MobiCom*, Sydney, Australia, Oct 17-22, 2022. <span style="color: red;">(CCF-A Conference, **Best Demo Award Runner-Up**)</span>

    [[**Paper**](https://dl.acm.org/doi/10.1145/3495243.3558756)]

4. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">APWeb-WAIM 2020</span> Instance-Aware Evaluation of Sensitive Columns in Tabular Dataset

    **<u>Zheng Gong</u><sup>‡</sup>**, Kechun Zhao<sup>‡</sup>, Hui Li, Yingxue Wang

    In Proc. of *APWeb-WAIM*, Tianjin, China, Sep 18-20, 2020 <span style="color: red;">(CCF-C Conference)</span>

    [[**Paper**](https://dl.acm.org/doi/abs/10.1007/978-3-030-60259-8_2)]

5. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">ACM TURC 2023</span> Building the Future: Empowering Smart Structures with In-Concrete Backscatter Networks 

    **<u>Zheng Gong</u>**, Zhenlin An, Jingyu Tong, Donghui Dai, Lei Yang

    In Proc. of *ACM Turing Award Celebration Conference-China*, Wuhan, China, July 28-30, 2023

    [[**Paper**](https://dl.acm.org/doi/10.1145/3603165.3607370)]

6. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">NSDI 2024</span> RFID+: Spatially Controllable Identification of UHF RFIDs via Controlled Magnetic Fields

    Donghui Dai, Zhenlin An, **<u>Zheng Gong</u>**, Qingrui Pan, Lei Yang

   In Proc. of *USENIX NSDI*, Santa Clara, USA, Apr 16-18, 2024 <span style="color: red;">(CCF-A Conference)</span>

   [[**Paper**](https://www.usenix.org/conference/nsdi24/presentation/dai)]

7. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">INFOCOM 2025</span> Repurposing Optical Mice for Acoustic Eavesdropping

    Zhimin Mei, Donghui Dai, Jingyu Tong, **<u>Zheng Gong</u>**, Lei Yang

   In Proc. of *IEEE INFOCOM*, London, UK, May 19-22, 2025 <span style="color: red;">(CCF-A Conference)</span>
   
8. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">UbiComp 2025</span> Everytime Everywhere All at Once: Enhancing Temporal-Spatial Traceability of Optical Codes through Voltmarks

    Jingyu Tong, Donghui Dai, **<u>Zheng Gong</u>**, Lei Yang

   In Proc. of *ACM UbiComp/ISWC*, Espoo, Finland, Oct 14-17, 2025 <span style="color: red;">(CCF-A Conference)</span>
 
9. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">PerCom 2025</span> Deciphering Micro-Scale, Sub-Hertz Mechanical Vibrations in Industry 4.0: A Battery-Free Sensing Approach

    Yuanhao Feng, Donghui Dai, Xiaopeng Zhao, Jingyu Tong, **<u>Zheng Gong</u>**, Lei Yang

    In Proc. of *IEEE PerCom*, Washington, D.C., USA, March 17-21, 2025. <span style="color: red;">(CCF-B Conference)</span>

    [[**Paper**](https://www.computer.org/csdl/proceedings-article/percom/2025/355100a222/27fiz3K5BXa)]

10. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">CIKM 2021 Demo</span> SaDes: An Interactive System for Sensitivity-aware Desensitization towards Tabular Data

    Kechun Zhao, Hui Li, **<u>Zheng Gong</u>**, Jiangtao Cui

    In Proc. of *ACM CIKM*, Gold Coast, Queensland, Australia, Nov 1-5, 2021 <span style="color: red;">(CCF-B Conference)</span>

    [[**Paper**](https://dl.acm.org/doi/10.1145/3459637.3481975)]


### Journal Articles 期刊论文

1. <span style="display: inline-block; background-color: #172088; color: white; padding: 1.5px 6px; border-radius: 3px; font-weight: bold; line-height: 100%;">TMC 2025</span> Streamlining Data Transfer in Collaborative SLAM through Bandwidth-aware Map Distillation

     Rui Ge<sup>#</sup>, Huanghuang Liang, **<u>Zheng Gong</u>**, Chuang Hu, Xiaobo Zhou, Dazhao Cheng

    In *IEEE Transactions on Mobile Computing*, 2025 <span style="color: red;">(CCF-A Journal)</span>

    [[**Paper**](https://ieeexplore.ieee.org/abstract/document/10918818)]



<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!-- </div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards 荣誉奖项

- *2022.10* Best Demo Award Runner-up (2/20), ACM MobiCom 2022


<!-- # 📖 Educations -->
# 🎓 Educations 教育
- *2021.08 - 2025.02*, **The Hong Kong Polytechnic University** 
    - Rank #57 in [QS World University Rankings](https://www.topuniversities.com/universities/hong-kong-polytechnic-university) 2025
    - Ph.D. Student in Computing
    - Chief Supervisor: Dr. [Lei Yang](https://www4.comp.polyu.edu.hk/~csyanglei/#/pages/profile/about)
- *2018.09 - 2021.05*, **Xidian University**
    - M.E. degree in Cyberspace Security
    - Chief Supervisor: Dr. [Hui Li](https://lihuixidian.github.io/)
- *2016.09 - 2020.07*, **Xidian University**
    - B.E. degree in Computer Science and Technology
    - Chief Supervisor: Dr. [Hui Li](https://lihuixidian.github.io/)

# 💬 Invited Talks 演讲

<span id="invited-talks"></span>
- *2024.08*, "Omnimedium Communication via Piezoelectricity", Tianjin University, Host: Prof. Xiulong Liu


# 🧑‍🏫 Students 学生

- Mr. Rui Ge (Ph.D, Student from [ICSLab](http://icslab.whu.edu.cn/english.html), Wuhan University)

# 💻 Academic Services 学术服务

- Reviewer for IEEE Transactions on Mobile Computing (CCF A)
- Reviewer for IEEE Transactions on Parallel and Distributed Systems (CCF A)
- Reviewer for IEEE Transactions on Theoretical Computer Science (CCF A)
- Reviewer for EAI MobiQuitous, 2023-2024 (CCF C)

# 🎬 Demonstration Videos 演示视频

<body>
  <div style="display: flex; justify-content: space-between; flex-wrap: wrap; gap: 20px;">
    <!-- 第一个视频 -->
    <div style="flex: 1; min-width: 300px; max-width: 560px; margin: auto;">
      <div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 6px;">
        <iframe 
          src="//player.bilibili.com/player.html?bvid=BV1Cg411S7R8&page=1&autoplay=0" 
          scrolling="no" 
          border="0" 
          frameborder="no" 
          framespacing="0" 
          allowfullscreen="true" 
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
        </iframe>
      </div>
      <h3 style="
        text-align: center; 
        font-size: 16px; 
        margin-top: 10px; 
        background-color: #21477D; 
        color: white; 
        padding: 8px; 
        border-radius: 3px;
        font-family: '黑体', 'SimHei', sans-serif;
      ">
        墙内压电反向散射通信系统演示视频
      </h3>
    </div>
  </div>
</body>
