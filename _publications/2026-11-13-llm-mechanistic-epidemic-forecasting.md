---
title: "Mechanistic Grounding Makes Large Language Models Trustworthy for Epidemic Forecasts"
collection: publications
permalink: /publication/2026-11-13-llm-mechanistic-epidemic-forecasting
excerpt: '**First Author** | Submitted to *Nature Computational Science* — A mechanistically grounded forecasting framework combining 11 large language models with a Bayesian multi-pathogen transmission model. Across six respiratory pathogens, grounding reduced 1–4-week log-scale forecast error by **31–42%**, lowered point-forecast error by **27%**, and restored 90% interval coverage from **64% to 91%**.'
date: 2026-11-13
venue: 'Nature Computational Science'
status: 'submitted'
citation: '<b>Chen, J.</b>, Kong, L., Cowling, B. J., &amp; Ali, S. T. (2026). &quot;Mechanistic Grounding Makes Large Language Models Trustworthy for Epidemic Forecasts.&quot; Manuscript submitted to <i>Nature Computational Science</i>.'
---

<div style="margin-bottom:1em;display:flex;gap:0.45em;flex-wrap:wrap;">
  <span style="background:#9b59b6;color:white;padding:3px 10px;border-radius:12px;font-size:0.85em;font-weight:bold;">Submitted</span>
  <span style="background:#3498db;color:white;padding:3px 10px;border-radius:12px;font-size:0.85em;font-weight:bold;">First Author</span>
  <span style="background:#2c3e50;color:white;padding:3px 10px;border-radius:12px;font-size:0.85em;">Nature Computational Science</span>
</div>

## Authors

**Jiaqi Chen**, Lingkai Kong, Benjamin J. Cowling, Sheikh Taslim Ali

## Overview

Large language models can recognize qualitative epidemic drivers, but direct numerical forecasts are often overconfident and inconsistent. This study introduces a mechanistically grounded framework in which an LLM judges how transmissibility will change, while a Bayesian transmission model converts that judgement into calibrated forecasts with explicit uncertainty.

The framework evaluated 11 LLMs from eight developers across six co-circulating respiratory pathogens and 1–4-week forecast horizons. Mechanistic grounding improved every evaluated non-frontier LLM, reduced log-scale error by **31–42%**, lowered point-forecast error by **27%**, and increased coverage of 90% prediction intervals from **64% to 91%**. Large forecast failures disappeared, and the gains persisted in a retrospective 2015–2019 evaluation.

## Key Contributions

- Combined **11 LLMs** with a Bayesian multi-pathogen transmission model, assigning each component the task it performs best
- Converted qualitative LLM judgements into interpretable, mechanism-aware forecasts with honest uncertainty
- Demonstrated robust gains across six pathogens, multiple horizons, prospective data, and retrospective out-of-period evaluation
- Established a reusable design principle for trustworthy LLM-assisted quantitative forecasting beyond epidemiology

## Methods

`Large Language Models` &nbsp; `Bayesian Transmission Modeling` &nbsp; `Mechanistic Grounding` &nbsp; `Uncertainty Calibration` &nbsp; `Multi-Pathogen Forecasting` &nbsp; `Prospective Evaluation`

## Citation

**Chen, J.**, Kong, L., Cowling, B. J., & Ali, S. T. (2026). *Mechanistic grounding makes large language models trustworthy for epidemic forecasts.* Manuscript submitted to *Nature Computational Science*.
