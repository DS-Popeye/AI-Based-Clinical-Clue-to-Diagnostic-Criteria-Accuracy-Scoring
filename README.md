# AI Clues to Diagnostic Criteria Accuracy Scoring

Score whether extracted evidence supports explicit diagnostic criteria.

**Research-only prototype.** Synthetic records are not physician graded, and no diagnostic output is validated for clinical use.

## Quick start
```bash
python -m pip install -r requirements.txt
python src/main.py
python -m unittest discover -s tests
```

## Structure
- `data/synthetic/`: 40 synthetic example cases
- `configs/`: 20 reproducible experiment configurations
- `src/`: deterministic demonstration code and utilities
- `tests/`: unit and smoke tests
- `docs/`: protocols, governance and reviewer templates
- `schemas/`: JSON Schemas
- `reports/`: output templates

No PHI should be committed to this repository.
