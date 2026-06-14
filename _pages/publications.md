---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
excerpt: "Selected publications by Qun Chen in biomedical AI, clinical multi-omics, molecular diagnostics, and translational data science."
---

<style>
.pub-cv-entry {
  padding: 14px 16px; margin-bottom: 10px;
  border-radius: 10px; border: 1.5px solid #e5e7eb;
  background: #fff; transition: border-color .2s, box-shadow .2s;
}
.pub-cv-entry:hover { border-color: #2563eb; box-shadow: 0 4px 16px rgba(37,99,235,.10); }
.pub-cv-venue {
  display: inline-block; font-size: 0.72em; font-weight: 700;
  background: #dbeafe; color: #1d4ed8; border-radius: 20px;
  padding: 2px 9px; margin-bottom: 6px; letter-spacing: .04em; text-transform: uppercase;
}
.pub-cv-title { font-size: 0.95em; font-weight: 700; line-height: 1.45; }
.pub-cv-title a { color: #1a2332; text-decoration: none; }
.pub-cv-title a:hover { color: #2563eb; text-decoration: underline; }
.pub-cv-authors { font-size: 0.80em; color: #6b7280; margin-top: 5px; line-height: 1.5; }
.pub-bib-wrap { margin-top: 6px; }
.pub-bib-btn {
  background: none; border: 1px solid #d1d5db; border-radius: 6px;
  color: #6b7280; font-size: 0.75em; font-weight: 600; padding: 2px 8px;
  cursor: pointer; transition: border-color .15s, color .15s;
}
.pub-bib-block { display: none; position: relative; margin-top: 6px; background: #1e293b; border-radius: 10px; padding: 18px 18px 12px; }
.pub-bib-block.open { display: block; }
.pub-bib-block pre { margin: 0; font-size: 0.78em; line-height: 1.65; color: #e2e8f0; white-space: pre; overflow-x: auto; }
.pub-bib-copy { position: absolute; top: 8px; right: 10px; background: #334155; border: none; border-radius: 5px; color: #adb5bd; font-size: 0.72em; font-weight: 600; padding: 3px 10px; cursor: pointer; }
.stat-badge { background:#f0f9ff;border:1px solid #bae6fd;border-radius:20px;padding:3px 12px;font-size:0.83em;font-weight:700;color:#0369a1; }
body.dark-mode .pub-cv-entry { background: #161b22 !important; border-color: #30363d !important; }
body.dark-mode .pub-cv-entry:hover { border-color: #58a6ff !important; box-shadow: 0 4px 16px rgba(88,166,255,.15); }
body.dark-mode .pub-cv-title a { color: #e6edf3 !important; }
body.dark-mode .pub-cv-authors { color: #8b949e !important; }
body.dark-mode .pub-cv-venue { background: #1e3a5f !important; color: #7dd3fc !important; }
body.dark-mode .stat-badge { background:#0c2044 !important; border-color:#1e3a5f !important; color:#7dd3fc !important; }
body.dark-mode .pub-bib-btn { border-color: #30363d !important; color: #8b949e !important; }
</style>

<div style="display:flex;gap:12px;flex-wrap:wrap;margin-bottom:1.2em;">
  <span class="stat-badge">Clinical multi-omics</span>
  <span class="stat-badge">Biomedical AI</span>
  <span class="stat-badge">Molecular diagnostics</span>
  <span class="stat-badge">Translational data science</span>
</div>

> Publications are listed in reverse chronological order. **\*** denotes co-first authorship and **†** denotes corresponding authorship where shown in the CV.

{% include base_path %}

<div style="padding:0; margin:0;">{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</div>
