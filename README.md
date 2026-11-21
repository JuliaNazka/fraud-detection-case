# Fraud Detection Case

Machine learning solution to flag potentially fraudulent card transactions,
built for the Artefact Data Science case.

## Data

The case data is not versioned. Place the two files provided by Artefact in `data/`:

- `data/transacoes_historico_2025.csv` (labelled history, 2025)
- `data/transacoes_jan2026.csv` (January 2026, to be classified)

## Setup

    python -m venv .venv
    .venv\Scripts\activate
    pip install -r requirements.txt
    jupyter notebook notebooks/
