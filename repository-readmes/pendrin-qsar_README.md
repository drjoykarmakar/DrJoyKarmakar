# pendrin-qsar

> Ligand-based QSAR modeling of pendrin inhibitors.

[![Status](https://img.shields.io/badge/status-active-00D4FF.svg)](#roadmap)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Why this exists

Pendrin is a transporter target relevant to diuretic discovery and ion transporter chemical biology. This repository organizes ligand-based modeling workflows for pendrin inhibitor datasets.

## What this repository should contain

- RDKit descriptor generation
- QSAR notebooks
- baseline models
- model evaluation notes
- limitations and applicability domain notes

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
git clone https://github.com/drjoykarmakar/pendrin-qsar.git
cd pendrin-qsar
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Reproducibility

Document data source, preprocessing, package versions, random seeds, train/test split, evaluation metrics, and known limitations.

## Roadmap

- [ ] Standardize data table
- [ ] Add scaffold split
- [ ] Add model comparison
- [ ] Add applicability domain
- [ ] Add citation metadata

## Citation

Add a CITATION.cff file and cite related papers, datasets, or repositories.

## License

MIT unless otherwise specified.
