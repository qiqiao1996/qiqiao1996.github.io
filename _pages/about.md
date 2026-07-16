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

<style>
:root {
  --academic-ink: #132238;
  --academic-muted: #5c6b7a;
  --academic-blue: #0b5c78;
  --academic-blue-dark: #073d52;
  --academic-cyan: #21a6a1;
  --academic-wash: #f2f8f8;
  --academic-line: #dce9e8;
}
html { scroll-behavior: smooth; }
h1[id], h2[id], h3[id] { scroll-margin-top: 92px; }
.page__content { color: var(--academic-ink); }
.page__content a { color: var(--academic-blue); text-decoration-color: rgba(11, 92, 120, .35); }
.page__content a:hover { color: var(--academic-blue-dark); }
.academic-hero {
  position: relative;
  overflow: hidden;
  margin: 0 0 2.6rem;
  padding: clamp(2rem, 5vw, 4rem);
  border-radius: 26px;
  color: #fff;
  background:
    radial-gradient(circle at 88% 18%, rgba(83, 220, 207, .35), transparent 30%),
    radial-gradient(circle at 72% 88%, rgba(74, 146, 214, .28), transparent 34%),
    linear-gradient(135deg, #082f43 0%, #0b5c78 58%, #117f88 100%);
  box-shadow: 0 22px 55px rgba(7, 61, 82, .18);
}
.academic-hero:after {
  content: "";
  position: absolute;
  width: 260px;
  height: 260px;
  right: -105px;
  top: -115px;
  border: 1px solid rgba(255,255,255,.2);
  border-radius: 50%;
  box-shadow: 0 0 0 34px rgba(255,255,255,.04), 0 0 0 68px rgba(255,255,255,.03);
}
.hero-kicker { margin: 0 0 .65rem; font-size: .82rem; font-weight: 700; letter-spacing: .17em; text-transform: uppercase; color: #a7eee7; }
.academic-hero h1 { max-width: 760px; margin: 0; font-size: clamp(2.05rem, 5.2vw, 4rem); line-height: 1.04; letter-spacing: -.045em; color: #fff; }
.academic-hero h1:before { display: none; }
.hero-subtitle { max-width: 720px; margin: 1rem 0 .35rem; font-size: clamp(1.05rem, 2vw, 1.35rem); line-height: 1.55; color: rgba(255,255,255,.92); }
.hero-role { margin: 0 0 1.4rem; color: rgba(255,255,255,.72); }
.hero-links { display: flex; flex-wrap: wrap; gap: .7rem; }
.hero-links a { display: inline-flex; align-items: center; gap: .4rem; padding: .72rem 1rem; border: 1px solid rgba(255,255,255,.32); border-radius: 999px; color: #fff; font-weight: 700; text-decoration: none; background: rgba(255,255,255,.09); backdrop-filter: blur(8px); transition: transform .18s ease, background .18s ease; }
.hero-links a:hover { color: #fff; background: rgba(255,255,255,.18); transform: translateY(-2px); }
.hero-links a.primary { color: var(--academic-blue-dark); background: #fff; border-color: #fff; }
.metric-grid { display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: .8rem; margin: -1.25rem 1.25rem 2.8rem; position: relative; z-index: 2; }
.metric-card { padding: 1rem 1.1rem; border: 1px solid var(--academic-line); border-radius: 16px; background: rgba(255,255,255,.97); box-shadow: 0 10px 28px rgba(19,34,56,.08); }
.metric-value { display: block; font-size: 1.3rem; font-weight: 800; color: var(--academic-blue-dark); }
.metric-label { display: block; margin-top: .2rem; font-size: .76rem; line-height: 1.35; color: var(--academic-muted); }
.section-heading { display: flex; align-items: center; gap: .75rem; margin: 3rem 0 1.1rem; padding-bottom: .75rem; border-bottom: 1px solid var(--academic-line); font-size: clamp(1.35rem, 2.6vw, 1.8rem); color: var(--academic-ink); }
.section-heading:before { content: ""; display: block; width: 5px; height: 1.2em; border-radius: 99px; background: linear-gradient(var(--academic-cyan), var(--academic-blue)); }
.section-heading span { margin-left: auto; font-size: .72rem; font-weight: 700; letter-spacing: .12em; text-transform: uppercase; color: var(--academic-blue); }
.intro-copy { font-size: 1.02rem; line-height: 1.85; }
.research-focus { display: grid; grid-template-columns: repeat(2, minmax(0,1fr)); gap: .9rem; margin: 1.5rem 0 2.5rem; }
.focus-card { padding: 1.15rem 1.2rem; border: 1px solid var(--academic-line); border-radius: 16px; background: linear-gradient(145deg, #fff, var(--academic-wash)); }
.focus-card strong { display: block; margin-bottom: .3rem; color: var(--academic-blue-dark); }
.focus-card small { color: var(--academic-muted); line-height: 1.5; }
.recruitment-box { margin: 1.3rem 0 1.6rem; padding: 1.35rem 1.5rem; border: 1px solid #b9dfdc; border-left: 5px solid var(--academic-cyan); border-radius: 14px; background: var(--academic-wash); }
.recruitment-box strong { color: var(--academic-blue-dark); }
.contact-strip { display: flex; flex-wrap: wrap; gap: .65rem 1.2rem; margin: 1.2rem 0 2.4rem; padding: 1rem 1.2rem; border-radius: 12px; background: #132238; color: #fff; }
.contact-strip a { color: #b8f4ed; text-decoration: none; }
.page__content > ol { padding-left: 1.35rem; }
.page__content > ol li { margin-bottom: .65rem; padding-left: .25rem; }
#publications + h2 { margin-top: 1.75rem; }
#publications ~ h2 { margin-top: 2.2rem; padding: .75rem 1rem; border-radius: 12px; color: var(--academic-blue-dark); background: var(--academic-wash); }
.page__content h3 { margin-top: 1.7rem; color: var(--academic-blue); }
.page__content ul li { margin-bottom: .65rem; line-height: 1.65; }
@media (max-width: 760px) {
  .academic-hero { margin-left: -.6rem; margin-right: -.6rem; padding: 2rem 1.35rem; border-radius: 20px; }
  .metric-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); margin: -1rem 0 2.4rem; }
  .research-focus { grid-template-columns: 1fr; }
  .hero-links a { flex: 1 1 auto; justify-content: center; }
}
@media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } .hero-links a { transition: none; } }
</style>

<header class="academic-hero">
  <p class="hero-kicker">Qi Qiao · 齐俏</p>
  <h1>Wireless Intelligence<br>for 6G</h1>
  <p class="hero-subtitle">面向 6G 的通信、感知与计算融合研究</p>
  <p class="hero-role">讲师 · 硕士生导师 · 杭州师范大学</p>
  <div class="hero-links">
    <a class="primary" href="https://scholar.google.com/citations?user=pBR9kbMAAAAJ&amp;hl=en">Google Scholar</a>
    <a href="https://orcid.org/0000-0002-5120-6186">ORCID</a>
    <a href="mailto:qiqiao@hznu.edu.cn">Email</a>
  </div>
</header>

<div class="metric-grid" aria-label="Academic highlights">
  <div class="metric-card"><span class="metric-value">近 1000</span><span class="metric-label">Google Scholar 引用</span></div>
  <div class="metric-card"><span class="metric-value">十余篇</span><span class="metric-label">第一 / 通讯作者 SCI 论文</span></div>
  <div class="metric-card"><span class="metric-value">2 项</span><span class="metric-label">国家级与省级青年项目主持</span></div>
  <div class="metric-card"><span class="metric-value">1 部</span><span class="metric-label">Springer 学术专著</span></div>
</div>

<h1 class="section-heading" id="about">个人简介 <span>About Me</span></h1>

<p class="intro-copy">齐俏，讲师，硕士生导师，浙江大学信息与通信工程博士。研究方向为无线通信，包括 6G 关键技术、新一代边缘智能网络、通感算一体化及人工智能与无线通信交叉等前沿领域的研究。目前，主持国家自然科学基金青年项目（C 类）及浙江省自然科学基金青年项目各 1 项，以第一/通讯作者在 <em>IEEE TWC</em>、<em>IEEE TSP</em>、<em>IEEE TCOM</em>、<em>SCIS</em> 等期刊发表 SCI 论文十余篇，在 <em>IEEE GLOBECOM</em> 等旗舰会议发表 EI 论文多篇，总引用近 1000 次；第一发明人获授权国家发明专利多项，出版学术专著 1 部。担任无线通信领域多个权威期刊和重要国际会议的审稿人，并担任 <em>IEEE GLOBECOM</em>、WCSP、<em>IEEE WCNC</em> 等国际会议的技术委员会成员。</p>

<div class="research-focus">
  <div class="focus-card"><strong>通感算一体化</strong><small>Integrated sensing, communication &amp; computing</small></div>
  <div class="focus-card"><strong>边缘智能网络</strong><small>Edge intelligence &amp; resource optimization</small></div>
  <div class="focus-card"><strong>6G 无线通信</strong><small>6G wireless systems &amp; intelligent metasurfaces</small></div>
  <div class="focus-card"><strong>卫星物联网</strong><small>LEO satellite IoT &amp; satellite–terrestrial networks</small></div>
</div>

<h1 class="section-heading" id="teaching">教学与招生 <span>Teaching &amp; Openings</span></h1>

主讲课程包括 Web 服务器端开发、数据库原理与应用、计算机前沿与科创讲座等。

<div class="recruitment-box"><strong>欢迎加入课题组</strong><br>欢迎对无线通信、人工智能、边缘智能、通感算一体化和 6G 等方向有浓厚兴趣，且态度端正认真、理论功底扎实的同学加入课题组。每年招收 1 名硕士生，同时欢迎感兴趣的大二、大三学生提前参与科研训练。</div>

加入本课题组的学生可以享受待遇如下：

1. 坚持师生平等，尊重学生权利；
2. 论文署名客观公正，不用担心被抢一作；
3. 亲力亲为、手把手指导学生快速入门；
4. 不安排学生做与科研无关的杂事，为学生营造良好的科研环境；
5. 发放额外助研金，并设置丰富的劳务津贴、科研成果奖励。

<div class="contact-strip"><strong>申请联系</strong><a href="mailto:qiqiao@hznu.edu.cn">qiqiao@hznu.edu.cn</a><a href="mailto:qiqiaozju@163.com">qiqiaozju@163.com</a><span>请附个人简历与成绩单</span></div>

<h1 class="section-heading" id="research">科研项目 <span>Research</span></h1>

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

<h1 class="section-heading" id="publications">论文发表 <span>Publications</span></h1>

<p>完整论文与最新引用数据请访问 <a href="https://scholar.google.com/citations?user=pBR9kbMAAAAJ&amp;hl=en"><strong>Google Scholar</strong></a>；研究者身份记录见 <a href="https://orcid.org/0000-0002-5120-6186"><strong>ORCID</strong></a>。</p>

## Journal Papers

### 2026

- Q. Qi, Q. Chen, J. An, Z. Yang, X. Chen, C. Huang, and C. Yuen, “[Task-Oriented Wave Processing: Forging 6G Service Symbiosis with Stacked Intelligent Metasurfaces](https://scholar.google.com/scholar?q=%22Task-Oriented+Wave+Processing%3A+Forging+6G+Service+Symbiosis+with+Stacked+Intelligent+Metasurfaces%22),” *IEEE Communications Magazine*, accepted, 2026.
- Q. Chen, Q. Qi, J. An, Z. Yang, X. Chen, C. Huang, and C. Yuen, “[Stacked Intelligent Metasurface Enhanced Integrated Communication and Computation](https://doi.org/10.1109/JIOT.2025.3649324),” *IEEE Internet of Things Journal*, vol. 13, no. 7, pp. 14442–14453, Apr. 2026. [DOI](https://doi.org/10.1109/JIOT.2025.3649324)
- M. Ying, X. Chen, Q. Qi, and Z. Zhang, “[QoS-Driven Satellite Constellation Design for LEO Satellite Internet of Things](https://doi.org/10.1109/TWC.2025.3605220),” *IEEE Transactions on Wireless Communications*, vol. 25, pp. 3610–3625, 2026. [DOI](https://doi.org/10.1109/TWC.2025.3605220) / [arXiv](https://arxiv.org/abs/2509.00345)
- Q. Wang, X. Chen, Q. Qi, Z. Wang, and Y. Liu, “[Integration of Navigation and Remote Sensing in LEO Satellite Constellations](https://doi.org/10.1109/TCOMM.2025.3634253),” *IEEE Transactions on Communications*, vol. 74, pp. 581–597, 2026. [DOI](https://doi.org/10.1109/TCOMM.2025.3634253) / [arXiv](https://arxiv.org/abs/2511.12430)
- W. Yao, X. Chen, Q. Wang, Q. Qi, and M. Ying, “[Metasurface Antenna-Enabled LEO Satellite Constellation Communications: Design and Optimization](https://doi.org/10.1109/JIOT.2026.3660315),” *IEEE Internet of Things Journal*, 2026. [DOI](https://doi.org/10.1109/JIOT.2026.3660315)
- M. Ying, X. Chen, Q. Qi, and Y. Xu, “[Modeling and Analysis for Multiple-Layer LEO Satellite Internet of Things Constellations](https://doi.org/10.1109/TWC.2026.3672191),” *IEEE Transactions on Wireless Communications*, 2026. [DOI](https://doi.org/10.1109/TWC.2026.3672191)

### 2025

- Q. Wang, X. Chen, Q. Qi, M. Li, and W. Gerstacker, “[Multiple-Satellite Cooperative Information Communication and Location Sensing in LEO Satellite Constellations](https://doi.org/10.1109/TWC.2025.3530083),” *IEEE Transactions on Wireless Communications*, vol. 24, no. 4, pp. 3346–3361, Apr. 2025. [DOI](https://doi.org/10.1109/TWC.2025.3530083)

### 2024

- Q. Qi, X. Chen, C. Zhong, C. Yuen, and Z. Zhang, “[Deep Learning-Based Design of Uplink Integrated Sensing and Communication](https://doi.org/10.1109/TWC.2024.3373797),” *IEEE Transactions on Wireless Communications*, vol. 23, no. 9, pp. 10639–10652, Sep. 2024. [DOI](https://doi.org/10.1109/TWC.2024.3373797) / [arXiv](https://arxiv.org/abs/2403.01480)
- Q. Qi, X. Chen, and C. Yuen, “[Joint Offloading Selection and Resource Allocation for Integrated Localization and Computing in Edge-Intelligent Networks](https://doi.org/10.1109/TVT.2024.3374705),” *IEEE Transactions on Vehicular Technology*, vol. 73, no. 8, pp. 11427–11440, Aug. 2024. [DOI](https://doi.org/10.1109/TVT.2024.3374705)
- 齐俏，陈晓明, “[面向边缘智能网络的通-感-算融合：架构、挑战和展望](https://scholar.google.com/scholar?q=%22%E9%9D%A2%E5%90%91%E8%BE%B9%E7%BC%98%E6%99%BA%E8%83%BD%E7%BD%91%E7%BB%9C%E7%9A%84%E9%80%9A-%E6%84%9F-%E7%AE%97%E8%9E%8D%E5%90%88%EF%BC%9A%E6%9E%B6%E6%9E%84%E3%80%81%E6%8C%91%E6%88%98%E5%92%8C%E5%B1%95%E6%9C%9B%22),” *移动通信*, vol. 48, no. 3, pp. 40–46, 2024.
- M. Ying, X. Chen, Q. Qi, and W. Gerstacker, “[Deep Learning-Based Joint Channel Prediction and Multibeam Precoding for LEO Satellite Internet of Things](https://doi.org/10.1109/TWC.2024.3406952),” *IEEE Transactions on Wireless Communications*, vol. 23, no. 10, pp. 13946–13960, Oct. 2024. [DOI](https://doi.org/10.1109/TWC.2024.3406952) / [arXiv](https://arxiv.org/abs/2405.17150)

### 2023

- Q. Wang, X. Chen, and Q. Qi, “[Task-Driven Robust Integration of Communication and Computation for Edge-Intelligent Networks](https://doi.org/10.1109/TCOMM.2022.3221403),” *IEEE Transactions on Communications*, vol. 71, no. 1, pp. 244–255, Jan. 2023. [DOI](https://doi.org/10.1109/TCOMM.2022.3221403)
- Q. Wang, X. Chen, and Q. Qi, “[Energy-Efficient Design of Satellite-Terrestrial Computing in 6G Wireless Networks](https://doi.org/10.1109/TCOMM.2023.3334813),” *IEEE Transactions on Communications*, vol. 72, no. 3, pp. 1759–1772, Mar. 2024. [DOI](https://doi.org/10.1109/TCOMM.2023.3334813)

### 2022

- Q. Qi and X. Chen, “[Robust Design of Federated Learning for Edge-Intelligent Networks](https://doi.org/10.1109/TCOMM.2022.3175921),” *IEEE Transactions on Communications*, vol. 70, no. 7, pp. 4469–4481, Jul. 2022. [DOI](https://doi.org/10.1109/TCOMM.2022.3175921) / [arXiv](https://arxiv.org/abs/2205.06955)
- Q. Qi, X. Chen, A. Khalili, C. Zhong, Z. Zhang, and D. W. K. Ng, “[Integrating Sensing, Computing, and Communication in 6G Wireless Networks: Design and Optimization](https://doi.org/10.1109/TCOMM.2022.3190363),” *IEEE Transactions on Communications*, vol. 70, no. 9, pp. 6212–6227, Sep. 2022. [DOI](https://doi.org/10.1109/TCOMM.2022.3190363) / [arXiv](https://arxiv.org/abs/2207.03634)

### 2021

- Q. Qi, X. Chen, C. Zhong, and Z. Zhang, “[Integrated Sensing, Computation and Communication in B5G Cellular Internet of Things](https://doi.org/10.1109/TWC.2020.3024787),” *IEEE Transactions on Wireless Communications*, vol. 20, no. 1, pp. 332–344, Jan. 2021. [DOI](https://doi.org/10.1109/TWC.2020.3024787) / [arXiv](https://arxiv.org/abs/2009.07545)

### 2020

- Q. Qi, X. Chen, and D. W. K. Ng, “[Robust Beamforming for NOMA-Based Cellular Massive IoT With SWIPT](https://doi.org/10.1109/TSP.2019.2959246),” *IEEE Transactions on Signal Processing*, vol. 68, pp. 211–224, 2020. [DOI](https://doi.org/10.1109/TSP.2019.2959246)
- Q. Qi, X. Chen, C. Zhong, and Z. Zhang, “[Physical Layer Security for Massive Access in Cellular Internet of Things](https://doi.org/10.1007/s11432-019-2650-4),” *Science China Information Sciences*, vol. 63, no. 2, pp. 121301:1–121301:12, Feb. 2020. [DOI](https://doi.org/10.1007/s11432-019-2650-4)
- Q. Qi, X. Chen, C. Zhong, and Z. Zhang, “[Integration of Energy, Computation and Communication in 6G Cellular Internet of Things](https://doi.org/10.1109/LCOMM.2020.2982151),” *IEEE Communications Letters*, vol. 24, no. 6, pp. 1333–1337, Jun. 2020. [DOI](https://doi.org/10.1109/LCOMM.2020.2982151)
- R. Jia, X. Chen, Q. Qi, and H. Lin, “[Massive Beam-Division Multiple Access for B5G Cellular Internet of Things](https://doi.org/10.1109/JIOT.2019.2958129),” *IEEE Internet of Things Journal*, vol. 7, no. 3, pp. 2386–2396, Mar. 2020. [DOI](https://doi.org/10.1109/JIOT.2019.2958129)

### 2019

- Q. Qi and X. Chen, “[Wireless Powered Massive Access for Cellular Internet of Things With Imperfect SIC and Non-Linear EH](https://doi.org/10.1109/JIOT.2018.2878860),” *IEEE Internet of Things Journal*, vol. 6, no. 2, pp. 3110–3120, Apr. 2019. [DOI](https://doi.org/10.1109/JIOT.2018.2878860)
- Q. Qi, X. Chen, L. Lei, C. Zhong, and Z. Zhang, “[Outage-Constrained Robust Design for Sustainable B5G Cellular Internet of Things](https://doi.org/10.1109/TWC.2019.2938962),” *IEEE Transactions on Wireless Communications*, vol. 18, no. 12, pp. 5780–5790, Dec. 2019. [DOI](https://doi.org/10.1109/TWC.2019.2938962)

## Conference Papers

### 2026

- Q. Chen, Q. Qi, J. An, Z. Yang, M. Ying, X. Chen, and C. Huang, “[Joint Resource Allocation of SIM-Aided Integrated Communication and Computation in 6G Networks](https://scholar.google.com/scholar?q=%22Joint+Resource+Allocation+of+SIM-Aided+Integrated+Communication+and+Computation+in+6G+Networks%22),” in *Proc. IEEE WCNC*, Kuala Lumpur, Malaysia, 2026, pp. 1–6.

### 2025

- C. Jin, Q. Qi, and J. Li, “[The Dual-Branch Cross-Alignment Design for Action Transfer Based on Feature Distribution Patterns](https://scholar.google.com/scholar?q=%22The+Dual-Branch+Cross-Alignment+Design+for+Action+Transfer+Based+on+Feature+Distribution+Patterns%22),” in *Proc. ICONIP*, Japan, 2025.
- M. Ying, X. Chen, Q. Qi, and Z. Zhang, “[Constellation Design of LEO Satellite Internet of Things With QoS Provision](https://scholar.google.com/scholar?q=%22Constellation+Design+of+LEO+Satellite+Internet+of+Things+With+QoS+Provision%22),” in *Proc. IEEE VTC-Spring*, Oslo, Norway, 2025.

### 2024

- Q. Wang, X. Chen, and Q. Qi, “[Joint Communication Beamforming and Sensing Waveform Design of LEO Satellite Constellations](https://doi.org/10.1109/WCNC57260.2024.10570761),” in *Proc. IEEE WCNC*, Dubai, United Arab Emirates, 2024. [DOI](https://doi.org/10.1109/WCNC57260.2024.10570761)

### 2023

- Q. Qi, X. Chen, and C. Yuen, “[DL-Based Joint Waveform and Beamforming Design for Integrated Sensing and Communication](https://scholar.google.com/scholar?q=%22DL-based+Joint+Waveform+and+Beamforming+Design+for+Integrated+Sensing+and+Communication%22),” in *Proc. IEEE GLOBECOM*, Kuala Lumpur, Malaysia, 2023, pp. 1–6.
- Q. Wang, X. Chen, and Q. Qi, “[Joint Offloading Selection, Beamforming Design and Resource Allocation for Satellite-Terrestrial Computing](https://scholar.google.com/scholar?q=%22Joint+Offloading+Selection%2C+Beamforming+Design+and+Resource+Allocation+for+Satellite-Terrestrial+Computing%22),” in *Proc. IEEE/CIC ICCC*, Dalian, China, 2023, pp. 1–6.

### 2022

- Q. Qi, X. Chen, and C. Yuen, “[Joint Resource Allocation for Integrated Localization and Computing in Edge-Intelligent Networks](https://scholar.google.com/scholar?q=%22Joint+Resource+Allocation+for+Integrated+Localization+and+Computing+in+Edge-Intelligent+Networks%22),” in *Proc. IEEE GLOBECOM*, Rio de Janeiro, Brazil, 2022, pp. 800–806.
- Q. Wang, X. Chen, and Q. Qi, “[Design of Delay-Optimal Robust Edge Computing in 6G Wireless Networks](https://scholar.google.com/scholar?q=%22Design+of+Delay-Optimal+Robust+Edge+Computing+in+6G+Wireless+Networks%22),” in *Proc. WCSP*, Nanjing, China, 2022, pp. 1–6.

### 2020

- Q. Qi, X. Chen, C. Zhong, and Z. Zhang, “[Robust Integration of Computation and Communication in B5G Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Robust+Integration+of+Computation+and+Communication+in+B5G+Cellular+Internet+of+Things%22),” in *Proc. IEEE WCNC*, Seoul, Korea, 2020, pp. 1–6.
- J. Chu, X. Chen, Q. Qi, C. Zhong, H. Lin, and Z. Zhang, “[On the Design of B5G MultiBeam LEO Satellite Internet of Things](https://scholar.google.com/scholar?q=%22On+the+Design+of+B5G+MultiBeam+LEO+Satellite+Internet+of+Things%22),” in *Proc. IEEE VTC2020-Spring*, Antwerp, Belgium, 2020, pp. 1–6.
- R. Fu, Q. Qi, C. Zhong, X. Chen, and Z. Zhang, “[Block Error Rate Analysis of Short-Packet NOMA Communications With Imperfect SIC](https://scholar.google.com/scholar?q=%22Block+Error+Rate+Analysis+of+Short-Packet+NOMA+Communications+With+Imperfect+SIC%22),” in *Proc. IEEE/CIC ICCC*, Chongqing, China, 2020, pp. 1–6.

### 2019

- Q. Qi, X. Chen, D. W. K. Ng, C. Zhong, and Z. Zhang, “[Robust Beamforming Design for SWIPT in Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Robust+Beamforming+Design+for+SWIPT+in+Cellular+Internet+of+Things%22),” in *Proc. IEEE/CIC ICCC*, Changchun, China, 2019, pp. 523–528.
- Q. Qi, X. Chen, L. Lei, C. Zhong, and Z. Zhang, “[Robust Convergence of Energy and Computation for B5G Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Robust+Convergence+of+Energy+and+Computation+for+B5G+Cellular+Internet+of+Things%22),” in *Proc. IEEE GLOBECOM*, Hawaii, USA, 2019, pp. 1–6.
- R. Jia, X. Chen, and Q. Qi, “[Low-Complexity Beamspace Massive Access for B5G Cellular Internet of Things](https://scholar.google.com/scholar?q=%22Low-Complexity+Beamspace+Massive+Access+for+B5G+Cellular+Internet+of+Things%22),” in *Proc. WCSP*, Xi'an, China, 2019, pp. 1–6.

<h1 class="section-heading" id="patents">发明专利 <span>Patents</span></h1>

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

<h1 class="section-heading" id="awards">奖励与荣誉 <span>Honors &amp; Awards</span></h1>

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
