---
permalink: /
title: "Qun Chen"
excerpt: "Associate Research Fellow | Clinical Multi-omics and Biomedical AI"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.tagline { font-size: 1.04em; line-height: 1.78; color: #333; margin-bottom: 1em; }
.quick-nav {
  background: #f0f4ff; border-radius: 8px;
  padding: 9px 16px; margin-bottom: 1.4em;
  font-size: 0.84em; display: flex; flex-wrap: wrap; gap: 5px 16px; align-items: center;
  position: sticky; top: 0; z-index: 90;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
}
.quick-nav a { color: #1565c0; text-decoration: none; padding: 2px 6px; border-radius: 5px; transition: background .15s, color .15s; }
.quick-nav a:hover { background: #e8effe; }
.quick-nav a.qn-active { background: #1565c0; color: #fff !important; }
.qn-label { font-weight: 800; color: #1565c0; }
.section-header {
  display: flex; align-items: center; gap: 10px;
  margin: 2em 0 1em; padding: 0; font-size: 1.18em; font-weight: 800; color: #1a2332;
  letter-spacing: 0; scroll-margin-top: 120px;
  border: none; background: none;
}
.section-header::after {
  content: ''; flex: 1; height: 2px;
  background: linear-gradient(to right, #1565c0, transparent); border-radius: 1px;
}
@keyframes gradientShift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
.hero-banner {
  background: linear-gradient(-45deg, #0a1626, #12395a, #0f7f7a, #6b4b1d, #0a2540);
  background-size: 400% 400%;
  animation: gradientShift 16s ease infinite;
  border-radius: 18px;
  padding: 46px 32px 38px;
  margin-bottom: 1.8em;
  text-align: center;
  color: #fff;
  box-shadow: 0 10px 40px rgba(13,40,90,0.28), inset 0 1px 0 rgba(255,255,255,0.08);
  position: relative; overflow: hidden;
}
.hero-banner::after {
  content: ''; position: absolute; inset: 0; pointer-events: none; z-index: 0;
  background: radial-gradient(120% 90% at 50% 0%, rgba(255,255,255,0.11), transparent 55%);
}
.hero-name, .hero-subtitle, .hero-pills, .hero-links { position: relative; z-index: 1; }
.hero-name {
  font-size: 2.55em; font-weight: 900; color: #fff;
  margin: 0 0 8px; padding: 0; line-height: 1.1; border: none;
}
.hero-subtitle {
  font-size: 1em; color: #dbeafe; margin-bottom: 16px;
  font-weight: 500; letter-spacing: 0.01em;
}
.hero-pills { display: flex; flex-wrap: wrap; gap: 7px; justify-content: center; max-width: 620px; margin: 0 auto 20px; }
.hero-pill {
  background: rgba(255,255,255,0.10); border: 1px solid rgba(255,255,255,0.20);
  color: #eaf3ff; padding: 5px 14px; border-radius: 20px;
  font-size: 0.80em; font-weight: 600; white-space: nowrap;
}
.hero-links { display: flex; gap: 9px; justify-content: center; flex-wrap: wrap; }
.hero-link {
  display: inline-flex; align-items: center; gap: 6px;
  background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.22);
  color: #fff !important; padding: 7px 16px; border-radius: 9px;
  font-size: 0.82em; font-weight: 700; text-decoration: none !important;
  transition: background .2s, transform .15s, box-shadow .2s, border-color .2s;
}
.hero-link:hover {
  background: rgba(255,255,255,0.92); color: #0d47a1 !important;
  border-color: rgba(255,255,255,0.92); transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.22);
}
.stats-row { display: flex; flex-wrap: wrap; gap: 12px; margin: 1.2em 0 1.6em; }
.stat-card {
  flex: 1 1 130px; background: #fff;
  border: 1.5px solid #e0e8f0; border-radius: 10px;
  padding: 14px 16px; text-align: center;
  box-shadow: 0 2px 8px rgba(21,101,192,.07);
}
.stat-number { font-size: 1.85em; font-weight: 900; color: #1565c0; line-height: 1.1; }
.stat-label { font-size: 0.77em; color: #595959; margin-top: 4px; line-height: 1.35; }
.research-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 14px; margin-bottom: 1.5em; }
.research-card {
  background: #fff; border: 1.5px solid #e0e8f0; border-radius: 10px;
  padding: 16px; transition: border-color .2s, box-shadow .2s;
}
.research-card:hover { border-color: #1565c0; box-shadow: 0 4px 14px rgba(21,101,192,.12); }
.rc-icon { font-size: 1.7em; margin-bottom: 8px; }
.rc-title { font-weight: 800; font-size: 0.93em; color: #1a2332; margin-bottom: 5px; }
.rc-desc { font-size: 0.81em; color: #555; line-height: 1.55; }
.pub-list { margin: 0; padding: 0; }
.pub-entry {
  display: grid; grid-template-columns: 92px 1fr; gap: 16px;
  padding: 18px 0; border-bottom: 1px solid #f0f0f0; align-items: start;
}
.pub-entry:last-child { border-bottom: none; }
.pub-left { display: flex; flex-direction: column; gap: 4px; align-items: flex-start; padding-top: 2px; }
.pb {
  display: inline-block; padding: 3px 8px; border-radius: 5px;
  font-size: 0.70em; font-weight: 900; letter-spacing: 0.02em; white-space: nowrap; line-height: 1.4;
}
.pb-digital { background: #1565c0; color: #fff; }
.pb-cvd { background: #00897b; color: #fff; }
.pb-omics { background: #6a1b9a; color: #fff; }
.pb-dx { background: #e65100; color: #fff; }
.pb-journal { background: #546e7a; color: #fff; }
.pub-year { font-size: 0.77em; color: #767676; font-weight: 700; }
.pub-title { font-weight: 700; font-size: 0.95em; color: #1a2332; line-height: 1.4; }
.pub-title a { color: #1565c0; text-decoration: none; }
.pub-title a:hover { text-decoration: underline; }
.pub-authors { font-size: 0.81em; color: #6b7280; margin-top: 3px; }
.pub-authors strong { color: #1a2332; font-weight: 700; }
.pub-desc { font-size: 0.81em; color: #444; margin-top: 4px; line-height: 1.55; }
.pub-hl {
  display: inline-block; background: #fff8e1;
  border-left: 3px solid #ffa000; padding: 2px 9px;
  border-radius: 0 4px 4px 0; font-size: 0.77em;
  color: #5a4000; margin-top: 5px; font-weight: 700;
}
.feature-list { margin: 0; padding-left: 1.1em; color: #444; line-height: 1.75; }
.skill-cloud { display: flex; flex-wrap: wrap; gap: 8px; margin-top: .8em; }
.skill-cloud span {
  display: inline-block; padding: 4px 10px; border-radius: 6px;
  background: #e8f4fd; color: #0d47a1; border: 1px solid #b3d4f7;
  font-size: 0.78em; font-weight: 700;
}
.timeline { position: relative; padding-left: 28px; margin: 1em 0 1.6em; }
.timeline::before {
  content: ''; position: absolute; left: 8px; top: 0; bottom: 0;
  width: 3px; background: linear-gradient(to bottom, #1565c0, #00897b, #e65100); border-radius: 2px;
}
.timeline-item { position: relative; padding: 10px 0 18px; font-size: 0.88em; }
.timeline-item::before {
  content: ''; position: absolute; left: -24px; top: 14px;
  width: 11px; height: 11px; border-radius: 50%;
  background: #fff; border: 3px solid #1565c0; z-index: 1;
}
.timeline-year { font-weight: 800; color: #1565c0; font-size: 0.82em; }
.timeline-title { font-weight: 700; color: #1a2332; margin-top: 2px; }
.timeline-desc { color: #555; font-size: 0.92em; line-height: 1.6; margin-top: 2px; }
@media(max-width:720px){
  .research-grid { grid-template-columns: 1fr; }
  .pub-entry { grid-template-columns: 1fr; }
  .pub-left { flex-direction: row; gap: 8px; }
}
body.dark-mode .tagline,
body.dark-mode .rc-desc,
body.dark-mode .pub-desc,
body.dark-mode .timeline-desc,
body.dark-mode .feature-list { color: #8b949e !important; }
body.dark-mode .research-card,
body.dark-mode .stat-card { background: #161b22 !important; border-color: #30363d !important; }
body.dark-mode .section-header,
body.dark-mode .rc-title,
body.dark-mode .pub-title,
body.dark-mode .pub-authors strong,
body.dark-mode .timeline-title { color: #e6edf3 !important; }
body.dark-mode .quick-nav { background: #1c2333 !important; }
body.dark-mode .quick-nav a,
body.dark-mode .qn-label { color: #58a6ff !important; }
body.dark-mode .quick-nav a.qn-active { background: #388bfd !important; color: #fff !important; }
body.dark-mode .pub-entry { border-bottom-color: #21262d !important; }
body.dark-mode .pub-authors,
body.dark-mode .pub-year,
body.dark-mode .stat-label { color: #8b949e !important; }
</style>

<div class="hero-banner">
  <h1 class="hero-name">Qun Chen, PhD</h1>
  <div class="hero-subtitle">Associate Research Fellow · The First Affiliated Hospital of Xiamen University</div>
  <div class="hero-pills">
    <span class="hero-pill">Clinical multi-omics</span>
    <span class="hero-pill">Biomedical AI</span>
    <span class="hero-pill">Disease trajectory modeling</span>
    <span class="hero-pill">Translational data science</span>
  </div>
  <div class="hero-links">
    <a class="hero-link" href="mailto:chenquns@xmu.edu.cn">Email</a>
    <a class="hero-link" href="/files/CV.pdf">CV</a>
    <a class="hero-link" href="https://orcid.org/0009-0002-8921-7697">ORCID</a>
  </div>
</div>

<div class="quick-nav">
  <span class="qn-label">Jump to</span>
  <a href="#research" data-qn="research">Research</a>
  <a href="#publications" data-qn="publications">Publications</a>
  <a href="#patents" data-qn="patents">Patents</a>
  <a href="#funding" data-qn="funding">Funding</a>
  <a href="#training" data-qn="training">Training</a>
  <a href="#skills" data-qn="skills">Skills</a>
</div>

<p class="tagline">
My research sits at the interface of <strong>clinical multi-omics</strong>, <strong>biomedical AI</strong>, and
<strong>translational data science</strong>. I build interpretable machine-learning and statistical models that connect
large-scale molecular signatures, including plasma proteomics and metabolomics, to disease trajectories,
clinical outcomes, and biological mechanisms.
</p>

<div class="stats-row">
  <div class="stat-card"><div class="stat-number">134,500</div><div class="stat-label">hospitalized children in Pathog-PDx validation</div></div>
  <div class="stat-card"><div class="stat-number">244,567</div><div class="stat-label">UK Biobank participants in CVD metabolomic atlas</div></div>
  <div class="stat-card"><div class="stat-number">87</div><div class="stat-label">cardiovascular disease phenotypes mapped</div></div>
  <div class="stat-card"><div class="stat-number">2,900</div><div class="stat-label">plasma proteins in UKB-PPP scale analyses</div></div>
</div>

<h2 id="research" class="section-header">Research</h2>
<div class="research-grid">
  <div class="research-card">
    <div class="rc-icon">AI</div>
    <div class="rc-title">Interpretable Clinical Prediction</div>
    <div class="rc-desc">Machine-learning systems that integrate EHR features and molecular data for diagnosis, risk modeling, and clinical decision support.</div>
  </div>
  <div class="research-card">
    <div class="rc-icon">OM</div>
    <div class="rc-title">Proteomic and Metabolomic Atlases</div>
    <div class="rc-desc">Population-scale maps of molecular signatures across cardiovascular phenotypes, comorbidity structures, and shared pathways.</div>
  </div>
  <div class="research-card">
    <div class="rc-icon">TR</div>
    <div class="rc-title">Trajectory-to-Mechanism Translation</div>
    <div class="rc-desc">Survival analysis, causal inference, mediation analysis, and biological interpretation for translational molecular medicine.</div>
  </div>
</div>

<h2 id="publications" class="section-header">Selected Publications</h2>
<div class="pub-list">
  <div class="pub-entry">
    <div class="pub-left"><span class="pb pb-digital">NPJ DM</span><span class="pub-year">2026</span></div>
    <div>
      <div class="pub-title"><a href="/publication/2026-01-01-pathog-pdx">Development and validation of a machine learning-based diagnostic system for 22 pediatric respiratory pathogens</a></div>
      <div class="pub-authors">Su D, <strong>Chen Q*</strong>, Xu R, Chen Q, Ma C, Chen X, Yang Y, et al.</div>
      <div class="pub-desc"><em>npj Digital Medicine</em>. doi:10.1038/s41746-026-02818-9.</div>
      <div class="pub-hl">Pathog-PDx · 42 EHR features · mean AUC 0.88</div>
    </div>
  </div>
  <div class="pub-entry">
    <div class="pub-left"><span class="pb pb-cvd">JACC</span><span class="pub-year">2026</span></div>
    <div>
      <div class="pub-title"><a href="/publication/2026-01-02-cvd-metabolomic-atlas">Metabolomic Atlas of Cardiovascular Diseases: Mapping Shared and Specific Signatures</a></div>
      <div class="pub-authors">Yang J, Ning W, Xu R, Guo Y, He A, Fan J, Wang Y, Li X, <strong>Chen Q†</strong></div>
      <div class="pub-desc"><em>JACC: Advances</em>, 5(5):102742. doi:10.1016/j.jacadv.2026.102742.</div>
      <div class="pub-hl">325 NMR metabolites · 244,567 participants · 87 CVD phenotypes</div>
    </div>
  </div>
  <div class="pub-entry">
    <div class="pub-left"><span class="pb pb-omics">SciBull</span><span class="pub-year">2026</span></div>
    <div>
      <div class="pub-title"><a href="/publication/2026-01-03-deep-visual-multi-omics">Deep visual multi-omics reveals intra-tumor heterogeneity of gene expression and immunophenotype in colorectal cancer</a></div>
      <div class="pub-authors">Lei S, Ning W, Zhang H, <strong>Chen Q*</strong>, Xu L, Tian S, Li X, et al.</div>
      <div class="pub-desc"><em>Science Bulletin</em>. doi:10.1016/j.scib.2026.04.047.</div>
      <div class="pub-hl">Pathology image AI · spatial molecular state prediction</div>
    </div>
  </div>
  <div class="pub-entry">
    <div class="pub-left"><span class="pb pb-dx">JMV</span><span class="pub-year">2023</span></div>
    <div>
      <div class="pub-title"><a href="/publication/2023-01-01-crispr-cas12-monkeypox">CRISPR Cas12-based field-deployable system for rapid detection of synthetic DNA sequence of the monkeypox virus genome</a></div>
      <div class="pub-authors"><strong>Chen Q*</strong>, Gul I*, Liu C, et al.</div>
      <div class="pub-desc"><em>Journal of Medical Virology</em>, 95(1):e28385.</div>
      <div class="pub-hl">CRISPR diagnostics · field-deployable detection</div>
    </div>
  </div>
</div>

<h2 id="patents" class="section-header">Selected Patents</h2>
<ul class="feature-list">
  <li><strong>Chen Q</strong>, Ning W, Zhang S, et al. Method and Apparatus for Brain Age Prediction Based on Deep Learning and Metabolomics Data. CN202411303281.8, 2025.</li>
  <li>Ning W, <strong>Chen Q</strong>, Zhang S, et al. Method and Apparatus for Cardiovascular Age Prediction Based on Deep Learning and Metabolic Profiling. CN202411384982.9, 2024.</li>
  <li>Ning W, <strong>Chen Q</strong>, Hong G, et al. Clustering Method and Apparatus for Cardiovascular and Cerebrovascular Disease Mortality Populations Based on DNN and Consensus Clustering. CN202411453198.9, 2024.</li>
</ul>

<h2 id="funding" class="section-header">Research Funding</h2>
<p class="tagline">
<strong>Principal Investigator</strong>, Fujian Provincial Natural Science Foundation, Grant No. 2025J08313,
May 2025 - Apr. 2028. Project: Study on Maternal Chronic Stress Inducing Neural Precursor Cell
Differentiation Disorders via the Ncam1-MAPK Signaling Pathway.
</p>

<h2 id="training" class="section-header">Position & Doctoral Training</h2>
<div class="timeline">
  <div class="timeline-item"><div class="timeline-year">Aug. 2023 - Present</div><div class="timeline-title">The First Affiliated Hospital of Xiamen University</div><div class="timeline-desc">Associate Research Fellow, Xiamen Cell Therapy Research Center & Xiamen University School of Medicine.</div></div>
  <div class="timeline-item"><div class="timeline-year">Sep. 2017 - Dec. 2022</div><div class="timeline-title">Tsinghua University</div><div class="timeline-desc">PhD in Biomedical Engineering. Dissertation: Molecular detection technologies for rapid infectious disease diagnosis and biomarker discovery.</div></div>
</div>

<h2 id="skills" class="section-header">Technical Skills</h2>
<div class="skill-cloud">
  <span>Python</span><span>R</span><span>PyTorch</span><span>TensorFlow</span><span>XGBoost</span>
  <span>Transformer models</span><span>Survival analysis</span><span>Mendelian randomization</span>
  <span>Mediation analysis</span><span>Plasma proteomics</span><span>Metabolomics</span>
  <span>scRNA-seq</span><span>Spatial omics</span><span>CRISPR-Cas12/13 diagnostics</span>
</div>

<script>
(function(){
  var sections = ['research','publications','patents','funding','training','skills'];
  var navLinks = Array.prototype.slice.call(document.querySelectorAll('.quick-nav a[data-qn]'));
  if (!navLinks.length || !('IntersectionObserver' in window)) return;

  function setActive(id) {
    navLinks.forEach(function(link) {
      link.classList.toggle('qn-active', link.dataset.qn === id);
    });
  }

  var current = '';
  var observer = new IntersectionObserver(function(entries) {
    entries.forEach(function(entry) {
      if (entry.isIntersecting) current = entry.target.id;
    });
    if (current) setActive(current);
  }, { rootMargin: '-20% 0px -68% 0px', threshold: 0 });

  sections.forEach(function(id) {
    var el = document.getElementById(id);
    if (el) observer.observe(el);
  });
})();
</script>
