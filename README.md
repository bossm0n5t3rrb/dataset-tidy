# dataset-tidy

Clean and split JSONL datasets for fine-tuning

## Install

```bash
# stdlib only
```

## Usage

```bash
python prep.py raw.jsonl --out-dir data/ --valid-ratio 0.1
```

## Features

- Prints a stats summary you can eyeball
- Length filters keep the sweet spot
- Deterministic split with a seed
- Dedup by normalized instruction text

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── usage.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
└── prep.py
```

## Notes

- mostly stable, edge cases remain
