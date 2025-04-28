# Titanic - Machine Learning from Disaster

Welcome to my Titanic Machine Learning project!  
This project is based on the classic Kaggle competition: [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic).

The goal is to build a machine learning model that predicts whether a passenger survived the Titanic shipwreck based on features like age, sex, and class.

---

## Project Structure 
```bash
Titanic-ML/
├── data/              # Raw datasets (train.csv, test.csv)
├── notebooks/         # Jupyter notebooks
├── output/            # Submission files
├── models/            # (Optional) Saved models
├── venv/              # Python virtual environment
├── .gitignore         # Files to be ignored by Git
├── README.md          # Project overview (this file)
└── requirements.txt   # Required Python packages
```

---

## Approach 🧠

- Selected simple features: `Pclass`, `Sex`, `Age`,`fare`
- Preprocessing steps:
  - Converted `Sex` to numeric values (male → 0, female → 1)
  - Filled missing `Age` values with median
- Built and trained a Logistic Regression model using scikit-learn
- Predicted survival on the test set
- Created a Kaggle submission file



## Results 🎯

- **Validation Accuracy:** ~74.8%
- **Kaggle Public Leaderboard Score:** 0.75837



## How to Run 💻
1. Clone this repository:

   ```bash
   git clone git@github.com:lesa-hettiarachchi/Titanic-ML.git
   cd Titanic-ML
   ```
2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate     # Windows
   ```
3. Install required packages:

  	```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebooks:

   ```bash
   jupyter notebook
   ```
   
5.	Execute the notebook cells to train the model and generate submission.csv
  
6.	Upload submission.csv to Kaggle for evaluation!



## Future Work 🚀

- Add more features (Embarked, Siblings or spouses, Parents or childern)

- Handle missing data more intelligently

- Try different models (Random Forest, XGBoost)

- Hyperparameter tuning using GridSearchCV

- Apply cross-validation for better evaluation


# Acknowledgements 📝

- Kaggle Titanic Competition

- scikit-learn documentation

- pandas and numpy libraries

   
