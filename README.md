<!-- ============================================================ -->
<!-- JAI LAB — GitHub Profile README                              -->
<!-- Upload this file to: DrJoyKarmakar/DrJoyKarmakar/README.md   -->
<!-- ============================================================ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:050B18,50:102A43,100:00D4FF&text=JAI%20Lab&fontColor=FFFFFF&fontSize=72&fontAlignY=38&desc=Building%20Open%20Infrastructure%20for%20Molecular%20Discovery&descAlignY=62&descSize=20" alt="JAI Lab banner" width="100%" />
</p>

<h1 align="center">JAI Lab</h1>

<h3 align="center">
  Building Open Infrastructure for Molecular Discovery
</h3>

<p align="center">
  <strong>Benchmarks</strong> · <strong>Datasets</strong> · <strong>Scientific Software</strong> · <strong>Molecular AI</strong> · <strong>Chemical Sensors</strong> · <strong>Drug Discovery</strong>
</p>

<p align="center">
  Founded by <strong>Dr. Joy Karmakar</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=24&pause=1200&center=true&vCenter=true&width=900&lines=Open+Infrastructure+for+Molecular+Discovery;SensorGenome+%E2%80%94+AI-Driven+Molecular+Sensing;DyeMind+%E2%80%94+Fluorescent+Probe+Discovery;AZAI+%E2%80%94+Xylazine+Analytics+and+Innovation;Science+Built+on+Datasets%2C+Benchmarks%2C+and+Validation" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://joykarmakar.com"><img src="https://img.shields.io/badge/Website-joykarmakar.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://scholar.google.com/citations?user=uaIKU0oAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar" /></a>
  <a href="https://www.linkedin.com/in/joykarmakarchem"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/Joy_Karmakar"><img src="https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</p>

---

## Mission

**JAI Lab** is an open research initiative building the scientific infrastructure needed for the next generation of molecular discovery.

We develop:

- open datasets and benchmark standards,
- AI-ready experimental schemas,
- active-learning workflows,
- molecular machine-learning tools,
- reproducible scientific software,
- chemistry-first platforms for drug discovery and sensing.

The goal is simple:

> **Make molecular discovery more reproducible, data-rich, benchmarkable, and experimentally useful.**

---

## Why This Exists

Most AI chemistry projects optimize molecular structures.

But molecular discovery is broader than a molecule alone.

Real discovery depends on:

```text
molecule → experiment → assay condition → signal → selectivity → uncertainty → next experiment
```

JAI Lab focuses on the full discovery loop.

We build infrastructure where experiments are not an afterthought. They are first-class scientific objects that AI systems can learn from, reason about, and improve.

---

## Research Ecosystem

<p align="center">
  <img src="assets/svg/jai-lab-ecosystem.svg" alt="JAI Lab research ecosystem" width="100%" />
</p>

```text
                              JAI Lab
          Building Open Infrastructure for Molecular Discovery

                                  │
        ┌─────────────────────────┼─────────────────────────┐
        │                         │                         │
 Infrastructure              Molecular AI              Translation
        │                         │                         │
 SensorGenome                 DyeMind                 Drug Discovery
        │                         │                         │
   ┌────┴─────┐                   │                 ┌───────┴────────┐
   │          │                   │                 │                │
 AZAI   NarcoticSense AI       BimaneDB       Pendrin / PAT1      CFTR
```

---

## Research Programs

<table>
<tr>
<td width="50%" valign="top">

### 🧬 SensorGenome

**Open foundation for AI-driven molecular sensing.**

SensorGenome builds datasets, schemas, benchmarks, models, and active-learning workflows for discovering and evaluating chemical sensors.

Initial focus:

- fluorescent small-molecule probes,
- bimane-derived probes,
- xylazine and adulterant sensing,
- analyte/interferent selectivity,
- raw spectra and response curves,
- uncertainty-aware ML baselines,
- active-learning experiment selection.

</td>
<td width="50%" valign="top">

### 🌈 DyeMind

**Molecular AI for fluorescent probe discovery.**

DyeMind explores AI-assisted design and optimization of luminescent probes, connecting molecular structure, photophysics, sensing behavior, and experimental validation.

Focus:

- fluorescent probe ideation,
- generative molecular design,
- probe-response modeling,
- bimane chemistry,
- fluorescence and chemical biology.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 AZAI

**AI-driven xylazine analytics and innovation.**

AZAI supports computational and experimental workflows for detecting and analyzing xylazine and emerging adulterants.

Focus:

- analytical chemistry,
- sensor development,
- forensic intelligence,
- machine-learning workflows,
- experimental prioritization.

</td>
<td width="50%" valign="top">

### 🔬 NarcoticSense AI

**Chemical intelligence through spectroscopy.**

NarcoticSense AI develops open tools for spectroscopy, chemometrics, signal interpretation, and AI-assisted chemical sensing.

Focus:

- spectral analysis,
- chemometric modeling,
- sensing workflows,
- reproducible analytical pipelines.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💊 Molecular Discovery Suite

**Medicinal chemistry + molecular machine learning.**

Computational and experimental programs supporting small-molecule drug discovery, QSAR, docking, SAR, and transporter biology.

Representative targets:

- Pendrin / SLC26A4,
- PAT1 / SLC26A6,
- CFTR,
- ion transporter chemical biology.

</td>
<td width="50%" valign="top">

### 📚 Open Science Tools

**Infrastructure for researchers.**

Reusable tools for organizing papers, building datasets, validating schemas, documenting experiments, and making scientific workflows easier to reproduce.

Includes:

- BimaneDB,
- Paper Organizer,
- benchmark templates,
- dataset schemas,
- research automation.

</td>
</tr>
</table>

---

## Flagship Project: SensorGenome

> **SensorGenome treats the experiment as the atomic unit of molecular sensing.**

Sensor discovery is not simply property prediction. It requires optimizing a chain:

```text
analyte → recognition mechanism → sensor molecule → assay protocol → signal → selectivity → uncertainty → next experiment
```

### SensorGenome-Bench v0.1.0-alpha

The first milestone establishes the benchmark interface and contribution workflow with:

- Python package scaffold,
- 25 seed probe-response examples,
- schemas for sensors, analytes, assays, spectra, and responses,
- CLI for validation, baseline training, and active-learning selection,
- FastAPI skeleton,
- Docker and docker-compose,
- CI, tests, issue templates,
- release notes, roadmap, documentation, and paper outline.

### Example Commands

```bash
sensorgenome validate data/sample/probe_response_sample.csv
sensorgenome train-baseline data/sample/probe_response_sample.csv --target response_ratio --out reports/baseline_metrics.json
sensorgenome select-next data/sample/probe_response_sample.csv --k 5
uvicorn sensorgenome.api.main:app --reload
```

---

## Scientific Foundation

Dr. Joy Karmakar's work combines medicinal chemistry, synthetic organic chemistry, fluorescent probe development, chemical biology, and AI/ML-guided molecular design.

Research experience includes:

- designing small-molecule inhibitors of ion transporters,
- developing fluorescent bimane-based probes and sensors,
- SAR-driven lead optimization,
- computational chemistry and molecular modeling,
- machine learning and generative AI for chemistry,
- open-source scientific software.

---

## Selected Research Impact

<table>
<tr>
<td width="33%" valign="top">

### Medicinal Chemistry

- Pendrin inhibitors
- PAT1 inhibitors
- CFTR-related modeling
- SAR optimization
- in vivo validation

</td>
<td width="33%" valign="top">

### Fluorescent Probes

- bimane chemistry
- water sensing
- iodine sensing
- pH-sensitive probes
- chemical biology tools

</td>
<td width="33%" valign="top">

### Molecular AI

- SensorGenome
- DyeMind
- AZAI
- NarcoticSense AI
- QSAR pipelines

</td>
</tr>
</table>

---

## Publications & Research Venues

Selected work has appeared in:

- **European Journal of Medicinal Chemistry**
- **RSC Medicinal Chemistry**
- **Chemical Communications**
- **Frontiers in Chemistry**
- **Synlett**
- **Israel Journal of Chemistry**
- **Inorganica Chimica Acta**

<p align="center">
  <a href="https://scholar.google.com/citations?user=uaIKU0oAAAAJ">
    <img src="https://img.shields.io/badge/View%20Full%20Publication%20Record-Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar" />
  </a>
</p>

---

## Honors & Milestones

<table>
<tr>
<td width="50%" valign="top">

### 🏆 UCSF PBBR Postdoctoral Independent Research Award

Independent research award supporting high-risk, high-reward biomedical research on a selective fluorescent sensor for xylazine.

</td>
<td width="50%" valign="top">

### 🚀 Harvard Business School Foundry Bootcamp

Selected participant in entrepreneurship and commercialization training focused on translating scientific innovation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎓 ACS Postdoc to Faculty Workshop

Competitively selected participant in the ACS P2F program for transition toward faculty-track research careers.

</td>
<td width="50%" valign="top">

### 🔬 Sigma Xi Full Member

Inducted as Full Member of The Scientific Research Honor Society.

</td>
</tr>
</table>

---

## Research Evolution

```text
Synthetic Organic Chemistry
        ↓
Bimane Fluorescent Probes
        ↓
Chemical Biology
        ↓
Medicinal Chemistry
        ↓
Ion Transporter Drug Discovery
        ↓
Machine Learning for Chemistry
        ↓
Open Infrastructure for Molecular Discovery
        ↓
JAI Lab
```

---

## Technical Capabilities

<table>
<tr>
<td width="33%" valign="top">

### Chemistry

- Medicinal chemistry
- Synthetic organic chemistry
- SAR studies
- Fluorescent probes
- Chemical sensors
- Chemical biology

</td>
<td width="33%" valign="top">

### Computational Science

- QSAR
- Molecular docking
- Cheminformatics
- RDKit workflows
- DFT analysis
- ADMET prediction

</td>
<td width="33%" valign="top">

### AI & Software

- Python
- Machine learning
- Deep learning
- Generative AI
- FastAPI
- Docker
- GitHub Actions

</td>
</tr>
</table>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,docker,git,github,linux,vscode,aws,fastapi" alt="Technical icons" />
</p>

---

## GitHub Dashboard

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=DrJoyKarmakar&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DrJoyKarmakar&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=DrJoyKarmakar&theme=tokyo-night&hide_border=true" alt="GitHub activity graph" width="100%" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=DrJoyKarmakar&theme=tokyonight&no-frame=true&margin-w=12&column=6" alt="GitHub trophies" />
</p>

<!-- Contribution snake: requires the workflow in .github/workflows/snake.yml -->
<p align="center">
  <img src="https://raw.githubusercontent.com/DrJoyKarmakar/DrJoyKarmakar/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" width="100%" />
</p>

---

## Research Principles

<table>
<tr>
<td width="50%" valign="top">

### 1. Infrastructure Outlives Models

A single model becomes outdated. A useful dataset, schema, benchmark, or workflow can support many generations of models.

</td>
<td width="50%" valign="top">

### 2. Experiments Matter

Molecular discovery is not only about molecular structures. Conditions, protocols, selectivity, uncertainty, and validation matter.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 3. Benchmarks Need Context

A benchmark is only meaningful when the task, dataset, assumptions, and limitations are transparent.

</td>
<td width="50%" valign="top">

### 4. Open Science Accelerates Discovery

Shared datasets, tools, and standards make science faster, more reproducible, and more useful.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 5. AI Should Close the Loop

The best molecular AI systems should help choose the next experiment, not only predict the last one.

</td>
<td width="50%" valign="top">

### 6. Translation Is the Goal

Scientific software should ultimately help generate better sensors, probes, therapeutics, and biological insight.

</td>
</tr>
</table>

---

## Current Direction

JAI Lab is building toward a connected ecosystem where researchers can:

- standardize molecular sensing experiments,
- contribute reproducible datasets,
- benchmark models fairly,
- run baseline and active-learning workflows,
- design better probes and sensors,
- connect computational prediction with experimental validation.

The long-term ambition is to create open infrastructure for molecular discovery that is useful to chemists, biologists, data scientists, and translational researchers.

---

## Connect

<p align="center">
  <a href="https://joykarmakar.com"><img src="https://img.shields.io/badge/Website-joykarmakar.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="mailto:contact@joykarmakar.com"><img src="https://img.shields.io/badge/Email-contact%40joykarmakar.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/joykarmakarchem"><img src="https://img.shields.io/badge/LinkedIn-joykarmakarchem-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://x.com/Joy_Karmakar"><img src="https://img.shields.io/badge/X-Joy__Karmakar-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
</p>

---

<p align="center">
  <strong>The future of molecular discovery will be built through open science, reproducible infrastructure, and intelligent experimentation.</strong>
</p>

<p align="center">
  <em>JAI Lab — Founded by Dr. Joy Karmakar</em>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:00D4FF,100:050B18&section=footer" alt="Footer wave" width="100%" />
</p>
