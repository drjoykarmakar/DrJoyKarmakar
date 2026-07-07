# Molecular Discovery Suite

> QSAR, docking, SAR, and ADMET workflows for transporter biology.

[![Status](https://img.shields.io/badge/status-active-00D4FF.svg)](#roadmap)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Why this exists

Medicinal chemistry projects benefit from standardized computational notebooks that connect SAR, docking, descriptors, ADMET, and experimental validation.

## What this repository should contain

- QSAR templates
- docking templates
- SAR tables
- ADMET workflow notes
- transporter biology project map

## Recommended structure

```text
.
├── README.md
├── data/
├── notebooks/
├── src/
├── examples/
├── docs/
├── CITATION.cff
├── LICENSE
└── requirements.txt
```

## Quickstart

```bash
git clone https://github.com/drjoykarmakar/Molecular-Discovery-Suite.git
cd Molecular-Discovery-Suite
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Reproducibility

Document data source, preprocessing, package versions, random seeds, train/test split, evaluation metrics, and known limitations.

## Roadmap

- [ ] Create shared notebook template
- [ ] Add standardized data schema
- [ ] Add model card template
- [ ] Add example transporter project
- [ ] Link to pendrin and CFTR repos

## Citation

Add a CITATION.cff file and cite related papers, datasets, or repositories.

## License

MIT unless otherwise specified.
