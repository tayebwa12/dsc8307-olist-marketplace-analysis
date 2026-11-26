# Olist marketplace analysis

The notebook covers data preparation, market baskets, seller segmentation, unusual-order review, and delivery prediction for DSC8307.

1. Create and activate a Python 3.14 virtual environment.
2. Install dependencies with `python -m pip install -r requirements.txt`.
3. Download the nine CSVs from the [Olist dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). Place them beside the notebook, or set `OLIST_DATA_DIR` to the directory containing them.
4. Start `python -m notebook`, open `Olist_Analysis.ipynb`, and choose **Restart Kernel and Run All Cells**.

For a command-line run, use `python -m nbconvert --to notebook --execute --inplace --ExecutePreprocessor.timeout=240 Olist_Analysis.ipynb`.
