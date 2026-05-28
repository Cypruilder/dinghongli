---
permalink: /
author_profile: true
stylesheets:
  - assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---
<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>

Hi! I’m Hongli Ding, I am currently an undergraduate at North China University of Technology, majoring in Digital Media Technology, ranking 1/53 with a GPA of 94.68/100.

News
---------------
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.01</em></span> My first paper got published! 🎉 Keep up the hard work 💪.</li>
    <li><span class="news-date"><em>2025.12</em></span> Won the National First Prize in the National Undergraduate Physics Experiment Competition 🏆🔬</li>
    <li><span class="news-date"><em>2025.10</em></span> Won the National Second Prize in the National College Student Digital Media Technology Works and Creativity Competition 🥈🎥</li>
    <li><span class="news-date"><em>2025.08</em></span> Started my research journey 🔬✨</li>
    <li><span class="news-date"><em>2025.07</em></span> Won the National First Prize in the Visual Art Design Competition of the Lanqiao Cup 🎨🏅</li>
    <li><span class="news-date"><em>2025.04</em></span> Crammed scattered Stata & Python for mathematical modeling, wrote data visualization analysis reports 📊💻</li>
    <li><span class="news-date"><em>2025.03</em></span> Scored 563 on CET-6 📝✅</li>
    <li><span class="news-date"><em>2024.12</em></span> Won the First Prize in the National Undergraduate Mathematics Competition (Preliminary) 🧮🥇</li>
    <li><span class="news-date"><em>2024.10</em></span> Received the National Endeavor Scholarship 🎓💰</li>
    <li><span class="news-date"><em>2024.09</em></span> Scored 616 on CET-4 – so happy! 😊📖</li>
    <li><span class="news-date"><em>2024.05</em></span> Won the National Third Prize in the National English Competition for College Students 🏅😊</li>
    <li><span class="news-date"><em>2023.09</em></span> Began my studies at North China University of Technology 🏫</li>
  </ul>
</div>

Education
---------------
<div class="experience-container">
  <div class="experience-card">
    <div style="display: flex; align-items: center;">
      <div style="width: 80px; margin-right: 20px; flex-shrink: 0;">
        <img src="images/ncut_logo.jpg" alt="NCUT logo" style="width: 100%; border-radius: 8px;">
      </div>
      <div class="experience-info">
        <strong>North China University of Technology</strong><br>
        <em>2023 – Present (expected 2027)</em><br>
        Bachelor of Engineering in Digital Media Technology<br>
        <strong>GPA: 94.68/100</strong> · Rank: <strong>1/53</strong><br>
        <strong>Selected top grades:</strong> Calculus (100), University Physics (99), Computer Graphics (99), Discrete Math (99), Game Engine (99), Linear Algebra (98), Database (98), Data Structure (97).<br>
        <strong>Skills:</strong> Python, C++, ClaudeCode, Trae, MySQL, Milvus, Photoshop, Premiere, Unity, Blender.
      </div>
    </div>
  </div>
</div>


Publications
--------------

<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution · † corresponding author)

<div id="core-publications" class="publication-view" data-publication-view="core">

<div class="publication-card" data-category="all"> 
  <div>
    <div class="pub-title"><strong>ScreenWeaver: Collaborative Long-form Screenwriting Based on Dual-axis Recursive Planning</strong></div>
    <div class="pub-authors"><em>Hongli Ding</em><sup>*</sup></div>
    <div class="pub-status">Submitted to a CCF-N class conference (under review)</div>
    <div class="pub-description">Proposed a multi-agent screenplay writing system with dual‑axis recursive task decomposition, inspired by professional screenwriting workflows.</div>
    <div class="pub-links"><b><i style="color:#83a1c7;">Under review &nbsp;</i></b> <a href=""><em>[preprint]</em></a></div>
  </div>
</div>

<div class="publication-card" data-category="all"> 
  <div>
    <div class="pub-title"><strong>MHTA-RAG: Mental Disorder Knowledge Support System Based on Markdown Heading Tree Augmented Retrieval‑Augmented Generation</strong></div>
    <div class="pub-authors"><em>Hongli Ding</em><sup>*</sup></div>
    <div class="pub-status">Accepted by <em>2025 6th International Symposium on Artificial Intelligence for Medical Sciences (ISAIMS 2025)</em> (EI)</div>
    <div class="pub-description">Introduced a hierarchical BM25 + RAPTOR hybrid retrieval strategy to improve domain‑specific RAG performance for mental health literature.</div>
    <div class="pub-links"><b><i style="color:#83a1c7;">Published &nbsp;</i></b> <a href="https://doi.org/10.1145/3777577.3777603" target="_blank"><em>[DOI:10.1145/3777577.3777603]</em></a> <a href=""><em>[paper]</em></a></div>
  </div>
</div>

</div>

<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">Under review</span>
      <span class="pub-list-title">ScreenWeaver: Collaborative Long-form Screenwriting Based on Dual-axis Recursive Planning</span><br>
      <span class="pub-list-authors"><strong>Hongli Ding</strong></span>
      <span class="pub-list-links"><a href="">[preprint]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Published</span>
      <span class="pub-list-title">MHTA-RAG: Mental Disorder Knowledge Support System Based on Markdown Heading Tree Augmented Retrieval‑Augmented Generation</span><br>
      <span class="pub-list-authors"><strong>Hongli Ding</strong></span>
      <span class="pub-list-links">
  <a href="https://dl.acm.org/doi/10.1145/3777577.3777603" target="_blank">[paper]</a>
</span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<!-- 注意：原本的 pub_media_rotator.js 已经不需要，可以删除该行，但保留也无害 -->

<style>
.publication-card {
  background: var(--card-bg, #fff);
  border-radius: 16px;
  padding: 20px;
  margin: 20px 0;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  transition: transform 0.2s;
}
.publication-card:hover {
  transform: translateY(-3px);
}
@media (max-width: 768px) {
  .publication-card > div {
    flex-direction: column;
  }
}
</style>



Projects
--------
<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/ruoyi_demo.png" alt="RuoYi-Community-Starter demo" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>RuoYi-Community-Starter</strong><br>
      <i style="font-size: 13px;">
        <strong>Hongli Ding</strong>
      </i><br>
      A community information management system built on the RuoYi framework, featuring a four‑level data model: community → grid → building → resident. Extended with a community data visualization dashboard, an AI assistant, and custom SVG icon integration. Comes with detailed documentation – ideal for learning RuoYi development.
      <br> 
      <b><i style="color:#83a1c7;">Spring Boot · Vue 3 · MyBatis · Redis · JWT · ECharts &nbsp;</i></b> 
      <a href="https://github.com/Cypruilder/RuoYi-Community-Starter"><em>[GitHub]</em></a> 
    </div>
  </div> 
</div>


<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/roguelike_tutorial.png" alt="RogueLike Card Game Tutorials" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>RogueLike Card Game Tutorials</strong><br>
      <i style="font-size: 13px;">
        <strong>Hongli Ding</strong>
      </i><br>
      A comprehensive tutorial series for anyone who wants to learn how to build a RogueLike card game like Slay the Spire, based on the principles of TCG Engine. Covers card system design, combat mechanics, map systems, UI design, and more. Packaged software and tutorials are included – ideal for beginners looking to understand the architecture of a mature card game.
      <br> 
      <b><i style="color:#83a1c7;">Unity · TCG Engine · Tutorial &nbsp;</i></b> 
      <a href="https://github.com/Cypruilder/RogueLike-CardGame-Tutorials"><em>[GitHub]</em></a> 
    </div>
  </div> 
</div>

<style>
.project-card {
  background: var(--card-bg, #fff);
  border-radius: 16px;
  padding: 20px;
  margin: 20px 0;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  transition: transform 0.2s;
}
.project-card:hover {
  transform: translateY(-3px);
}
@media (max-width: 768px) {
  .project-card > div {
    flex-direction: column;
  }
}
</style>




Awards
--------
**Honors & Scholarships**  
- **National Endeavor Scholarship** (2023–2025, two consecutive years)  
- **University Top-three Student** 
- **College-level Excellent League Member** 
- **2-Star Running Master** 

**National-Level Competition Awards**  
- **First Prize** – National Undergraduate Physics Experiment Competition  
- **First Prize** – National College Mathematics Competition (Non-Math Category A)  
- **Second Prize** – National College Student Digital Media Technology Works and Creativity Competition  
- **Third Prize** – Lanqiao Cup (Visual Art Design)  
- **Third Prize** – National English Competition for College Students  

**Provincial-Level Competition Awards (Beijing)**  
- **Second Prize** – Lanqiao Cup (Software Individual Competition)  
- **Third Prize** – SFLEP·Word Master Cup  
- **Third Prize** – China College Computer Design Competition  


Services 
--------
- **Class President** (Digital Media Tech Class 23-2): led 10+ class meetings, twice awarded “University Advanced Class Collective”.  
- **Student Union Officer** (Sports Department): organized university‑wide football and volleyball leagues.  
- **Volunteer**: 273.5 hours accumulated, participating in community services and large‑scale events.





