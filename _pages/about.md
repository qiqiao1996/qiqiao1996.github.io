---
permalink: /
title: ""
excerpt: "Qi Qiao 鈥?wireless communications, edge intelligence, integrated sensing, communication and computing, and 6G."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
:root {
  --academic-ink: #172331;
  --academic-muted: #647180;
  --academic-blue: #0b5c78;
  --academic-cyan: #16877f;
  --academic-wash: #f3f8f7;
  --academic-line: #dce9e8;
}
html { scroll-behavior: smooth; }
[id] { scroll-margin-top: 92px; }
.page__content { color: var(--academic-ink); line-height: 1.75; }
.content-view[hidden] { display: none !important; }
.profile-heading { margin: .25rem 0 1rem; padding-bottom: .85rem; border-bottom: 1px solid var(--academic-line); font-size: clamp(1.65rem, 3.5vw, 2.2rem); color: var(--academic-ink); }
.profile-heading span { display: block; margin-top: .3rem; font-size: .78rem; font-weight: 700; letter-spacing: .13em; text-transform: uppercase; color: var(--academic-blue); }
.intro-copy { font-size: 1.03rem; line-height: 1.9; }
.research-label { margin: 1.7rem 0 .7rem; font-size: .84rem; font-weight: 800; letter-spacing: .08em; text-transform: uppercase; color: var(--academic-blue); }
.research-tags { display: flex; flex-wrap: wrap; gap: .55rem; margin: 0 0 1.55rem; }
.research-tags span { padding: .48rem .75rem; border: 1px solid var(--academic-line); border-radius: 999px; color: #28404e; background: var(--academic-wash); }
.profile-links { display: flex; flex-wrap: wrap; gap: .65rem; margin: 1.25rem 0 3rem; }
.profile-links a { padding: .62rem .85rem; border-radius: 8px; color: #fff; background: var(--academic-blue); font-weight: 700; text-decoration: none; }
.profile-links a:hover { color: #fff; background: #073d52; }
.news-heading { margin: 0 0 1.2rem; padding-bottom: .75rem; border-bottom: 1px solid var(--academic-line); font-size: 1.55rem; color: var(--academic-ink); }
.news-heading span { margin-left: .45rem; font-size: .75rem; font-weight: 700; letter-spacing: .12em; text-transform: uppercase; color: var(--academic-blue); }
.news-list { display: grid; }
.news-item { display: grid; grid-template-columns: 5.5rem minmax(0,1fr); gap: 1rem; padding: 1rem 0; border-bottom: 1px solid var(--academic-line); }
.news-item time { font-size: .85rem; font-weight: 800; color: var(--academic-cyan); }
.news-item p { margin: .15rem 0 0; line-height: 1.65; }
.news-tag { display: inline-block; padding: .15rem .42rem; border-radius: 5px; font-size: .68rem; font-weight: 800; letter-spacing: .06em; text-transform: uppercase; color: var(--academic-blue); background: var(--academic-wash); }

.section-hero { position: relative; overflow: hidden; margin: 0 0 2rem; padding: 2rem 2.2rem; border: 1px solid #d7e8e7; border-radius: 20px; background: linear-gradient(135deg,#f7fbfa 0%,#eaf5f4 100%); box-shadow: 0 14px 36px rgba(7,61,82,.08); }
.section-hero:after { content: ""; position: absolute; right: -55px; top: -75px; width: 190px; height: 190px; border-radius: 50%; background: rgba(18,126,139,.09); }
.section-kicker { display: inline-block; margin-bottom: .65rem; color: #0b7180; font-size: .74rem; font-weight: 800; letter-spacing: .15em; text-transform: uppercase; }
.section-hero h1 { margin: 0; color: #073d52; font-size: clamp(1.7rem,4vw,2.45rem); line-height: 1.2; }
.section-hero p { max-width: 670px; margin: .75rem 0 0; color: #57707b; }
.content-view h2 { margin: 2.5rem 0 1rem; padding-bottom: .65rem; border-bottom: 1px solid #dce9e8; color: #073d52; }
.content-view h3 { margin-top: 1.45rem; color: #087884; }
.content-view a { color: #087884; text-decoration-color: rgba(8,120,132,.34); text-underline-offset: 2px; }

[data-view="research"] > ol,
[data-view="patents"] > ol { padding: 0; list-style: none; counter-reset: academic-item; }
[data-view="research"] > ol > li,
[data-view="patents"] > ol > li { position: relative; margin: 0 0 .85rem; padding: 1.08rem 1.15rem 1.08rem 3.8rem; border: 1px solid #e0ecea; border-radius: 14px; background: #fff; box-shadow: 0 7px 22px rgba(12,65,77,.05); counter-increment: academic-item; }
[data-view="research"] > ol > li:before,
[data-view="patents"] > ol > li:before { content: counter(academic-item,decimal-leading-zero); position: absolute; left: 1.05rem; top: 1.08rem; display: grid; place-items: center; width: 2rem; height: 2rem; border-radius: 10px; background: #e6f4f2; color: #087884; font-size: .72rem; font-weight: 800; }

.course-title { margin: 0 0 .9rem !important; padding: 0 !important; border: 0 !important; color: #073d52; font-size: 1.25rem; }
.course-list { display: grid; grid-template-columns: repeat(3,minmax(0,1fr)); gap: .8rem; margin: 0 0 2rem; padding: 0; list-style: none; }
.course-list li { position: relative; margin: 0; padding: 1.15rem 1rem 1.1rem 2.65rem; border: 1px solid #deebe9; border-radius: 14px; background: #fff; box-shadow: 0 8px 22px rgba(12,65,77,.05); }
.course-list li:before { content: "\2713"; position: absolute; left: 1rem; top: 1.08rem; display: grid; place-items: center; width: 1.25rem; height: 1.25rem; border-radius: 50%; background: #dff2ef; color: #087884; font-weight: 900; }
.recruitment-box { margin: 1.4rem 0; padding: 1.35rem 1.45rem; border-left: 4px solid #118697; border-radius: 0 14px 14px 0; background: #f2f8f7; }
.recruitment-box strong { display: block; margin-bottom: .35rem; color: #073d52; font-size: 1.08rem; }
[data-view="teaching"] > ol { padding-left: 1.25rem; }
[data-view="teaching"] > ol > li { margin: .7rem 0; padding: .75rem .85rem; border-bottom: 1px solid #edf3f2; }
.contact-strip { display: flex; flex-wrap: wrap; align-items: center; gap: .55rem .8rem; margin-top: 1.7rem; padding: 1rem 1.1rem; border: 1px solid #d8e8e6; border-radius: 14px; background: #fff; }
.contact-strip a { padding: .32rem .65rem; border-radius: 999px; background: #e8f4f2; text-decoration: none; }

[data-view="publications"] .profile-links { display: block; margin: 0 0 1rem; padding: .85rem 1rem; border: 1px solid #e0ecea; border-radius: 12px; background: #fff; color: #637980; font-size: .92rem; }
.author-note { margin: 0 0 2rem; color: #6e8389; font-size: .86rem; }
.author-note strong,.self-author { color: #063f55; font-weight: 800; }
.corresponding-author:after { content: "*"; position: relative; top: -.42em; margin-left: .08em; color: #c34d32; font-size: .72em; font-weight: 900; }
.corresponding-symbol { color: #c34d32; font-weight: 900; }
[data-view="publications"] h2 { border-bottom: 2px solid #dceae8; font-size: 1.42rem; }
[data-view="publications"] h3 { display: inline-block; margin: 1.45rem 0 .75rem; padding: .28rem .72rem; border-radius: 999px; background: #e8f4f2; color: #087884; font-size: .9rem; letter-spacing: .04em; }
[data-view="publications"] > ul { margin: 0; padding: 0; list-style: none; }
[data-view="publications"] > ul > li { position: relative; margin: 0 0 .8rem; padding: 1.05rem 1.1rem 1.05rem 1.3rem; border: 1px solid #e0ecea; border-radius: 14px; background: #fff; box-shadow: 0 7px 22px rgba(12,65,77,.045); }
[data-view="publications"] > ul > li:before { content: ""; position: absolute; left: 0; top: .8rem; bottom: .8rem; width: 3px; border-radius: 3px; background: linear-gradient(#0f8794,#69b5ae); }

[data-view="awards"] > ol { position: relative; margin-left: .45rem; padding: 0 0 0 1.8rem; list-style: none; }
[data-view="awards"] > ol:before { content: ""; position: absolute; left: .35rem; top: .5rem; bottom: .6rem; width: 2px; background: linear-gradient(#0f8794,#d9eae8); }
[data-view="awards"] > ol > li { position: relative; margin: 0 0 .8rem; padding: .95rem 1.1rem; border: 1px solid #e0ecea; border-radius: 13px; background: #fff; box-shadow: 0 7px 20px rgba(12,65,77,.045); }
[data-view="awards"] > ol > li:before { content: ""; position: absolute; left: -1.9rem; top: 1.35rem; width: .72rem; height: .72rem; border: 3px solid #fff; border-radius: 50%; background: #0f8794; box-shadow: 0 0 0 1px #91c9c8; }
[data-view="awards"] > ol > li:last-child { border-color: #bcdedb; background: linear-gradient(135deg,#f5fbfa,#ecf7f5); font-weight: 700; color: #073d52; }

@layer academic-fallback {
  body { margin: 0; color: #172331; background: #fff; font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","PingFang SC","Microsoft YaHei",Arial,sans-serif; }
  .masthead { position: sticky; top: 0; z-index: 30; border-bottom: 1px solid #e4eceb; background: rgba(255,255,255,.97); }
  .masthead__inner-wrap { max-width: 1280px; margin: 0 auto; padding: .65rem 1rem; }
  .greedy-nav { display: flex; align-items: center; min-height: 3rem; background: transparent; }
  .greedy-nav .site-title { margin-right: auto; color: #073d52; font-weight: 800; text-decoration: none; }
  .greedy-nav .visible-links { display: flex; align-items: center; gap: .1rem; margin: 0; padding: 0; list-style: none; }
  .greedy-nav .visible-links li { margin: 0; list-style: none; }
  .greedy-nav .visible-links a { display: block; padding: .62rem .68rem; color: #29434f; font-size: .92rem; font-weight: 650; text-decoration: none; }
  .greedy-nav .visible-links a:hover,.greedy-nav .visible-links a.is-active { color: #087884; }
  .greedy-nav__toggle,.greedy-nav .hidden-links { display: none; }
  .author__avatar img { display: block; width: 140px; height: 140px; border-radius: 50%; object-fit: cover; }
  .author__urls { padding-left: 0; list-style: none; }
}

@media (max-width: 760px) {
  .section-hero { padding: 1.5rem; border-radius: 16px; }
  .course-list { grid-template-columns: 1fr; }
  .news-item { grid-template-columns: 1fr; gap: .35rem; }
  .greedy-nav .visible-links { max-width: 100%; overflow-x: auto; white-space: nowrap; }
}
</style>

<span id="about-me" aria-hidden="true"></span>
<div class="content-view" data-view="home" id="home" markdown="1">
<h1 class="profile-heading" id="about">个人简介 <span>About Me</span></h1>

<p class="intro-copy">齐俏，讲师，硕士生导师，浙江大学信息与通信工程博士。研究方向为无线通信，包括 6G 关键技术、新一代边缘智能网络、通感算一体化及人工智能与无线通信交叉等前沿领域的研究。目前，主持国家自然科学基金青年项目（C 类）及浙江省自然科学基金青年项目各 1 项，以第一/通讯作者在 <em>IEEE TWC</em>、<em>IEEE TSP</em>、<em>IEEE TCOM</em>、<em>SCIS</em> 等期刊发表 SCI 论文十余篇，在 <em>IEEE GLOBECOM</em> 等旗舰会议发表 EI 论文多篇，Google Scholar 总引用已<strong>超过 1000 次</strong>；第一发明人获授权国家发明专利多项，出版学术专著 1 部。担任无线通信领域多个权威期刊和重要国际会议的审稿人，并担任 <em>IEEE GLOBECOM</em>、WCSP、<em>IEEE WCNC</em> 等国际会议的技术委员会成员。</p>

<p class="research-label">Research Interests</p>
<div class="research-tags" aria-label="Research interests">
  <span>通感算一体化</span><span>边缘智能网络</span><span>6G 无线通信</span><span>卫星物联网</span><span>人工智能与无线通信</span>
</div>

<div class="profile-links">
  <a href="https://scholar.google.com/citations?user=pBR9kbMAAAAJ&amp;hl=en">Google Scholar</a>
  <a href="https://orcid.org/0000-0002-5120-6186">ORCID</a>
  <a href="mailto:qiqiao@hznu.edu.cn">Email</a>
</div>

<section id="news" aria-labelledby="news-title">
  <h1 class="news-heading" id="news-title">最新动态 <span>News</span></h1>
  <div class="news-list">
  {% for item in site.data.news %}
    <article class="news-item">
      <time datetime="{{ item.date }}">{{ item.date }}</time>
      <div><span class="news-tag">{{ item.category }}</span>{{ item.content | markdownify }}</div>
    </article>
  {% endfor %}
  </div>
</section>
</div>

<div class="content-view" data-view="research" id="research" hidden markdown="1">
<header class="section-hero">
  <span class="section-kicker">Research Portfolio</span>
  <h1>科研项目</h1>
  <p>围绕 6G 无线通信、通感算一体化、边缘智能网络与卫星物联网开展基础研究和关键技术攻关。</p>
</header>

1. 国家自然科学基金青年项目（C 类），任务驱动的通信-感知-计算融合网络资源优化方法研究，主持，在研，2026.01–2028.12。
2. 浙江省自然科学基金青年项目，基于多基站协作的 6G 通感算一体化多维资源管理技术研究，主持，在研，2025.01–2026.12。
3. 杭州师范大学启动项目，面向工业互联网的通信、感知和计算一体化技术研究，主持，在研，2023.08–2027.08。
4. 杭州师范大学培育项目，面向 6G 蜂窝物联网的通信、感知和计算一体化资源管理研究，主持，结题，2023.12–2024.12。
5. 浙江大学争创优秀博士学位论文资助项目，面向边缘智能网络的通信、感知和计算一体化技术研究，主持，结题，2022.06–2023.06。
6. 国家自然科学基金面上项目，面向人体动作质量的精确评估研究，参与，在研，2025.01–2028.12。
7. 国家自然科学基金区创重点项目，低轨卫星物联网的移动覆盖和巨址接入理论与关键技术，参与，结题，2022.01–2025.12。
8. 华为公司合作项目，有限位宽均衡算法研究，参与，结题，2020–2021。

<h2 class="section-heading" id="book">学术专著 <span>Book</span></h2>

1. X. Chen and Q. Qi, [*Convergence of Energy, Communication and Computation in B5G Cellular Internet of Things*](https://doi.org/10.1007/978-981-15-4140-7_1), Germany: Springer, 2020.
</div>

<div class="content-view" data-view="teaching" id="teaching" hidden markdown="1">
<header class="section-hero">
  <span class="section-kicker">Teaching & Openings</span>
  <h1>教学与招生</h1>
  <p>面向本科生与研究生开展课程教学、科研训练和学术指导。</p>
</header>

<h2 class="course-title">主讲课程</h2>

<ul class="course-list">
  <li>Web 服务器端开发</li>
  <li>数据库原理与应用</li>
  <li>计算机前沿与科创讲座</li>
</ul>

<div class="recruitment-box"><strong>欢迎加入课题组</strong><br>欢迎对无线通信、人工智能、边缘智能、通感算一体化和 6G 等方向有浓厚兴趣，且态度端正认真、理论功底扎实的同学加入课题组。每年招收 1 名硕士生，同时欢迎感兴趣的大二、大三学生提前参与科研训练。</div>

加入本课题组的学生可以享受待遇如下：

1. 坚持师生平等，尊重学生权利；
2. 论文署名客观公正，不用担心被抢一作；
3. 亲力亲为、手把手指导学生快速入门；
4. 不安排学生做与科研无关的杂事，为学生营造良好的科研环境；
5. 发放额外助研金，并设置丰富的劳务津贴、科研成果奖励。

<div class="contact-strip"><strong>申请联系</strong><a href="mailto:qiqiao@hznu.edu.cn">qiqiao@hznu.edu.cn</a><a href="mailto:qiqiaozju@163.com">qiqiaozju@163.com</a><span>请附个人简历与成绩单</span></div>
</div>

<div class="content-view" data-view="publications" id="publications" hidden markdown="1">
<header class="section-hero">
  <span class="section-kicker">Selected Publications</span>
  <h1>论文发表</h1>
  <p>研究成果涵盖 6G、通感算一体化、边缘智能网络、低轨卫星物联网与智能超表面。</p>
</header>

<p class="profile-links">完整论文与最新引用数据请访问 <a href="https://scholar.google.com/citations?user=pBR9kbMAAAAJ&amp;hl=en"><strong>Google Scholar</strong></a>；研究者身份记录见 <a href="https://orcid.org/0000-0002-5120-6186"><strong>ORCID</strong></a>。</p>

<p class="author-note"><strong>&#21152;&#31895;&#22995;&#21517;</strong>&#20026;&#26412;&#20154;&#65307;<span class="corresponding-symbol" aria-hidden="true">*</span> &#34920;&#31034;&#36890;&#35759;&#20316;&#32773;&#12290;</p>

## Journal Papers

### 2026

- <strong class="self-author">Q. Qi</strong>, Q. Chen, J. An, Z. Yang, X. Chen, C. Huang, and C. Yuen, “[Task-Oriented Wave Processing: Forging 6G Service Symbiosis with Stacked Intelligent Metasurfaces](https://scholar.google.com/scholar?q=%22Task-Oriented+Wave+Processing%3A+Forging+6G+Service+Symbiosis+with+Stacked+Intelligent+Metasurfaces%22),” *IEEE Communications Magazine*, accepted, 2026.
- Q. Chen, <strong class="self-author corresponding-author">Q. Qi</strong>, J. An, Z. Yang, X. Chen, C. Huang, and C. Yuen, “[Stacked Intelligent Metasurface Enhanced Integrated Communication and Computation](https://doi.org/10.1109/JIOT.2025.3649324),” *IEEE Internet of Things Journal*, vol. 13, no. 7, pp. 14442–14453, Apr. 2026. [DOI](https://doi.org/10.1109/JIOT.2025.3649324)
- M. Ying, X. Chen, <strong class="self-author">Q. Qi</strong>, and Z. Zhang, “[QoS-Driven Satellite Constellation Design for LEO Satellite Internet of Things](https://doi.org/10.1109/TWC.2025.3605220),” *IEEE Transactions on Wireless Communications*, vol. 25, pp. 3610–3625, 2026. [DOI](https://doi.org/10.1109/TWC.2025.3605220) / [arXiv](https://arxiv.org/abs/2509.00345)
- Q. Wang, X. Chen, <strong class="self-author">Q. Qi</strong>, Z. Wang, and Y. Liu, “[Integration of Navigation and Remote Sensing in LEO Satellite Constellations](https://doi.org/10.1109/TCOMM.2025.3634253),” *IEEE Transactions on Communications*, vol. 74, pp. 581–597, 2026. [DOI](https://doi.org/10.1109/TCOMM.2025.3634253) / [arXiv](https://arxiv.org/abs/2511.12430)
- W. Yao, X. Chen, Q. Wang, <strong class="self-author">Q. Qi</strong>, and M. Ying, “[Metasurface Antenna-Enabled LEO Satellite Constellation Communications: Design and Optimization](https://doi.org/10.1109/JIOT.2026.3660315),” *IEEE Internet of Things Journal*, 2026. [DOI](https://doi.org/10.1109/JIOT.2026.3660315)
- M. Ying, X. Chen, <strong class="self-author">Q. Qi</strong>, and Y. Xu, “[Modeling and Analysis for Multiple-Layer LEO Satellite Internet of Things Constellations](https://doi.org/10.1109/TWC.2026.3672191),” *IEEE Transactions on Wireless Communications*, 2026. [DOI](https://doi.org/10.1109/TWC.2026.3672191)

### 2025

- Q. Wang, X. Chen, <strong class="self-author">Q. Qi</strong>, M. Li, and W. Gerstacker, “[Multiple-Satellite Cooperative Information Communication and Location Sensing in LEO Satellite Constellations](https://doi.org/10.1109/TWC.2025.3530083),” *IEEE Transactions on Wireless Communications*, vol. 24, no. 4, pp. 3346–3361, Apr. 2025. [DOI](https://doi.org/10.1109/TWC.2025.3530083)

### 2024

- <strong class="self-author">Q. Qi</strong>, X. Chen, C. Zhong, C. Yuen, and Z. Zhang, “[Deep Learning-Based Design of Uplink Integrated Sensing and Communication](https://doi.org/10.1109/TWC.2024.3373797),” *IEEE Transactions on Wireless Communications*, vol. 23, no. 9, pp. 10639–10652, Sep. 2024. [DOI](https://doi.org/10.1109/TWC.2024.3373797) / [arXiv](https://arxiv.org/abs/2403.01480)
- <strong class="self-author">Q. Qi</strong>, X. Chen, and C. Yuen, “[Joint Offloading Selection and Resource Allocation for Integrated Localization and Computing in Edge-Intelligent Networks](https://doi.org/10.1109/TVT.2024.3374705),” *IEEE Transactions on Vehicular Technology*, vol. 73, no. 8, pp. 11427–11440, Aug. 2024. [DOI](https://doi.org/10.1109/TVT.2024.3374705)
- <strong>齐俏</strong>，陈晓明, “[面向边缘智能网络的通-感-算融合：架构、挑战和展望](https://scholar.google.com/scholar?q=%22%E9%9D%A2%E5%90%91%E8%BE%B9%E7%BC%98%E6%99%BA%E8%83%BD%E7%BD%91%E7%BB%9C%E7%9A%84%E9%80%9A-%E6%84%9F-%E7%AE%97%E8%9E%8D%E5%90%88%EF%BC%9A%E6%9E%B6%E6%9E%84%E3%80%81%E6%8C%91%E6%88%98%E5%92%8C%E5%B1%95%E6%9C%9B%22),” *移动通信*, vol. 48, no. 3, pp. 40–46, 2024.
- M. Ying, X. Chen, <strong class="self-author">Q. Qi</strong>, and W. Gerstacker, “[Deep Learning-Based Joint Channel Prediction and Multibeam Precoding for LEO Satellite Internet of Things](https://doi.org/10.1109/TWC.2024.3406952),” *IEEE Transactions on Wireless Communications*, vol. 23, no. 10, pp. 13946–13960, Oct. 2024. [DOI](https://doi.org/10.1109/TWC.2024.3406952) / [arXiv](https://arxiv.org/abs/2405.17150)

### 2023

- Q. Wang, X. Chen, and <strong class="self-author">Q. Qi</strong>, “[Task-Driven Robust Integration of Communication and Computation for Edge-Intelligent Networks](https://doi.org/10.1109/TCOMM.2022.3221403),” *IEEE Transactions on Communications*, vol. 71, no. 1, pp. 244–255, Jan. 2023. [DOI](https://doi.org/10.1109/TCOMM.2022.3221403)
- Q. Wang, X. Chen, and <strong class="self-author">Q. Qi</strong>, “[Energy-Efficient Design of Satellite-Terrestrial Computing in 6G Wireless Networks](https://doi.org/10.1109/TCOMM.2023.3334813),” *IEEE Transactions on Communications*, vol. 72, no. 3, pp. 1759–1772, Mar. 2024. [DOI](https://doi.org/10.1109/TCOMM.2023.3334813)

### 2022

- <strong class="self-author">Q. Qi</strong> and X. Chen, “[Robust Design of Federated Learning for Edge-Intelligent Networks](https://doi.org/10.1109/TCOMM.2022.3175921),” *IEEE Transactions on Communications*, vol. 70, no. 7, pp. 4469–4481, Jul. 2022. [DOI](https://doi.org/10.1109/TCOMM.2022.3175921) / [arXiv](https://arxiv.org/abs/2205.06955)
- <strong class="self-author">Q. Qi</strong>, X. Chen, A. Khalili, C. Zhong, Z. Zhang, and D. W. K. Ng, “[Integrating Sensing, Computing, and Communication in 6G Wireless Networks: Design and Optimization](https://doi.org/10.1109/TCOMM.2022.3190363),” *IEEE Transactions on Communications*, vol. 70, no. 9, pp. 6212–6227, Sep. 2022. [DOI](https://doi.org/10.1109/TCOMM.2022.3190363) / [arXiv](https://arxiv.org/abs/2207.03634)

### 2021

- <strong class="self-author">Q. Qi</strong>, X. Chen, C. Zhong, and Z. Zhang, “[Integrated Sensing, Computation and Communication in B5G Cellular Internet of Things](https://doi.org/10.1109/TWC.2020.3024787),” *IEEE Transactions on Wireless Communications*, vol. 20, no. 1, pp. 332–344, Jan. 2021. [DOI](https://doi.org/10.1109/TWC.2020.3024787) / [arXiv](https://arxiv.org/abs/2009.07545)

### 2020

- <strong class="self-author">Q. Qi</strong>, X. Chen, and D. W. K. Ng, “[Robust Beamforming for NOMA-Based Cellular Massive IoT With SWIPT](https://doi.org/10.1109/TSP.2019.2959246),” *IEEE Transactions on Signal Processing*, vol. 68, pp. 211–224, 2020. [DOI](https://doi.org/10.1109/TSP.2019.2959246)
- <strong class="self-author">Q. Qi</strong>, X. Chen, C. Zhong, and Z. Zhang, “[Physical Layer Security for Massive Access in Cellular Internet of Things](https://doi.org/10.1007/s11432-019-2650-4),” *Science China Information Sciences*, vol. 63, no. 2, pp. 121301:1–121301:12, Feb. 2020. [DOI](https://doi.org/10.1007/s11432-019-2650-4)
- <strong class="self-author">Q. Qi</strong>, X. Chen, C. Zhong, and Z. Zhang, “[Integration of Energy, Computation and Communication in 6G Cellular Internet of Things](https://doi.org/10.1109/LCOMM.2020.2982151),” *IEEE Communications Letters*, vol. 24, no. 6, pp. 1333–1337, Jun. 2020. [DOI](https://doi.org/10.1109/LCOMM.2020.2982151)
- R. Jia, X. Chen, <strong class="self-author">Q. Qi</strong>, and H. Lin, “[Massive Beam-Division Multiple Access for B5G Cellular Internet of Things](https://doi.org/10.1109/JIOT.2019.2958129),” *IEEE Internet of Things Journal*, vol. 7, no. 3, pp. 2386–2396, Mar. 2020. [DOI](https://doi.org/10.1109/JIOT.2019.2958129)

### 2019

- <strong class="self-author">Q. Qi</strong> and X. Chen, “[Wireless Powered Massive Access for Cellular Internet of Things With Imperfect SIC and Non-Linear EH](https://doi.org/10.1109/JIOT.2018.2878860),” *IEEE Internet of Things Journal*, vol. 6, no. 2, pp. 3110–3120, Apr. 2019. [DOI](https://doi.org/10.1109/JIOT.2018.2878860)
- <strong class="self-author">Q. Qi</strong>, X. Chen, L. Lei, C. Zhong, and Z. Zhang, “[Outage-Constrained Robust Design for Sustainable B5G Cellular Internet of Things](https://doi.org/10.1109/TWC.2019.2938962),” *IEEE Transactions on Wireless Communications*, vol. 18, no. 12, pp. 5780–5790, Dec. 2019. [DOI](https://doi.org/10.1109/TWC.2019.2938962)

## Conference Papers

### 2026

- Q. Chen, <strong class="self-author corresponding-author">Q. Qi</strong>, J. An, Z. Yang, M. Ying, X. Chen, and C. Huang, “[Joint Resource Allocation of SIM-Aided Integrated Communication and Computation in 6G Networks](https://scholar.google.com/scholar?q=%22Joint+Resource+Allocation+of+SIM-Aided+Integrated+Communication+and+Computation+in+6G+Networks%22),” in *Proc. IEEE WCNC*, Kuala Lumpur, Malaysia, 2026, pp. 1–6.

### 2025

- C. Jin, <strong class="self-author corresponding-author">Q. Qi</strong>, and J. Li, “[The Dual-Branch Cross-Alignment Design for Action Transfer Based on Feature Distribution Patterns](https://scholar.google.com/scholar?q=%22The+Dual-Branch+Cross-Alignment+Design+for+Action+Transfer+Based+on+Feature+Distribution+Patterns%22),” in *Proc. ICONIP*, Japan, 2025.
- M. Ying, X. Chen, <strong class="self-author">Q. Qi</strong>, and Z. Zhang, “[Constellation Design of LEO Satellite Internet of Things With QoS Provision](https://scholar.google.com/scholar?q=%22Constellation+Design+of+LEO+Satellite+Internet+of+Things+With+QoS+Provision%22),” in *Proc. IEEE VTC-Spring*, Oslo, Norway, 2025.

### 2024

- Q. Wang, X. Chen, and <strong class="self-author">Q. Qi</strong>, “[Joint Communication Beamforming and Sensing Waveform Design of LEO Satellite Constellations](https://doi.org/10.1109/WCNC57260.2024.10570761),” in *Proc. IEEE WCNC*, Dubai, United Arab Emirates, 2024. [DOI](https://doi.org/10.1109/WCNC57260.2024.10570761)

### 2023

- <strong class="self-author">Q. Qi</strong>, X. Chen, and C. Yuen, “[DL-Based Joint Waveform and Beamforming Design for Integrated Sensing and Communication](https://scholar.google.com/scholar?q=%22DL-based+Joint+Waveform+and+Beamforming+Design+for+Integrated+Sensing+and+Communication%22),” in *Proc. IEEE GLOBECOM*, Kuala Lumpur, Malaysia, 2023, pp. 1–6.
- Q. Wang, X. Chen, and <strong class="self-author">Q. Qi</strong>, “[Joint Offloading Selection, Beamforming Design and Resource Allocation for Satellite-Terrestrial Computing](https://scholar.google.com/scholar?q=%22Joint+Offloading+Selection%2C+Beamforming+Design+and+Resource+Allocation+for+Satellite-Terrestrial+Computing%22),” in *Proc. IEEE/CIC ICCC*, Dalian, China, 2023, pp. 1–6.

### 2022

- <strong class="self-author">Q. Qi</strong>, X. Chen, and C. Yuen, “[Joint Resource Allocation for Integrated Localization and Computing in Edge-Intelligent Networks](https://scholar.google.com/scholar?q=%22Joint+Resource+Allocation+for+Integrated+Localization+and+Computing+in+Edge-Intelligent+Networks%22),” in *Proc. IEEE GLOBECOM*, Rio de Janeiro, Brazil, 2022, pp. 800–806.
- Q. Wang, X. Chen, and <strong class="self-author">Q. Qi</strong>, “[Design of Delay-Optimal Robust Edge Computing in 6G Wireless Networks](https://scholar.google.com/scholar?q=%22Design+of+Delay-Optimal+Robust+Edge+Computing+in+6G+Wireless+Networks%22),” in *Proc. WCSP*, Nanjing, China, 2022, pp. 1–6.

### 2020

- <strong class="self-author">Q. Qi</strong>, X. Chen, C. Zhong, and Z. Zhang, “[Robust Integration of Computation and Communication in B5G Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Robust+Integration+of+Computation+and+Communication+in+B5G+Cellular+Internet+of+Things%22),” in *Proc. IEEE WCNC*, Seoul, Korea, 2020, pp. 1–6.
- J. Chu, X. Chen, <strong class="self-author">Q. Qi</strong>, C. Zhong, H. Lin, and Z. Zhang, “[On the Design of B5G MultiBeam LEO Satellite Internet of Things](https://scholar.google.com/scholar?q=%22On+the+Design+of+B5G+MultiBeam+LEO+Satellite+Internet+of+Things%22),” in *Proc. IEEE VTC2020-Spring*, Antwerp, Belgium, 2020, pp. 1–6.
- R. Fu, <strong class="self-author">Q. Qi</strong>, C. Zhong, X. Chen, and Z. Zhang, “[Block Error Rate Analysis of Short-Packet NOMA Communications With Imperfect SIC](https://scholar.google.com/scholar?q=%22Block+Error+Rate+Analysis+of+Short-Packet+NOMA+Communications+With+Imperfect+SIC%22),” in *Proc. IEEE/CIC ICCC*, Chongqing, China, 2020, pp. 1–6.

### 2019

- <strong class="self-author">Q. Qi</strong>, X. Chen, D. W. K. Ng, C. Zhong, and Z. Zhang, “[Robust Beamforming Design for SWIPT in Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Robust+Beamforming+Design+for+SWIPT+in+Cellular+Internet+of+Things%22),” in *Proc. IEEE/CIC ICCC*, Changchun, China, 2019, pp. 523–528.
- <strong class="self-author">Q. Qi</strong>, X. Chen, L. Lei, C. Zhong, and Z. Zhang, “[Robust Convergence of Energy and Computation for B5G Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Robust+Convergence+of+Energy+and+Computation+for+B5G+Cellular+Internet+of+Things%22),” in *Proc. IEEE GLOBECOM*, Hawaii, USA, 2019, pp. 1–6.
- R. Jia, X. Chen, and <strong class="self-author">Q. Qi</strong>, “[Low-Complexity Beamspace Massive Access for B5G Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Low-Complexity+Beamspace+Massive+Access+for+B5G+Cellular+Internet+of+Things%22),” in *Proc. WCSP*, Xi'an, China, 2019, pp. 1–6.
</div>

<div class="content-view" data-view="patents" id="patents" hidden markdown="1">
<header class="section-hero">
  <span class="section-kicker">Intellectual Property</span>
  <h1>发明专利</h1>
  <p>面向无线通信、边缘智能与通感算融合关键技术形成的国家发明专利成果。</p>
</header>

1. 齐俏，陈晓明：一种基于无线信息与能量协同传输的大规模接入方法。专利号：ZL201811564288.X。发明专利。授权时间：2020 年 3 月。
2. 齐俏，陈晓明：一种计算与通信融合的大规模接入方法。专利号：ZL201910603565.1。发明专利。授权时间：2021 年 1 月。
3. 齐俏，陈晓明：一种面向边缘智能网络的大规模接入方法。专利号：ZL202110049384.6。发明专利。授权时间：2021 年 11 月。
4. 齐俏，陈晓明，张朝阳：一种无线网络中感知、计算和通信的融合方法。专利号：ZL202111029984.2。发明专利。授权时间：2023 年 8 月。
5. 齐俏，陈晓明，张朝阳：一种定位、通信和计算的融合方法。专利号：ZL202210350401.4。发明专利。授权时间：2025 年 2 月。
6. 齐俏，陈晓明，张朝阳：一种基于深度学习的通信和感知融合方法。专利号：ZL202211249697.7。发明专利。授权时间：2025 年 8 月。
7. 齐俏，陈麒羽，钱正洪：一种堆叠智能超表面增强的通信和计算融合方法。专利号：ZL202511679882.3。发明专利。
8. 齐俏，陈麒羽，盛喆，王瑞钢，钱正洪：一种堆叠智能超表面辅助的多站协作通信和感知融合方法。专利号：ZL202610129697.5。发明专利。
9. 王琦，陈晓明，齐俏，张朝阳：一种计算和通信的融合方法。专利号：ZL202210035660.8。发明专利。授权时间：2023 年 12 月。
10. 王琦，陈晓明，齐俏，张朝阳：一种星地联合的边缘计算方法。专利号：ZL202210977079.8。发明专利。授权时间：2025 年 2 月。
11. 王琦，陈晓明，齐俏，张朝阳：一种基于多星协作的信息通信和位置感知一体化设计方法。专利号：202311059330.3。发明专利。
</div>

<div class="content-view" data-view="awards" id="awards" hidden markdown="1">
<header class="section-hero">
  <span class="section-kicker">Honors & Awards</span>
  <h1>奖励与荣誉</h1>
  <p>记录在学术研究、人才培养与综合表现方面获得的代表性荣誉。</p>
</header>

1. 2019 年 09 月，国家奖学金。
2. 2020 年 04 月，华为菁英奖学金。
3. 2020 年 06 月，浙江大学学生十大学术新成果奖。
4. 2020 年 09 月，浙江大学竺可桢奖学金。
5. 2020 年 12 月，浙江大学十佳大学生。
6. 2021 年 06 月，浙江大学优秀共产党员。
7. 2021 年 12 月，华为奖学金、大华奖学金。
8. 2022 年 12 月，国睿奖学金、ISEE 荣誉学子、IEEE 通信学会学生奖。
9. 2023 年 06 月，浙江省优秀毕业生。
10. 2023 年 06 月，浙江大学信电学院优秀博士学位论文。
11. 2023 年 12 月，浙江大学优秀博士学位论文。
12. 2023 年 12 月，中国电子教育学会优秀博士学位论文。
13. 2026 年 04 月，6G 星辰博士。
</div>

<script>
(function () {
  var panelIds = ['research','teaching','publications','patents','awards'];
  function setView() {
    var requested = (window.location.hash || '#home').slice(1);
    var panel = panelIds.indexOf(requested) >= 0 ? requested : 'home';
    document.querySelectorAll('.content-view').forEach(function (node) {
      node.hidden = node.getAttribute('data-view') !== panel;
    });
    document.querySelectorAll('.greedy-nav a').forEach(function (link) {
      var hash = new URL(link.href, window.location.href).hash.slice(1);
      var active = hash === requested || (panel === 'home' && requested === 'home' && hash === 'about');
      link.classList.toggle('is-active', active);
      if (active) link.setAttribute('aria-current', 'page'); else link.removeAttribute('aria-current');
    });
    window.requestAnimationFrame(function () {
      var target = document.getElementById(requested);
      if (target) target.scrollIntoView({behavior: 'smooth', block: 'start'});
      else window.scrollTo({top: 0, behavior: 'smooth'});
    });
  }
  document.addEventListener('click', function (event) {
    var link = event.target.closest('a[href]');
    if (!link) return;
    var url = new URL(link.href, window.location.href);
    if (url.origin === window.location.origin && url.pathname === '/' && url.hash) {
      event.preventDefault();
      history.pushState(null, '', url.hash);
      setView();
    }
  });
  window.addEventListener('popstate', setView);
  window.addEventListener('hashchange', setView);
  document.querySelectorAll('.author__avatar img').forEach(function (img) {
    function hideBroken() { if (!img.naturalWidth) img.closest('.author__avatar').hidden = true; }
    img.addEventListener('error', hideBroken);
    if (img.complete) hideBroken();
  });
  setView();
}());
</script>
