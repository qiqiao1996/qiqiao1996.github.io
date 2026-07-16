---
permalink: /
title: ""
excerpt: "Qi Qiao — wireless communications, edge intelligence, integrated sensing, communication and computing, and 6G."
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
h1[id] { scroll-margin-top: 92px; }
.page__content { color: var(--academic-ink); }
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
.news-list { display: grid; gap: 0; }
.news-item { display: grid; grid-template-columns: 5.5rem minmax(0,1fr); gap: 1rem; padding: 1rem 0; border-bottom: 1px solid var(--academic-line); }
.news-item time { font-size: .85rem; font-weight: 800; color: var(--academic-cyan); }
.news-item p { margin: .15rem 0 0; line-height: 1.65; }
.news-tag { display: inline-block; padding: .15rem .42rem; border-radius: 5px; font-size: .68rem; font-weight: 800; letter-spacing: .06em; text-transform: uppercase; color: var(--academic-blue); background: var(--academic-wash); }
@media (max-width: 560px) { .news-item { grid-template-columns: 1fr; gap: .35rem; } }
</style>

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
