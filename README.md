# ShopSmart - E-Commerce Purchase Prediction
Predicts whether a visitor will purchase a product using browsing behavior for targeted marketing.

### Dataset
Kaggle - Online Shoppers Purchasing Intention Dataset (12,330 sessions) Link: https://www.kaggle.com/datasets/uciml/online-shoppers-purchasing-intention-dataset
Note: Dataset not included in repo. Download file `online_shoppers_intention.csv` from Kaggle link above.

### Models Used
- Decision Tree Classifier
- Pruning Technique (ccp_alpha)

### Steps Done
- Data Cleaning
- EDA with Matplotlib, Seaborn
- Feature Engineering & Encoding (VisitorType, Weekend, Month)
- Handled Imbalanced Data
- Model Training & Evaluation (F1-Score, Precision, Recall, Confusion Matrix)
- Overfitting Control using max_depth & Pruning

### Tech Stack
Python, Pandas, Numpy, Scikit-Learn, Anaconda, Jupyter Notebook

### How to Run
1. Download dataset from: https://www.kaggle.com/datasets/uciml/online-shoppers-purchasing-intention-dataset
2. Place `online_shoppers_intention.csv` in same folder as notebook
3. Install requirements: `pip install pandas scikit-learn matplotlib seaborn`
4. Run `shopsmart_ecommerce_prediction.ipynb` in Jupyter Notebook or VS Code

### Author
Arati Likitha
