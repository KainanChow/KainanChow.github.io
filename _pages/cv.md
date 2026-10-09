---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

- **2027** — Ph.D., Tianjin Medical University (in progress)
- **2022** — Master's degree, Nantong University
- **2018** — Bachelor's degree, Nanjing Medical University

## Research Experience

- **2023** — Research Assistant, Fudan University

## Technical Skills

- **Molecular biology:** DNA/RNA extraction, RT-PCR, Western blotting, co-immunoprecipitation, and plasmid isolation.
- **Histology and imaging:** Paraffin and frozen sectioning, H&E staining, immunohistochemistry, and immunofluorescence.
- **Cell biology:** Endothelial and tumor cell culture; lentiviral overexpression and CRISPR–Cas9-based cell-line engineering; tube formation, migration, proliferation, apoptosis, and cell-cycle assays.
- **Neurobiology:** Mouse EEG, EMG, and calcium-signal recording.
- **Animal experiments:** Mouse retinal dissection and retinal vascular immunofluorescence, corneal angiogenesis, and Matrigel plug assays.
- **Data analysis:** MATLAB, ImageJ, and GraphPad.

## Awards and Scholarships

- **2024, 2025, 2026** — Graduate Academic Scholarship, Tianjin Medical University.
- **2020–2021, 2021–2022** — Third-Class Postgraduate Scholarship, Nantong University.
- **2019–2020** — First-Year Postgraduate Academic Scholarship, Nantong University.
- **2015–2016, 2016–2017, 2017–2018** — Outstanding Student Scholarship — Individual Award, Nanjing Medical University.

## Publications

<ul>
{% for post in site.publications reversed %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>. <em>{{ post.venue | escape }}</em>, {{ post.date | date: "%Y" }}.</li>
{% endfor %}
</ul>
