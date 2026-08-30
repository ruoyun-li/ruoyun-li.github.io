---
title: "Research"
permalink: /research/
author_profile: false
---

---

<div class="research-item">
  <h2 class="research-item__title">Cost-Aware Framework for Personalized Feature Acquisition in Multi-Disease Prediction<span class="research-item__badge">Manuscript in Preparation</span></h2>
  <p class="research-item__meta">Jul 2025 – Present &nbsp;·&nbsp; Prof. Yize Zhao, Department of Biostatistics, Yale School of Public Health</p>

  <div class="research-item__body">
    <figure class="research-item__figure">
      <a href="/images/ukb-cost-aware-pipeline.png"><img src="/images/ukb-cost-aware-pipeline.png" alt="UK Biobank preprocessing pipeline: feature matrix construction, PCA reduction, cost mapping, and PheCode outcome alignment"></a>
    </figure>

    <div class="research-item__text">
      <p>Most prediction models assume every useful measurement is already available, but real clinical decisions come with a price: each lab test, MRI, or genetic assay must earn its cost. This project asks how <strong>multi-disease prediction</strong> can balance information gained against resources spent. My role was to build the <strong>UK Biobank</strong> data foundation for that question. I developed a preprocessing pipeline that harmonized demographic, lifestyle, clinical, environmental, genetic, and imaging data, reduced high-dimensional modalities with <strong>PCA</strong>, and constructed <strong>time-aligned PheCode outcomes</strong> from longitudinal health records. I also built a real-world <strong>feature acquisition cost benchmark</strong> by linking UK Biobank measurements to <strong>CPT/HCPCS procedures and reimbursement schedules</strong>, turning a standard prediction dataset into a cost-aware modeling resource.</p>
      <p class="research-item__links"><a href="https://pangpang12-cofamd.hf.space/">Interactive demo</a></p>
    </div>
  </div>

  <p class="research-item__tags">
    <span class="tag">UK Biobank</span>
    <span class="tag">Multimodal Integration</span>
    <span class="tag">Cost-Aware Prediction</span>
    <span class="tag">PheCodes</span>
    <span class="tag">Dimensionality Reduction</span>
  </p>
</div>

<div class="research-item">
  <h2 class="research-item__title">High-Dimensional Mediation of Social Determinants, Brain Connectivity &amp; Youth Mental Health<span class="research-item__badge">Manuscript in Preparation</span></h2>
  <p class="research-item__meta">Jan 2025 – Aug 2026 &nbsp;·&nbsp; Prof. Aiying Zhang, NeuroBioInformatics Lab, School of Data Science, University of Virginia</p>

  <div class="research-item__body">
    <figure class="research-item__figure">
      <a href="/images/abcd-sdoh-connectivity.jpg"><img src="/images/abcd-sdoh-connectivity.jpg" alt="Whole-brain connectome showing connections carrying the association between a social-determinant dimension and OCD symptoms, coloured by functional network"></a>
    </figure>

    <div class="research-item__text">
      <p>A child's neighborhood may shape mental health long before those effects appear as symptoms. One possibility is that social and environmental exposures influence the organization of brain networks, creating a neural pathway between where children grow up and how they feel.</p>
      <p>I studied this question using the <strong>ABCD cohort</strong>, combining 81 social-determinant measures, <strong>whole-brain resting-state functional connectivity</strong> across 379 regions, and psychiatric symptom data. Because both the exposure and mediator spaces were highly dimensional, I used <strong>sparse PCA</strong> to derive interpretable SDoH dimensions and <strong>high-dimensional mediation analysis</strong> to identify connectivity patterns that may carry their associations with OCD and anxiety symptoms. I also used <strong>bootstrap inference</strong> and <strong>longitudinal mixed-effects models</strong> to examine these relationships over time.</p>
    </div>
  </div>

  <p class="research-item__tags">
    <span class="tag">ABCD</span>
    <span class="tag">Social Determinants of Health</span>
    <span class="tag">rs-fMRI</span>
    <span class="tag">Sparse PCA</span>
    <span class="tag">High-Dimensional Mediation</span>
    <span class="tag">Linear Mixed-Effects Models</span>
  </p>
</div>

<div class="research-item">
  <h2 class="research-item__title">Longitudinal Modeling of Real-World Mobility, Momentary Experience and Primal World Beliefs<span class="research-item__badge">Distinguished Majors Thesis</span></h2>
  <p class="research-item__meta">Aug 2023 – May 2025 &nbsp;·&nbsp; Prof. Adrienne Wood, Emotion and Behavior Lab, University of Virginia</p>

  <div class="research-item__body">
    <figure class="research-item__figure">
      <img src="/images/explore-exploit-daily-mobility.gif" alt="Animated illustration of one person's daily mobility, alternating between familiar routes and newly visited places">
    </figure>

    <div class="research-item__text">
      <p>People move through familiar and unfamiliar places every day, but those movements are not just about geography. They may also reflect how people perceive and engage with the world around them. For example, someone who sees the world as safe may feel more comfortable exploring unfamiliar environments. My thesis examined how these <strong>primal world beliefs</strong> interact with real-world <strong>mobility patterns</strong> to shape <strong>momentary affect</strong> and <strong>activity typicality</strong>, using <strong>longitudinal geolocation data</strong>, <strong>ecological momentary assessment (EMA)</strong>, and self-reported world-belief measures.</p>
      <p class="research-item__links"><a href="/files/Li_ReidConference2025_poster.pdf">Poster (PDF)</a></p>
    </div>
  </div>

  <p class="research-item__tags">
    <span class="tag">Mobile Sensing</span>
    <span class="tag">Ecological Momentary Assessment (EMA)</span>
    <span class="tag">Longitudinal Data</span>
    <span class="tag">Mixed-Effects Models</span>
    <span class="tag">R</span>
    <span class="tag">Python</span>
  </p>

</div>
