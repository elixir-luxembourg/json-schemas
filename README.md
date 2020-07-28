# ELIXIR-LU json schemas

This repository stores JSON schemas used for validation of data by ELIXIR-LU tools.

## Structure

```bash
.
├── elixir-lu-json-schemas              # folder with schemas
│   └── ...
├── README.md
├── setup.py
└── tests                               # folder with tests validating schemas
    ├── data                            # folder with testing datasets
    └── ...

```

# Running tests

1. create Python virtual environment and activate
   ```bash
   python3 -m virtualenv venv
   source venv/bin/activate
   ```
2. install dependencies
   ```
   pip install .
   ```
3. call tests
   ```
   python -m unittest
   ```
