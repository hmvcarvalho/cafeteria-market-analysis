# cafeteria-market-analysis

Market analysis of Los Angeles restaurants to understand if a robot-staffed cafeteria can succeed long-term.

## Project Structure

```
cafeteria-market-analysiss/
├── data/
│   └── hrest_data_us_upd.csv       # LA Restaurants data
├── notebooks/
│   ├── 01_Data_Preparation.ipynb    # Data validation and preparation
│   └── 02_EDA      # Exploratory data Analysis
├── .gitignore
├── README.md
└── requirements.txt
```

## Key Dependencies

| Library | Version | Purpose |
|---|---|---|
| pandas | 3.0.3 | Data manipulation and analysis |
| numpy | 2.4.6 | Numerical computing |
| matplotlib | 3.10.9 | Data visualization |
| seaborn | 0.13.2 | Statistical data visualization |
| jupyter / notebook | 1.1.1 / 7.5.7 | Inte

## Setup

### 1. Create and activate the virtual environment

**Windows (PowerShell):**
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**macOS / Linux:**
```bash
python -m venv .venv
source .venv/bin/activate
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open the notebooks inside the `notebooks/` folder in the order indicated by their prefix numbers.