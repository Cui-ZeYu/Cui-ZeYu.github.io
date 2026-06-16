---
permalink: /
title: "崔泽宇 | Digital Economy, AI & Quant Research"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
:root {
  --cz-ink: #121826;
  --cz-muted: #536071;
  --cz-line: rgba(18, 24, 38, 0.12);
  --cz-blue: #0f62fe;
  --cz-panel: rgba(255,255,255,0.82);
}

.page__title { display: none; }
.page { width: 100%; padding-right: 0; }
.page__inner-wrap { max-width: none; }
.page__content { font-size: 1rem; }
.archive, .page { float: none; }

.cz-home {
  color: var(--cz-ink);
  margin: -1.5rem auto 0;
  max-width: 1180px;
  padding: 0 1rem 3rem;
}

.cz-hero {
  position: relative;
  min-height: 76vh;
  overflow: hidden;
  display: grid;
  align-items: center;
  padding: clamp(3rem, 7vw, 6.5rem) clamp(1.25rem, 5vw, 4.5rem);
  background:
    radial-gradient(circle at 12% 18%, rgba(18,181,203,0.28), transparent 24rem),
    radial-gradient(circle at 82% 22%, rgba(15,98,254,0.22), transparent 24rem),
    linear-gradient(135deg, #f8fbff 0%, #eef5ff 42%, #f7fbf6 100%);
  box-shadow: 0 24px 80px rgba(18, 24, 38, 0.10);
}

.cz-hero::before,
.cz-hero::after {
  content: "";
  position: absolute;
  inset: 8%;
  pointer-events: none;
  background-image:
    linear-gradient(rgba(15,98,254,0.16) 1px, transparent 1px),
    linear-gradient(90deg, rgba(15,98,254,0.16) 1px, transparent 1px);
  background-size: 44px 44px;
  mask-image: radial-gradient(circle at 50% 45%, black, transparent 70%);
  animation: cz-drift 18s linear infinite;
}

.cz-hero::after {
  inset: auto 6% 8% auto;
  width: min(38vw, 420px);
  height: min(38vw, 420px);
  border: 1px solid rgba(15,98,254,0.18);
  border-radius: 50%;
  background: conic-gradient(from 90deg, rgba(15,98,254,0.1), rgba(18,181,203,0.2), rgba(46,125,50,0.14), rgba(15,98,254,0.1));
  animation: cz-spin 16s linear infinite;
}

.cz-hero__content {
  position: relative;
  z-index: 1;
  max-width: 860px;
}

.cz-kicker {
  display: inline-flex;
  gap: 0.55rem;
  align-items: center;
  padding: 0.45rem 0.7rem;
  border: 1px solid rgba(15,98,254,0.22);
  color: #194f90;
  background: rgba(255,255,255,0.72);
  backdrop-filter: blur(10px);
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0;
}

.cz-hero h1 {
  margin: 1.35rem 0 1rem;
  max-width: 780px;
  font-size: clamp(2.45rem, 6vw, 5.6rem);
  line-height: 0.96;
  letter-spacing: 0;
}

.cz-hero h1 span {
  color: transparent;
  background: linear-gradient(90deg, #0f62fe, #0b7f8f 48%, #2e7d32);
  -webkit-background-clip: text;
  background-clip: text;
}

.cz-lead {
  max-width: 760px;
  color: var(--cz-muted);
  font-size: clamp(1.02rem, 1.8vw, 1.25rem);
  line-height: 1.78;
}

.cz-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.8rem;
}

.cz-button {
  display: inline-flex;
  align-items: center;
  min-height: 42px;
  padding: 0.75rem 1rem;
  border: 1px solid rgba(18,24,38,0.16);
  color: var(--cz-ink) !important;
  background: rgba(255,255,255,0.78);
  text-decoration: none !important;
  font-weight: 700;
}

.cz-button--primary {
  color: white !important;
  border-color: #0f62fe;
  background: #0f62fe;
}

.cz-metrics {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.75rem;
  margin-top: 2.2rem;
  max-width: 780px;
}

.cz-metric {
  border: 1px solid rgba(18,24,38,0.12);
  background: rgba(255,255,255,0.68);
  backdrop-filter: blur(10px);
  padding: 0.85rem;
}

.cz-metric strong {
  display: block;
  font-size: 1.25rem;
  color: var(--cz-blue);
}

.cz-metric span {
  display: block;
  margin-top: 0.2rem;
  color: var(--cz-muted);
  font-size: 0.82rem;
  line-height: 1.45;
}

.cz-section {
  margin-top: clamp(2rem, 5vw, 4rem);
}

.cz-section h2 {
  font-size: clamp(1.55rem, 2.7vw, 2.35rem);
  margin-bottom: 1rem;
  letter-spacing: 0;
}

.cz-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}

.cz-card {
  border: 1px solid var(--cz-line);
  border-radius: 8px;
  background: var(--cz-panel);
  padding: 1.15rem;
  box-shadow: 0 14px 36px rgba(18,24,38,0.06);
}

.cz-card h3 {
  margin: 0 0 0.5rem;
  font-size: 1.08rem;
}

.cz-card p,
.cz-card li {
  color: var(--cz-muted);
  line-height: 1.72;
}

.cz-card ul { padding-left: 1.05rem; margin-bottom: 0; }
.cz-tagline { color: var(--cz-muted); max-width: 780px; line-height: 1.76; }

.cz-timeline {
  display: grid;
  gap: 1rem;
}

.cz-item {
  display: grid;
  grid-template-columns: minmax(150px, 220px) 1fr;
  gap: 1rem;
  border-top: 1px solid var(--cz-line);
  padding-top: 1rem;
}

.cz-date {
  color: var(--cz-blue);
  font-weight: 800;
}

.cz-item h3 { margin: 0 0 0.35rem; font-size: 1.1rem; }
.cz-item p { margin: 0.2rem 0 0; color: var(--cz-muted); line-height: 1.72; }

.cz-chip-row { display: flex; flex-wrap: wrap; gap: 0.55rem; margin-top: 0.85rem; }
.cz-chip {
  border: 1px solid rgba(18,24,38,0.14);
  padding: 0.45rem 0.65rem;
  background: #fff;
  color: #334155;
  font-size: 0.88rem;
}

.cz-footer-note {
  margin-top: 3rem;
  color: var(--cz-muted);
  border-top: 1px solid var(--cz-line);
  padding-top: 1.2rem;
}

@keyframes cz-drift {
  from { transform: translate3d(0,0,0); }
  to { transform: translate3d(44px,44px,0); }
}

@keyframes cz-spin {
  to { transform: rotate(360deg); }
}

@media (max-width: 900px) {
  .cz-metrics, .cz-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .cz-item { grid-template-columns: 1fr; }
  .cz-date { margin-bottom: -0.35rem; }
}

@media (max-width: 560px) {
  .cz-home { padding-left: 0.35rem; padding-right: 0.35rem; }
  .cz-hero { min-height: 70vh; padding: 2.5rem 1rem; }
  .cz-metrics, .cz-grid { grid-template-columns: 1fr; }
  .cz-actions { flex-direction: column; }
  .cz-button { justify-content: center; }
}
</style>

<div class="cz-home">
  <section class="cz-hero" id="top">
    <div class="cz-hero__content">
      <div class="cz-kicker">Nanjing University · Digital Economy · AI for Finance</div>
      <h1>崔泽宇<br><span>把数据变成判断力</span></h1>
      <p class="cz-lead">南京大学数字经济专业本科生，关注人工智能、量化金融与数据驱动决策。我的工作横跨高频数据工程、多因子策略研究、低比特模型量化与多模态金融分析，习惯用清晰的工程实现支撑可解释的商业洞察。</p>
      <div class="cz-actions">
        <a class="cz-button cz-button--primary" href="mailto:3027771319@qq.com">联系我</a>
        <a class="cz-button" href="https://github.com/Cui-ZeYu">GitHub</a>
        <a class="cz-button" href="#projects">查看项目</a>
      </div>
      <div class="cz-metrics" aria-label="Highlights">
        <div class="cz-metric"><strong>4.22/5.0</strong><span>南京大学 GPA</span></div>
        <div class="cz-metric"><strong>13.84x</strong><span>高频表查询性能提升</span></div>
        <div class="cz-metric"><strong>22.26%</strong><span>可转债多因子组合年化收益</span></div>
        <div class="cz-metric"><strong>Top 1</strong><span>LVMH Beauty 校园创意挑战赛金奖</span></div>
      </div>
    </div>
  </section>

  <section class="cz-section" id="profile">
    <h2>Profile</h2>
    <p class="cz-tagline">我喜欢把复杂问题拆成可验证的信号、模型与系统：从金融市场中的因子挖掘，到模型量化中的精度与部署权衡，再到遥感影像中的城市经济测算。相比堆叠概念，我更重视数据口径、实验设计、工程稳定性与最终解释力。</p>
  </section>

  <section class="cz-section" id="experience">
    <h2>Experience</h2>
    <div class="cz-timeline">
      <article class="cz-item">
        <div class="cz-date">2025.01 - 2025.03</div>
        <div>
          <h3>建信期货 · 量化实习生</h3>
          <p>完成 EQUITY / FUTURES / OPTIONS 数据迁移、弹性表空间重构、按月分区与本地分区索引建设，将典型分钟级高频表查询耗时降至 7 秒。基于 XtTraderApi 构建 tick 订阅与分钟线实时聚合管道，通过 Zarr 共享内存输出将分钟数据接收延迟由 0.19 秒降至 0.01 秒。</p>
        </div>
      </article>
      <article class="cz-item">
        <div class="cz-date">2025.06 - 2025.08</div>
        <div>
          <h3>上海智辰微技术有限公司 · 算法实习生</h3>
          <p>调研并实验旋转前放缩、FPTQuant、BitNetV2 等超低比特量化算法；基于 Neural Compressor 对 Qwen3 进行 W8A8 量化并分析逐层运算数据，在硬件友好条件下控制精度损失。针对 SD3.5 / SDSL 的文本编码器、UNET、EVA 模块完成组合量化实验。</p>
        </div>
      </article>
    </div>
  </section>

  <section class="cz-section" id="projects">
    <h2>Selected Projects</h2>
    <div class="cz-grid">
      <article class="cz-card">
        <h3>PetroAlpha 油价多因子预测与风险分析平台</h3>
        <p>构建覆盖库存、供需、进口成本、宏观金融、地缘风险和新闻文本的原油因子体系，生成约 400 个候选因子，并通过经济逻辑与统计检验筛选核心因子。</p>
        <ul>
          <li>花旗杯项目，已进入决赛</li>
          <li>组合年化收益约 13.95%，夏普比率 1.04</li>
        </ul>
      </article>
      <article class="cz-card">
        <h3>FinerSeek 智能金融分析平台</h3>
        <p>使用多模态检索增强生成框架，融合 CLIP 跨模态对齐与混合检索技术，服务包含图表年报的语义问答与关键指标解析。</p>
        <ul>
          <li>语义问答准确率 92%</li>
          <li>构建 Milvus 数据库与 5 万+术语库</li>
        </ul>
      </article>
      <article class="cz-card">
        <h3>遥感影像驱动的第三产业 GDP 测算</h3>
        <p>作为队长构建 CNN 驱动的多模态遥感分析框架，结合 SDGSAT-1 全波段数据、土地利用数据与 POI 信息，研究长三角第三产业空间化发展。</p>
        <ul>
          <li>第三产业 GDP 预测误差率不高于 8%</li>
          <li>支持商业聚集区与产业园区识别</li>
        </ul>
      </article>
    </div>
  </section>

  <section class="cz-section" id="education">
    <h2>Education & Leadership</h2>
    <div class="cz-grid">
      <article class="cz-card">
        <h3>南京大学 · 数字经济</h3>
        <p>GPA 4.22 / 5.0。主修课程包括最优化、概率统计、数据结构与算法、人工智能、机器学习、深度学习平台、数据库、操作系统、计量经济学与金融经济学。</p>
      </article>
      <article class="cz-card">
        <h3>组织与协作</h3>
        <p>曾任南京大学团学联文体部副部长，参与十佳歌手、三行情诗等活动组织，负责外联、评审协调、现场统筹与执行落地。</p>
      </article>
      <article class="cz-card">
        <h3>荣誉与志愿服务</h3>
        <p>2025 年 LVMH Beauty 第九届校园创意挑战赛 Top 1 金奖；累计志愿时长 300 余小时，参与社区关怀与大型会议服务。</p>
      </article>
    </div>
  </section>

  <section class="cz-section" id="skills">
    <h2>Skills</h2>
    <p class="cz-tagline">技术栈覆盖金融数据分析、机器学习实验、数据库处理与内容表达工具，适合在研究、产品与业务之间做跨语言协作。</p>
    <div class="cz-chip-row">
      <span class="cz-chip">Python</span>
      <span class="cz-chip">C / C++</span>
      <span class="cz-chip">SQL</span>
      <span class="cz-chip">R</span>
      <span class="cz-chip">MATLAB</span>
      <span class="cz-chip">Machine Learning</span>
      <span class="cz-chip">Quant Research</span>
      <span class="cz-chip">Milvus</span>
      <span class="cz-chip">Zarr</span>
      <span class="cz-chip">ArcGIS</span>
      <span class="cz-chip">Photoshop / Premiere / Audition</span>
    </div>
  </section>

  <p class="cz-footer-note">Open to opportunities around quantitative research, AI applications, data-driven product strategy, and interdisciplinary business analytics.</p>
</div>
