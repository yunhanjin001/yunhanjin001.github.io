---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Columbia University**, New York, US
  * *Master in Mathematical Finance*, Expected Dec 2026
* **Fudan University**, Shanghai, CN
  * *B.Econ in Finance*, June 2025

Work experience
======
* Summer 2025: Inno Asset Management Co. | Quantitative Research Intern
  * Refined future factor models by implementing forward pricing, month-end adjustments, and vectorized computation.
  * Developed convergence and momentum strategies on minute-level data; FG and SA pairs achieved a peak **annual return of 27.81%**.
  * Applied linear regression for weight optimization, achieving an overall **Sharpe Ratio of 2.0** across 10 price-volume factors.

* Spring 2025: Shangjun Investment Management Co. | Quantitative Research Intern
  * Implemented an **LLM-based Stock-Agent** using Retrieval-Augmented Generation (RAG) for macro commodity market insights.
  * Optimized basis arbitrage strategies for stock index futures, enabling linked arbitrage between IC/IM/IF.

* Summer 2024: Jialong Technology Co. | Market Risk Management Intern
  * Generated daily market risk and P/L reports for Chinese futures markets; evaluated performance based on theoretical VaR deviations.
  * Enhanced multi-factor strategies using historical IC and volatility-based risk-adjusted weights, **improving annual returns by 30%** (Sharpe: 1.25).

* Zhejiang DeepWin Assets Co. | Quantitative Strategy Intern
  * Developed daily stock factors based on moment sorting and cross-sectional volume-price strategies.
  * Adapted **NSGA-II (Genetic Algorithm)** with IC and annual return thresholds, achieving a long-short annual return of **50.78% (IR: 3.77)**.

* CITIC Securities | Financial Analyst Intern
  * Evaluated stocks with research team using relevant risk management calculation models.

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
