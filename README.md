# ML_ALL_SVM_RF_NN

Machine-learning notebook comparing three model families — **SVM**, **Random Forest**,
and a **Neural Network (MLP)** — on a protein–DNA binding-affinity dataset.
Hyperparameters are tuned with `hyperopt`. Built and tested on **Python 3.11**.

## Contents

```
.
├── ML_ALL_SVM_RF_NN.ipynb        # the notebook
├── requirements.txt              # Python dependencies
├── README.md
└── ML-Protein-DNA-Binding-Affinity/
    └── tutorial notebooks/
        └── Data/
            ├── rawdat.csv        # per-frame energy features
            └── exp_data_all.csv  # one label per sequence
```

> **Important:** the notebook reads its data from
> `ML-Protein-DNA-Binding-Affinity/tutorial notebooks/Data/`.
> The two CSV files must be present at that path (or edit the `DATA_DIR`
> variable near the top of the notebook to point elsewhere).

## Run it locally

Requires Python 3.11.

```bash
git clone https://github.com/WallaceCYWong/ML_ALL_SVM_RF_NN.git
cd ML_ALL_SVM_RF_NN

python3 -m venv venv
source venv/bin/activate          # Windows: venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook ML_ALL_SVM_RF_NN.ipynb
```

Then run the cells top to bottom.

## Run it in the browser (no install)

Open in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/WallaceCYWong/ML_ALL_SVM_RF_NN/blob/main/ML_ALL_SVM_RF_NN.ipynb)


