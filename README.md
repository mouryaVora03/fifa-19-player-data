# FIFA 19 Complete Player Dataset Analysis

Exploratory Data Analysis (EDA) and insights on the FIFA 19 Complete Player Dataset from Kaggle.

## Project Structure

```text
├── README.md
├── requirements.txt
├── .gitignore
├── data/                                         # Dataset instructions & local CSVs (git-ignored)
├── notebooks/
│   └── fifa-19-complete-player-dataset.ipynb     # Jupyter analysis notebook
└── images/                                       # Exported plots & charts
```

## Getting Started

### 1. Clone & Set Up Environment
```bash
python -m venv .venv
# On Windows:
.venv\Scripts\activate
# On Linux/macOS:
source .venv/bin/activate

pip install -r requirements.txt
```

### 2. Download the Dataset
1. Visit the [Kaggle FIFA 19 Dataset](https://www.kaggle.com/datasets/karangadiya/fifa19).
2. Download and place `data.csv` inside the `data/` folder.

### 3. Run the Notebook
Launch Jupyter Notebook or JupyterLab:
```bash
jupyter notebook notebooks/fifa-19-complete-player-dataset.ipynb
```
