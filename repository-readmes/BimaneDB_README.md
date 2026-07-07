# BimaneDB

> Open bimane fluorescent dye database and QSAR workspace.

[![Status](https://img.shields.io/badge/status-active-00D4FF.svg)](#roadmap)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Why this exists

Bimane chemistry has rich fluorescent sensing potential, but the data is fragmented. BimaneDB aims to make bimane structures, properties, and sensing annotations reusable for AI-assisted probe discovery.

## What this repository should contain

- curated bimane entries
- SMILES and descriptor workflows
- preliminary QSAR notebooks
- data dictionary
- publication links

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
git clone https://github.com/drjoykarmakar/BimaneDB.git
cd BimaneDB
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Reproducibility

Document data source, preprocessing, package versions, random seeds, train/test split, evaluation metrics, and known limitations.

## Roadmap

- [ ] Clean molecule identifiers
- [ ] Add descriptor generation script
- [ ] Add dataset card
- [ ] Add baseline QSAR notebook
- [ ] Link related bimane papers

## Citation

Add a CITATION.cff file and cite related papers, datasets, or repositories.

## License

MIT unless otherwise specified.
