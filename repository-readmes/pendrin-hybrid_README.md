# pendrin-hybrid

> Structure-based and ligand-based modeling of pendrin inhibitors.

[![Status](https://img.shields.io/badge/status-active-00D4FF.svg)](#roadmap)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Why this exists

Hybrid modeling can connect SAR, docking, and descriptor-based learning for transporter inhibitor discovery. This repository focuses on pendrin using structure-informed workflows.

## What this repository should contain

- docking workflow notes
- ligand-based QSAR examples
- hybrid feature ideas
- model evaluation notebooks
- reproducibility checklist

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
git clone https://github.com/drjoykarmakar/pendrin-hybrid.git
cd pendrin-hybrid
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Reproducibility

Document data source, preprocessing, package versions, random seeds, train/test split, evaluation metrics, and known limitations.

## Roadmap

- [ ] Document docking setup
- [ ] Add RDKit feature notebook
- [ ] Add hybrid model notebook
- [ ] Add limitations
- [ ] Add citation metadata

## Citation

Add a CITATION.cff file and cite related papers, datasets, or repositories.

## License

MIT unless otherwise specified.
