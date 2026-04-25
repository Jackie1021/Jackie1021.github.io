---
title: "Predicting the Time-Varying Population Immunity and Importation Risk and Their Impact on Co-Circulation of Influenza and COVID-19 in Hong Kong"
collection: publications
permalink: /publication/2026-04-22-flu-covid-cocirculation-hk
excerpt: 'First Author | **Manuscript Under Submission** &nbsp;·&nbsp; target: *Nature Human Behaviour* — Benchmarks **three Bayesian transmission models — fully mechanistic, semi-mechanistic, and purely statistical** — against multi-source surveillance data to reconstruct 15 years of subtype-specific influenza immunity in Hong Kong and quantify a durable post-pandemic regime change in influenza–COVID-19 co-circulation.'
date: 2026-04-22
venue: 'Nature Human Behaviour'
status: 'submission'
citation: '<b>Chen, J.</b>, Wang, H., Wang, D., Lau, Y. C., Hossain, M. P., Ryu, S., Wu, P., Opatowski, L., Cowling, B. J., &amp; Ali, S. T. (2026). &quot;Predicting the time-varying population immunity and importation risk and their impact on co-circulation of influenza and COVID-19 in Hong Kong.&quot; <i>Manuscript under submission.</i>'
---

<div style="margin-bottom: 1em;">
  <span style="background:#f39c12;color:white;padding:3px 10px;border-radius:12px;font-size:0.85em;font-weight:bold;">📝 Under Submission</span>
  &nbsp;
  <span style="background:#2ecc71;color:white;padding:3px 10px;border-radius:12px;font-size:0.85em;font-weight:bold;">First Author</span>
  &nbsp;
  <span style="background:#1a5276;color:white;padding:3px 10px;border-radius:12px;font-size:0.85em;">Target: <i>Nature Human Behaviour</i></span>
</div>

## Authors

**Jiaqi Chen**, Hao Wang, Dong Wang, Yiu Chung Lau, M. Pear Hossain, Sukhyun Ryu, Peng Wu, Lulla Opatowski, Benjamin J. Cowling, Sheikh Taslim Ali

## Status

**Manuscript currently under submission.** Full preprint and publication links will be added after peer review.

## Three-Model Bayesian Benchmarking Framework

The central methodological contribution of this work is a side-by-side benchmarking of **three Bayesian transmission model families**, each representing a distinct philosophy of how influenza dynamics should be formalised:

<div style="display:flex; gap:1em; flex-wrap:wrap; margin:1em 0;">

  <div style="flex:1; min-width:230px; background:#f4f8ff; border:1px solid #aac8e8; border-radius:10px; padding:1em 1.2em;">
    <strong style="color:#1a5276;">① Fully Mechanistic</strong><br>
    <span style="color:#555; font-size:0.9em; line-height:1.6;">
      Compartmental SIR-type dynamics with explicit biological parameters (contact, waning, antigenic drift). Strong priors, full interpretability, but sensitive to model misspecification.
    </span>
  </div>

  <div style="flex:1; min-width:230px; background:#f5fff8; border:1px solid #a8ddb8; border-radius:10px; padding:1em 1.2em;">
    <strong style="color:#27ae60;">② Semi-Mechanistic</strong><br>
    <span style="color:#555; font-size:0.9em; line-height:1.6;">
      Hybrid framework retaining a mechanistic transmission core while letting flexible latent processes absorb unmodelled heterogeneity — <strong>consistently recovers subtype-resolved immunity distributions</strong> where the other two degrade.
    </span>
  </div>

  <div style="flex:1; min-width:230px; background:#fff5f0; border:1px solid #f0b0a0; border-radius:10px; padding:1em 1.2em;">
    <strong style="color:#c0392b;">③ Purely Statistical</strong><br>
    <span style="color:#555; font-size:0.9em; line-height:1.6;">
      Data-driven Bayesian regression with minimal structural assumptions. Flexible and low-bias under dense data, but weak extrapolation beyond the observed regime.
    </span>
  </div>

</div>

Benchmarking all three against identical syndromic, genomic, serological and air-travel data reveals that **only the semi-mechanistic framework consistently recovers subtype-resolved immunity distributions** (Kolmogorov–Smirnov distance 0.133–0.242), whereas the fully mechanistic and purely statistical alternatives each degrade two-fold for at least one subtype — establishing hybrid inference as methodologically essential for subtype-resolved influenza epidemiology.

## Abstract

Whether the COVID-19 pandemic only transiently interrupted seasonal influenza, or durably reshaped its transmission ecology, remains an unresolved question rendered urgent by anomalously severe post-pandemic influenza seasons. We reconstruct subtype-specific population immunity against influenza in Hong Kong across fifteen years (2010–2025) by benchmarking **three Bayesian transmission models — fully mechanistic, semi-mechanistic, and purely statistical** — against syndromic surveillance, genomic, serological and international air-travel data from twelve countries.

Inferred immunity follows a subtype-specific sawtooth pattern in which each epidemic initiates only after immunity returns to a seasonally reproducible, lineage-stable floor, predicting epidemic magnitude, speed and peak timing — and explaining up to 72% of within-subtype variance. Joint modelling of influenza–COVID-19 co-circulation (2019–2025) reveals durable post-pandemic shifts, including a twenty-fold pandemic collapse of the COVID-19–influenza interaction parameter and a four-fold attenuation of seasonal travel–influenza coupling despite near-complete mobility recovery.

## Key Contributions

- Built a **three-model Bayesian benchmarking framework** (fully mechanistic + semi-mechanistic + purely statistical) to reconstruct subtype-resolved influenza immunity over 15 years
- Established the **semi-mechanistic model as methodologically essential** — the only framework that consistently recovers the distributional profiles of immunity across all subtypes
- Integrated **multi-source surveillance**: syndromic, genomic, serological, and international air-travel data from 12 countries
- Uncovered a **subtype-specific sawtooth immunity pattern** that predicts epidemic magnitude, speed and peak timing (up to 72% within-subtype variance explained)
- Identified a **Simpson's paradox** in pooled influenza data, challenging the treatment of influenza as a single pathogen
- Quantified **subtype- and outcome-specific antigenic drift** effects across A(H1N1)pdm09, A(H3N2) and influenza B
- Demonstrated a **post-pandemic regime change** in influenza transmission: 20× collapse in the COVID-19–influenza interaction parameter, asymmetric restructuring of mainland-China importation dynamics, and 4× attenuation of travel–influenza seasonal coupling

## Technologies

`Python` &nbsp; `Stan / PyMC (Bayesian Inference)` &nbsp; `Fully Mechanistic ODE` &nbsp; `Semi-Mechanistic Hybrid Inference` &nbsp; `Statistical Bayesian Regression` &nbsp; `Genomic Surveillance Integration` &nbsp; `Multi-Source Data Fusion` &nbsp; `Kolmogorov–Smirnov Diagnostics`
