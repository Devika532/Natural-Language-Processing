# Natural-Language-Processing
# Offensive Language Detection using Machine Learning (7120CEM CW1)

## 📘 Project Overview
This project identifies offensive tweets using the **OffensEval 2019** dataset.  
Three models were tested: **Logistic Regression**, **Linear SVM**, and **RBF SVM** (with hyperparameter tuning).  
The tuned RBF SVM achieved the best results with an overall accuracy of 75% and a macro F1 score of 0.69.

## 🧩 Dataset
The English subset of the OffensEval 2019 dataset was used.  
You can access it from the official repository:  
[https://sites.google.com/site/offensevalsharedtask/](https://sites.google.com/site/offensevalsharedtask/)

## ⚙️ Methodology Summary
1. Data preprocessing – removing URLs, mentions, emojis, and symbols.  
2. TF-IDF feature extraction with unigrams and bigrams.  
3. Model training using Logistic Regression, Linear SVM, and RBF SVM.  
4. Hyperparameter tuning via GridSearchCV for optimal C and gamma values.  
5. Evaluation using F1-score, precision, recall, and confusion matrices.  

## 🧠 Results
- Best model: **Tuned RBF SVM**
- Accuracy: **0.75**
- Macro F1: **0.69**
- Best parameters: `C=10`, `gamma=0.1`

Visuals:
- Confusion matrix (RBF SVM)
- Learning curve

## 🧾 Dependencies
Install dependencies with:


## 🧪 How to Run
1. Open the notebook `CW1_Offensive_Language_Detection.ipynb` in Google Colab.
2. Upload the dataset file `offenseval-training-v1.tsv` to the `data/` folder.
3. Run each cell sequentially.
4. Results and plots will be saved to the `results/` folder.

## 👩‍💻 Author
**Devika Giriyappa**  
MSc Data Science and Computational Intelligence  
Coventry University (Module 7120CEM)
