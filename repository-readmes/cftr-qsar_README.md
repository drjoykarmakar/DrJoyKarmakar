# cftr-qsar

> QSAR modeling of CFTR potentiators using RDKit and ML.

[![Status](https://img.shields.io/badge/status-active-00D4FF.svg)](#roadmap)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Why this exists

CFTR potentiator datasets provide an opportunity to practice transparent ligand-based modeling and drug discovery workflows.

## What this repository should contain

- RDKit descriptor workflow
- baseline ML models
- notebooks
- model evaluation notes
- data limitations

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
git clone https://github.com/drjoykarmakar/cftr-qsar.git
cd cftr-qsar
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Reproducibility

Document data source, preprocessing, package versions, random seeds, train/test split, evaluation metrics, and known limitations.

## Roadmap

- [ ] Add dataset card
- [ ] Add reproducible environment
- [ ] Add baseline model table
- [ ] Add train/test split notes
- [ ] Add citation

## Citation

Add a CITATION.cff file and cite related papers, datasets, or repositories.

## License

MIT unless otherwise specified.
