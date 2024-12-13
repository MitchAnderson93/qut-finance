# qut-finance 

### Steps to setup:
- Requires Python3/pip to run (install both)
- ```python3 -m venv env``` to initialise a local env
- ```source env/bin/activate``` to activate local dev environment (for installing pip packages)
- ```pip install -r requirements.txt``` to install dependencies 
- ```jupyter notebook``` to run

### This repository:
``` 
├── env/                    # Not committed.
├── data/
│   ├── raw/                # Raw datasets (CSV/JSON)
│   ├── processed/          # Cleaned datasets
├── library/
│   ├── fetch_data.py       # Data collection scripts
│   ├── clean_data.py       # Data cleaning and preprocessing
│   ├── fundamental_analysis.py
│   ├── technical_analysis.py
│   ├── risk_analysis.py
│   ├── valuation.py
│   ├── visualization.py
│   ├── generate_report.py
├── tests/                  # Unit tests for scripts
├── requirements.txt        # Dependencies
├── README.md               # Project overview and usage instructions
```