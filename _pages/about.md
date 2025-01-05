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

This is Donghui Dai, a final-year Ph.D. student in Computer Science at The Hong Kong Polytechnic University, supervised by [Dr. Lei Yang](https://www4.comp.polyu.edu.hk/~csyanglei/#/pages/profile/about). My research focuses on mobile and sensing technologies for wireless security, backscatter communication, cyber-physical systems, and wireless sensing. I design algorithms and construct systems that connect, perceive, and interact with the environment in innovative ways to enable more efficient, secure, robust, and capable mobile systems.

I have published several papers in top-tier avenues such as USENIX NSDI, ACM MobiCom, IEEE S&P, IEEE TMC, IEEE INFOCOM, and IEEE PerCom. I have received awards including the Best Demo Award Runner-up at ACM MobiCom. I am passionate about leveraging cutting-edge technologies to solve real-world challenges in wireless communication and security.


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
<span id="news"></span>
- *2024.12*: &nbsp;🎉🎉 Two papers have been accepted at *IEEE INFOCOM 2025*. One paper has been accepted at *IEEE PerCom 2025*.
- *2024.07*: &nbsp;🎉🎉 Our paper on physical side-channel communication systems has been accepted for publication in *IEEE TMC*.  
- *2024.04*: &nbsp;🎉🎉 We are delighted to share that our paper on RFID inventory systems has been accepted at *USENIX NSDI 2024*.  
- *2023.10*: &nbsp;🎉🎉 Thrilled to announce that our paper on NFC-to-Camera communication systems has been accepted at *ACM MobiCom 2023*.  
- *2023.05*: &nbsp;🎉🎉 Proud to share that our paper on inaudible voice attacks has been accepted at *IEEE S&P 2023*.  

# 📝 Publications 
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NSDI 2024</div><img src='../images/RFID-NDSI.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
### Regular Articles

1. **RFID+: Spatially Controllable Identification of UHF RFIDs via Controlled Magnetic Fields**

    **Donghui Dai**, Zhenlin An, Zheng Gong, Qingrui Pan, Lei Yang

    In Proc. of *USENIX NSDI*, Santa Clara, USA, April 16-18, 2024. <span style="color: red;">(CCF-A Conference)</span>

    [[**Paper**](https://www.usenix.org/conference/nsdi24/presentation/dai)] [[**Video**](https://youtu.be/9jnNp9LVpo4?si=64ipo-GN42B95u0Y)]

2. **MagCode: NFC-Enabled Barcodes for NFC-Disabled Smartphones**

    **Donghui Dai**, Zhenlin An, Qingrui Pan, Lei Yang

    In Proc. of *ACM MobiCom*, Madrid, Spain, Oct 2-6, 2023. <span style="color: red;">(CCF-A Conference)</span>

    [[**Paper**](https://dl.acm.org/doi/10.1145/3570361.3592528)] [[**Video**](https://donghui-dai.github.io/magcode/)]

3. **Inducing Wireless Chargers to Voice Out for Inaudible Command Attacks**

    **Donghui Dai**, Zhenlin An, Lei Yang

    In Proc. of *IEEE S&P (Oakland)*, San Francisco, USA, May 22-24, 2023. <span style="color: red;">(CCF-A Conference)</span>

    [[**Paper**](https://ieeexplore.ieee.org/document/10179363)] [[**Video**](https://anplus.github.io/magsound/)]

4. **Harnessing NFC to Generate Standard Optical Barcodes for NFC-Missing Smartphones**

    **Donghui Dai**, Zhenlin An, Qingrui Pan, Lei Yang

    In *IEEE Transactions on Mobile Computing*, 2024. <span style="color: red;">(CCF-A Journal)</span>

    [[**Paper**](https://ieeexplore.ieee.org/document/10577149)]

5. **Repurposing Optical Mice for Acoustic Eavesdropping**

    Zhimin Mei, **Donghui Dai**, Jingyu Tong, Zheng Gong, Lei Yang

    In Proc. of *IEEE INFOCOM*, London, UK, May 19-22, 2025. <span style="color: red;">(CCF-A Conference)</span>

6. **Deciphering Micro-Scale, Sub-Hertz Mechanical Vibrations in Industry 4.0: A Battery-Free Sensing Approach**

    Yuanhao Feng, **Donghui Dai**, Xiaopeng Zhao, Jingyu Tong, Zheng Gong, Lei Yang

    In Proc. of *IEEE PerCom*, Washington, D.C., USA, March 17-21, 2025. <span style="color: red;">(CCF-B Conference)</span>

7. **Mirror Never Lies: Unveiling Reflective Privacy Risks in Glass-laden Short Videos**

     Shen Wang, Xiaopeng Zhao, **Donghui Dai**, Lei Yang

    In Proc. of *ACM MobiCom*, Washington, D.C., USA, Oct 1-5, 2024. <span style="color: red;">(CCF-A Conference)</span>

8. **Enabling Cross-Medium Wireless Networks with Miniature Mechanical Antennas**

     Zheng Gong, Zhenlin An, **Donghui Dai**, Jingyu Tong, Shuijie Long, Lei Yang

    In Proc. of *ACM MobiCom*, Washington, D.C., USA, Oct 1-5, 2024. <span style="color: red;">(CCF-A Conference)</span>

9. **Commercial RFIDs as Reconfigurable Intelligent Surfaces**

     Jingyu Tong, Xiaopeng Zhao, Zhicheng Wang, **Donghui Dai**, Zhenlin An, Lei Yang

    In Proc. of *IEEE INFOCOM*, London, UK, May 19-22, 2025. <span style="color: red;">(CCF-A Conference)</span>

### Demo & Poster Articles

1. **Demo: Inducing Wireless Chargers to Voice Out**

     **Donghui Dai**, Zhenlin An, Lei Yang

    In Proc. of *ACM MobiCom*, Sydney, Australia, Oct 17-22, 2022 <span style="color: red;">(Best Demo Award Runner-up)</span>

2. **Demo: Constructing Smart Buildings with In-concrete Backscatter Networks**

     Zheng Gong, Zhenlin An, Jingyu Tong, **Donghui Dai**, Lei Yang

    In Proc. of *ACM MobiCom*, Sydney, Australia, Oct 17-22, 2022 <span style="color: red;">(Best Demo Award Runner-up)</span>

3. **Demo: MagCode: Bringing NFC Feature to All Smartphones**

     **Donghui Dai**, Zhenlin An, Qingrui Pan, Lei Yang

    In Proc. of *ACM MobiCom*, Madrid, Spain, Oct 02-06, 2023.

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!-- </div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2024.07* Nomination for Schmidt Science Fellows, The Hong Kong Polytechnic University 
- *2024.04* Student Travel Grant, USENIX NSDI 2024
- *2022.10* Two Best Demo Award Runner-up (2/20), ACM MobiCom 2022
- *2020 & 2019* National Encouragement Scholarships, Sun Yat-sen University
- *2020.07* Excellent Undergraduate Thesis Award (5/100), Sun Yat-sen University
- *2020.07* ZhuoYue Outstanding Scholarship, Sun Yat-sen University

# 📖 Educations
- *2020.09 - 2025.06 (expected)*, **The Hong Kong Polytechnic University**
    - Ph.D. Student in Computer Science
    - Chief Supervisor: Dr. [Lei Yang](https://www4.comp.polyu.edu.hk/~csyanglei/#/pages/profile/about)
- *2016.09 - 2020.07*, **Sun Yat-sen University**
    - B.E. degree in Electrical Engineering
    - Chief Supervisor: Dr. [Peiran Wu](https://ieeexplore.ieee.org/author/38236551200)

# 💬 Invited Talks
<span id="invited-talks"></span>
- *2024.08*, "Unlocking the Power of Electromagnetic Interference in Mobile Computing", Central South University, host: Prof. Qilong Feng
- *2023.12*, "NFC-Enabled Barcodes for NFC-Disabled Smartphones", Beihang University, host: Dr. Haohua Du
- *2023.07*, "Inducing Wireless Chargers to Voice Out for Inaudible Command Attacks", PolyU COMP Research Student Seminar, host: Dr. Lei Yang

# 🧑‍🏫 Teaching
- Teaching Assistant at HK PolyU, ENG2003 Information Technology Part II (Database)
    Fall 2021, Spring 2022, Spring 2023, Spring 2024
- Teaching Assistant at HK PolyU, COMP5322 Internet Computing and Applications
    Fall 2022, Fall 2023, Fall 2024

# 💻 Academic Services
- Reviewer for IEEE Internet of Things Journal, 2025
- Reviewer for EAI MobiQuitous, 2024
- Reviewer for IEEE ICC special issues, 2024
- Reviewer for EAI MobiQuitous, 2023

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->