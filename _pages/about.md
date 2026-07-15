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

Hi! I'm **Ke Xu** — I just finished my M.Eng. at Peking University and recently joined Baidu ERNIE, where I work on LLM Agents. Before that, I got my B.Eng. at Sun Yat-sen University.

My research lives at the crossroads of **LLM Agents** and **Reinforcement Learning**. Always happy to chat about agents, RL, or anything in between!

# 🔥 News
- *2026.07*: &nbsp;🎓 Graduated with my M.Eng. from Peking University and joined Baidu ERNIE to keep working on LLM agents!
- *2026.04*: &nbsp;🎉 Our paper *FuseSearch* was accepted to Findings of ACL 2026!
- *2023.06*: &nbsp;🎓 Graduated with my B.Eng. from Sun Yat-sen University and was admitted to Peking University for graduate study.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/stamp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[STAMP: Provenance-Guided Credit Assignment for Deep Search Agents](https://arxiv.org/abs/2607.11172)

**Ke Xu**, Han Xu, Xinran Chen, Yuqian Wang, Zhixuan Li, Xiaojian Liu, Changwo Wu, Jianqiang Xia, Yuchen Li

- A provenance-guided credit assignment method that traces which retrieval steps actually drive a deep search agent's final answer, giving cleaner learning signals.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/codi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Cognitively Decoupled Meta-Induction for Out-of-Distribution Generalization

Yuqian Wang, Yuanzheng Wang, Chaojun Xiao, **Ke Xu**, Bingxiang He, Jinghan Tan, Zijun Chen, Lu Chen, Yi-Xin Huo, Maosong Sun

- Proposes CoDI, a meta-learning method that induces query-blind, task-level inductive representations to improve in-context learning under out-of-distribution shift, with gains persisting even without explicit induction at inference.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/scoperl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SCOPE-RL: Optimizing Reasoning Paths Before and After Success](https://arxiv.org/abs/2607.11506)

Xiaojian Liu, Han Xu, Jianqiang Xia, Zhixuan Li, **Ke Xu**, Yiwei Dai, Xinran Chen, Changwo Wu, Yuchen Li

- An RL approach that refines an agent's reasoning paths both before and after a correct answer, making the reasoning more robust and reliable.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/fusesearch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FuseSearch: Learning Adaptive Parallel Execution for Efficient Code Localization](https://aclanthology.org/2026.findings-acl.143/)

**Ke Xu**, Siyang Xiao, Ming Liang, Yichen Yu, Zhixiang Wang, Jingxuan Xu, Dajun Chen, Wei Jiang, Yong Li. *Findings of ACL 2026*

- Reframes parallel code localization as a quality–efficiency co-optimization problem. FuseSearch-4B matches SOTA on SWE-bench Verified (84.7% file-level, 56.4% function-level F1) while being 93.6% faster, using 67.7% fewer turns and 68.9% fewer tokens.
</div>
</div>

# 📖 Educations
- *2023.09 - 2026.07*, M.Eng. in Advanced Manufacturing and Robotics, Peking University.
- *2019.09 - 2023.07*, B.Eng., School of Aeronautics and Astronautics, Sun Yat-sen University.

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Internships
- *2026.01 - 2026.06*, Baidu ERNIE, — Long-horizon Agent.
- *2025.06 - 2026.01*, Ant Group, CodeFuse Group — Agentic RL for Code Agent.
- *2024.11 - 2025.05*, Tencent IEG, LightSpeed Learning & Development Group — RL for Game.
