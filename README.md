# BT4012 GitHub Submission

## Data setup

The dataset is not included in this repository. Download it from the Kaggle
competition page and place the files in a folder named `data/` located
**next to** this repository folder (in its parent directory):

```
parent-folder/
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── txs_edgelist.csv
│   └── sample_submission.csv
└── BT4012-GitHub-Submission/
    └── e1249190.ipynb
```

The notebook reads the files using the relative path `../data`.

## How to run

1. Use Python 3.13.16.
2. Create a virtual environment and install the dependencies:
```bash
   python -m venv .venv
   source .venv/bin/activate      # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
```
3. Place the data files as described above.
4. Open `e1249190.ipynb` and run all cells from top to bottom.