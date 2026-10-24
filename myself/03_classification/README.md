# Chapter 3: Market direction

## Clean: `Smarket`
Create `03_clean_smarket.ipynb` here. Load the data with:
```python
import pandas as pd
smarket = pd.read_csv("https://raw.githubusercontent.com/intro-stat-learning/ISLP/main/ISLP/data/Smarket.csv")
```
Follow `03_classification.ipynb` section by section: binary → accuracy/dummy → confusion matrix → precision/recall → trade-off → ROC → multiclass → error analysis → multilabel. Finish with one evaluation on the test set.

## Messy: S&P 500 + VIX
First run `pip install arch`. Then open `03_messy_sp500_vix_preprocessing.ipynb`: run the preprocessing cells, answer the 🤔 questions, and fill in Part 2.

## When you're done
Run all cells, save, commit, push, then ask for a review.
