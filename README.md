##  Project Structure

```text
airport-congestion-prediction-ml-dl/
│
├── data/
│   ├── raw/              # raw dataset (Kaggle source data)
│   ├── processed/        # cleaned dataset + engineered features
│
├── notebooks/
│   ├── EDA.ipynb         # exploratory data analysis
│   ├── ML.ipynb          # machine learning models
│   ├── DL.ipynb          # deep learning models
│
├── src/
│   ├── preprocessing.py  # data cleaning and preprocessing
│   ├── features.py       # feature engineering
│   ├── train_ml.py       # ML model training
│   ├── train_dl.py       # DL model training
│   ├── evaluate.py       # evaluation metrics (MAE, RMSE)
│
├── outputs/
│   ├── models/           # saved trained models
│   ├── figures/          # graphs and visualizations
│   ├── metrics/          # evaluation results
│
├── pipeline.py           # end-to-end automated pipeline
├── requirements.txt      # project dependencies
├── report.pdf            # technical report (15–20 pages)
├── presentation.pptx     # final presentation slides
