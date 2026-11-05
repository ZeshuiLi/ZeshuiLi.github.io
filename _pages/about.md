---
layout: single
permalink: /
title: "Zeshui Li"
excerpt: "Zeshui Li — Wireless Sensing and Haptics"
author_profile: false
toc: false
share: false
related: false
comments: false
redirect_from:
  - /about/
  - /about.html
---

<style>
/* 覆盖当前首页的 Academicpages 默认布局 */
body {
  background: #faf9f6;
  margin-bottom: 0 !important;
}

.masthead,
.page__footer {
  display: none !important;
}

#main {
  width: 100%;
  max-width: none;
  margin: 0;
  padding: 0;
}

#main > .sidebar {
  display: none;
}

#main .page,
#main .page__inner-wrap {
  float: none;
  width: 100%;
  margin: 0;
  padding: 0;
}

#main .page__inner-wrap > header,
#main .page__meta,
#main .page__share,
#main .page__related,
#main .page__comments,
#main .pagination {
  display: none;
}

#main .page__content {
  margin: 0;
  padding: 0;
}

/* 页面基础样式 */
#academic-home {
  --ink: #18364a;
  --text: #30343a;
  --muted: #626972;
  --line: #d9dde0;

  box-sizing: border-box;
  max-width: 1080px;
  margin: 0 auto;
  padding: 0 40px;
  color: var(--text);
  font-family:
    -apple-system, BlinkMacSystemFont,
    "Segoe UI", Arial, sans-serif;
  font-size: 16px;
  line-height: 1.75;
}

#academic-home *,
#academic-home *::before,
#academic-home *::after {
  box-sizing: border-box;
}

#academic-home h1,
#academic-home h2,
#academic-home h3 {
  margin: 0;
  padding: 0;
  border: 0;
  color: var(--ink);
  font-family:
    Georgia, "Times New Roman",
    "Songti SC", SimSun, serif;
  font-weight: 600;
  line-height: 1.35;
}

#academic-home h2 {
  font-size: 28px;
}

#academic-home p {
  margin: 0;
  line-height: inherit;
}

#academic-home a {
  color: var(--ink);
  text-decoration: underline;
  text-decoration-color: #a8b4bc;
  text-decoration-thickness: 1px;
  text-underline-offset: 3px;
  overflow-wrap: anywhere;
}

#academic-home a:hover {
  color: #376583;
  text-decoration-color: currentColor;
}

#academic-home a:focus-visible {
  outline: 2px solid #376583;
  outline-offset: 4px;
}

#academic-home img {
  display: block;
  max-width: 100%;
  margin: 0;
  border: 0;
  box-shadow: none;
}

#academic-home section {
  scroll-margin-top: 24px;
}

/* 顶部导航 */
#academic-home .home-nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  min-height: 76px;
  border-bottom: 1px solid var(--line);
}

#academic-home .home-brand {
  font: 600 23px Georgia, "Times New Roman", serif;
  text-decoration: none;
}

#academic-home .home-links {
  display: flex;
  flex-wrap: wrap;
  gap: 26px;
}

#academic-home .home-links a {
  font-size: 14px;
  text-decoration: none;
}

/* 个人信息 */
#academic-home .profile-header {
  display: grid;
  grid-template-columns: 180px minmax(0, 1fr);
  align-items: center;
  gap: 44px;
  padding: 42px 0 34px;
}

#academic-home .profile-photo {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
}

#academic-home .profile-name {
  font-size: 46px;
  letter-spacing: -1px;
}

#academic-home .profile-name span {
  display: inline-block;
  margin-left: 14px;
  font-size: 27px;
  font-weight: 400;
  letter-spacing: 1px;
}

#academic-home .profile-role {
  margin-top: 8px;
  font-size: 18px;
}

#academic-home .profile-location {
  margin-top: 2px;
  color: var(--muted);
  font-size: 15px;
}

#academic-home .research-topics {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 16px;
}

#academic-home .research-topics span {
  padding: 3px 13px;
  border: 1px solid #bac4ca;
  border-radius: 4px;
  color: var(--ink);
  font-size: 13px;
}

#academic-home .profile-email {
  margin-top: 13px;
  font-size: 14px;
}

/* 个人简介 */
#academic-home .about-section {
  padding-bottom: 32px;
}

#academic-home .about-section h2 {
  margin-bottom: 16px;
}

#academic-home .about-section p + p {
  margin-top: 13px;
}

/* 论文区：保持整体宽度，缩小内部元素 */
#academic-home .publications-section,
#academic-home .hobbies-section {
  border-top: 1px solid var(--line);
  padding-top: 25px;
}

#academic-home .publications-section > h2 {
  margin-bottom: 12px;
}

#academic-home .publication {
  display: grid;
  grid-template-columns: minmax(0, 245px) minmax(0, 1fr);
  align-items: start;
  gap: 24px;
  padding: 20px 0;
  border-bottom: 1px solid var(--line);
}

#academic-home .publication:last-child {
  border-bottom: 0;
}

#academic-home .publication-image {
  align-self: center;
}

#academic-home .publication-image img {
  width: 100%;
  height: auto;
  border-radius: 4px;
}

#academic-home .publication h3 {
  font-size: 17px;
  font-weight: 600;
  line-height: 1.45;
}

#academic-home .publication .authors {
  margin-top: 6px;
  font-size: 14px;
  line-height: 1.55;
}

#academic-home .publication .venue {
  margin-top: 5px;
  color: var(--ink);
  font-size: 13px;
  line-height: 1.55;
}

#academic-home .publication .year {
  color: var(--muted);
  white-space: nowrap;
}

#academic-home .publication strong {
  font-weight: 600;
}

/* 爱好 */
#academic-home .hobbies-section {
  margin-top: 16px;
}

#academic-home .hobby-list {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 28px 32px;
  margin-top: 22px;
}

#academic-home .hobby h3 {
  margin-bottom: 9px;
  font-size: 18px;
}

#academic-home .hobby p {
  font-size: 14px;
  line-height: 1.7;
}

#academic-home .hobby p + p {
  margin-top: 7px;
}

#academic-home .hobby img {
  width: auto;
  max-width: 100%;
  height: 145px;
  object-fit: contain;
  object-position: left center;
  margin-top: 13px;
  border-radius: 4px;
}

/* 页脚 */
#academic-home .home-footer {
  display: flex;
  flex-wrap: wrap;
  gap: 8px 26px;
  margin-top: 42px;
  padding: 20px 0 30px;
  border-top: 1px solid var(--line);
  color: var(--muted);
  font-size: 13px;
}

/* 较窄桌面窗口仍保留论文左右布局 */
@media (max-width: 800px) {
  #academic-home {
    padding: 0 28px;
  }

  #academic-home .publication {
    grid-template-columns: minmax(0, 200px) minmax(0, 1fr);
    gap: 20px;
  }

  #academic-home .profile-header {
    grid-template-columns: 150px minmax(0, 1fr);
    gap: 28px;
  }

  #academic-home .profile-photo {
    width: 150px;
    height: 150px;
  }

  #academic-home .profile-name {
    font-size: 38px;
  }
}

/* 手机布局 */
@media (max-width: 600px) {
  #academic-home {
    padding: 0 20px;
    font-size: 15px;
  }

  #academic-home .home-nav {
    align-items: flex-start;
    flex-direction: column;
    gap: 9px;
    padding: 17px 0;
  }

  #academic-home .home-links {
    gap: 20px;
  }

  #academic-home .profile-header {
    grid-template-columns: 1fr;
    gap: 20px;
    padding: 28px 0;
  }

  #academic-home .profile-photo {
    width: 124px;
    height: 124px;
  }

  #academic-home .profile-name {
    font-size: 36px;
  }

  #academic-home .profile-name span {
    font-size: 23px;
  }

  #academic-home .profile-role {
    font-size: 16px;
  }

  #academic-home h2 {
    font-size: 25px;
  }

  #academic-home .publication {
    grid-template-columns: minmax(0, 1fr);
    gap: 12px;
    padding: 20px 0;
  }

  #academic-home .publication-image {
    width: min(245px, 100%);
  }

  #academic-home .publication h3 {
    font-size: 16px;
  }

  #academic-home .hobby-list {
    grid-template-columns: minmax(0, 1fr);
    gap: 25px;
  }
}
</style>

<div id="academic-home">

  <nav class="home-nav" aria-label="Homepage navigation">
    <a class="home-brand" href="{{ '/' | relative_url }}">Zeshui Li</a>
    <div class="home-links">
      <a href="#about">About</a>
      <a href="#publications">Publications</a>
      <a href="#hobbies">Hobbies</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header class="profile-header">
    <img
      class="profile-photo"
      src="{{ '/images/MeLittle.jpg' | relative_url }}"
      alt="Zeshui Li"
      width="180"
      height="180"
      fetchpriority="high"
    >
    <div>
      <h1 class="profile-name">
        Zeshui Li <span lang="zh-Hans">李泽水</span>
      </h1>
      <p class="profile-role">Postdoctoral Research Fellow</p>
      <p class="profile-location">Hong Kong</p>

      <div class="research-topics" aria-label="Research interests">
        <span>Wireless Sensing</span>
        <span>Haptics</span>
      </div>

      <p class="profile-email">
        <a href="mailto:zeshuili@cityu.edu.hk">zeshuili@cityu.edu.hk</a>
      </p>
    </div>
  </header>

  <section id="about" class="about-section" aria-labelledby="about-heading">
    <h2 id="about-heading">About</h2>

    <p>
      This is the homepage of Zeshui Li. My research interests are
      <strong>Wireless Sensing</strong> and <strong>Haptics</strong>.
      Welcome to share your questions and ideas with me
      (<a href="mailto:zeshuili@cityu.edu.hk">zeshuili@cityu.edu.hk</a>).
    </p>

    <p>
      I am a Postdoctoral Research Fellow at
      <a href="https://meilab-hk.github.io/index.html">MEI Lab</a>,
      supervised by Professor
      <a href="https://zhukening.wixsite.com/aboutme">Kening Zhu</a>.
      I received my Ph.D. from Nanjing University, where I was supervised
      by Professor
      <a href="http://cs.nju.edu.cn/gchen/">Guihai Chen</a>
      and Professor
      <a href="http://cs.nju.edu.cn/daihp/">Haipeng Dai</a>.
      During my doctoral studies, I also collaborated extensively with
      Professor <a href="http://cs.nju.edu.cn/ww/">Wei Wang</a>.
      Earlier in my career, from 2011 to 2014, I was a member of
      <a href="http://www.xiaoming-lab.com/">XiaoMing-Lab</a>.
    </p>
  </section>

  <section
    id="publications"
    class="publications-section"
    aria-labelledby="publications-heading"
  >
    <h2 id="publications-heading">Publications</h2>

    <article class="publication" aria-labelledby="pub-omnitex">
      <div class="publication-image">
        <img
          src="{{ '/images/OmniTex.png' | relative_url }}"
          alt="OmniTex haptic controller and surface texture rendering"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-omnitex">
          OmniTex: Omnidirectional Haptic Rendering of Surface Texture
          on VR Handheld Controller using 3-DOF Motion Mechanism.
        </h3>
        <p class="authors">
          Tianrui Hu, Haichen Gao, <strong>Zeshui Li</strong>,
          and Kening Zhu.
        </p>
        <p class="venue">
          <strong>ACM UIST</strong>
          <span class="year">· 2026</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-airpalm">
      <div class="publication-image">
        <img
          src="{{ '/images/AirPalm.png' | relative_url }}"
          alt="AirPalm phone-back airflow and haptic patterns"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-airpalm">
          AirPalm: Exploring Airborne Haptic Feedback from Phone-Back
          Airflow on the Palm.
        </h3>
        <p class="authors">
          Yibin Huai, Lina Zhang, <strong>Zeshui Li</strong>,
          and Kening Zhu.
        </p>
        <p class="venue">
          <strong>ACM IMWUT(Ubicomp)</strong>
          <span class="year">· 2026</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-proxeek">
      <div class="publication-image">
        <img
          src="{{ '/images/ProXeek.png' | relative_url }}"
          alt="ProXeek virtual reality scene and real-world haptic proxies"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-proxeek">
          ProXeek: Seeking and Leveraging Real-World Objects and
          Environments as Haptic Proxies for Virtual Reality through
          Multimodal Reasoning.
        </h3>
        <p class="authors">
          Haichen Gao, Tianrui Hu, <strong>Zeshui Li</strong>,
          and Kening Zhu.
        </p>
        <p class="venue">
          <strong>ACM TOG &amp; ACM SIGGRAPH</strong>
          <span class="year">· 2026</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-liqmetcraft">
      <div class="publication-image">
        <img
          src="{{ '/images/LiqMetCraft.png' | relative_url }}"
          alt="LiqMetCraft papercraft with embedded liquid-metal electronics"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-liqmetcraft">
          LiqMetCraft: A Toolkit for Creating Papercraft with Embedded
          Electronics By Directly Cutting and Folding Liquid-Metal-Dyed
          Paper-like Fabric.
        </h3>
        <p class="authors">
          Qi Zhang, Shuwen Jiang, <strong>Zeshui Li</strong>,
          Yong Lyu, Tiande Mo, and Kening Zhu.
        </p>
        <p class="venue">
          <strong>ACM CHI</strong>
          <span class="year">· 2026</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-mpgait">
      <div class="publication-image">
        <img
          src="{{ '/images/mPGait.png' | relative_url }}"
          alt="mP-Gait gait impairment assessment research figure"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-mpgait">
          mP-Gait: Fine-grained Parkinson’s Disease Gait Impairment
          Assessment with Robust Feature Analysis.
        </h3>
        <p class="authors">
          Wenhao Zhang, Haipeng Dai, Dongyu Xia, Yang Pan,
          <strong>Zeshui Li</strong>, Wei Wang, Zhen Li,
          Lei Wang and Guihai Chen.
        </p>
        <p class="venue">
          <strong>ACM IMWUT(Ubicomp)</strong>
          <span class="year">· 2024</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-pdgait">
      <div class="publication-image">
        <img
          src="{{ '/images/PDGait.png' | relative_url }}"
          alt="PD-Gait contactless acoustic gait measurement research figure"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-pdgait">
          PD-Gait: Contactless and Privacy-Preserving Gait Measurement
          of Parkinson's Disease Patients using Acoustic Signals.
        </h3>
        <p class="authors">
          <strong>Zeshui Li</strong>, Yang Pan, Haipeng Dai,
          Wenhao Zhang, Zhen Li, Wei Wang and Guihai Chen.
        </p>
        <p class="venue">
          <strong>Software: Practice and Experience (SPE)</strong>
          <span class="year">· 2023</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-pcias">
      <div class="publication-image">
        <img
          src="{{ '/images/PCIAS1.jpg' | relative_url }}"
          alt="PCIAS smartphone angular speed measurement research figure"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-pcias">
          PCIAS: Precise and Contactless Measurement of Instantaneous
          Angular Speed using a Smartphone.
        </h3>
        <p class="authors">
          <strong>Zeshui Li</strong>, Haipeng Dai, Wei Wang,
          Alex X. Liu and Guihai Chen.
        </p>
        <p class="venue">
          <strong>ACM IMWUT(Ubicomp)</strong>
          <span class="year">· 2019</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-driver">
      <div class="publication-image">
        <img
          src="{{ '/images/VehicleSpeaker.png' | relative_url }}"
          alt="Smartphone sensing of driver talking direction in a vehicle"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-driver">
          Recognizing Driver Talking Direction in Running Vehicles
          with a Smartphone.
        </h3>
        <p class="authors">
          Haipeng Dai, Alex X. Liu, <strong>Zeshui Li</strong>,
          Wei Wang, Fengmin Zhang and Chao Dong.
        </p>
        <p class="venue">
          <strong>IEEE MASS</strong>
          <span class="year">· 2019</span>
        </p>
      </div>
    </article>

    <article class="publication" aria-labelledby="pub-transistor">
      <div class="publication-image">
        <img
          src="{{ '/images/Transistor.jpg' | relative_url }}"
          alt="LabVIEW-based transistor tracer"
          loading="lazy"
          decoding="async"
        >
      </div>
      <div>
        <h3 id="pub-transistor">
          Design and Implementation of Simple Transistor Tracer
          Based on LabVIEW.
        </h3>
        <p class="authors">
          <strong>Zeshui Li</strong>, Weiling Liu, and Xiaoming Chang.
        </p>
        <p class="venue">
          <strong>
            National Embedded Instrument and SystemTechnology
            Academic Conference
          </strong>
          <span class="year">· 2013</span>
        </p>
      </div>
    </article>
  </section>

  <section
    id="hobbies"
    class="hobbies-section"
    aria-labelledby="hobbies-heading"
  >
    <h2 id="hobbies-heading">My Hobby</h2>

    <div class="hobby-list">
      <article class="hobby">
        <h3>Self balancing robot</h3>
        <p>
          I'm trying to combine such robot with smartphones to build
          a mobile platform for smart sensing.
        </p>
        <p>
          <a
            href="https://www.youtube.com/watch?v=_J-YQ3ySKJA&amp;list=PLxVt4lPz_cAiK9lSIy2-FKN1Th8wJ7R3r"
            title="My self balancing robot"
          >See my self balancing robot at youtube.</a>
        </p>
        <img
          src="{{ '/images/SelfBalancingRobotLittle.jpeg' | relative_url }}"
          alt="Self balancing robot"
          loading="lazy"
          decoding="async"
        >
      </article>

      <article class="hobby">
        <h3>Acoustic sensing</h3>
        <p>Acoustic sensing in robot arm control.</p>
        <img
          src="{{ '/images/AcousticSensingRobotArm.gif' | relative_url }}"
          alt="Acoustic sensing demonstration controlling a robot arm"
          loading="lazy"
          decoding="async"
        >
      </article>

      <article class="hobby">
        <h3>MicroPython</h3>
        <p>
          MicroPython based on hardware platform such as Pyboard,
          Microbit, ESP8266 and ESP32. A NeoPixel led ring drived
          by ESP8266 is shown below.
        </p>
        <img
          src="{{ '/images/NeoPixelLittle.jpeg' | relative_url }}"
          alt="NeoPixel LED ring driven by ESP8266"
          loading="lazy"
          decoding="async"
        >
      </article>

      <article class="hobby">
        <h3>CNC machine</h3>
        <p>
          I have a personal CNC machine, which effectively meets
          the needs of my DIY projects.
        </p>
        <img
          src="{{ '/images/CNC.jpg' | relative_url }}"
          alt="Personal CNC machine"
          loading="lazy"
          decoding="async"
        >
      </article>

      <article class="hobby">
        <h3>3D printer</h3>
        <p>
          The 3D printer could help me make mechanical parts for
          the self-balancing robots and toys for my children.
        </p>
        <img
          src="{{ '/images/3Dprinter.gif' | relative_url }}"
          alt="3D printer making a part"
          loading="lazy"
          decoding="async"
        >
      </article>
    </div>
  </section>

  <footer id="contact" class="home-footer">
    <span>Zeshui Li · Hong Kong</span>
    <a href="mailto:zeshuili@cityu.edu.hk">zeshuili@cityu.edu.hk</a>
  </footer>

</div>
