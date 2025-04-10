# Assignment-Decision-Trees
this is the dataset of heeart desease where i have wroked on predicting if a person has a heart desease or not based on various health indicators such as age, cholesterol, chest pain type, blood pressure, and more.if yes,then at what is the severity of that heart ailment.I have used Decision Tree model here.
🧠 Dataset
The dataset contains 14 attributes including:

age, sex, cp (chest pain type), trestbps (resting blood pressure), chol (serum cholesterol), thalach (max heart rate), and others.

target: Initially a multiclass variable (0–4) indicating severity of disease, but can also be simplified to binary classification (0 = no disease, 1 = disease present).

🛠️ Methods Used
Data Preprocessing:

Handling null values

Label encoding of categorical features

Splitting target into binary vs multiclass formats

Modeling:

Decision Tree Classifier

Train-test split using train_test_split

Accuracy comparison across multiple random states

Evaluation:

Accuracy Score

Training vs Testing accuracy average

Understanding impact of data splits

📊 Key Learnings
How random state affects model performance.

The difference between binary and multiclass classification in medical datasets.

Importance of data preprocessing and proper feature treatment in building robust models.

🔮 Possible Improvements
Try other classifiers (e.g., Random Forest, XGBoost)

Tune hyperparameters using GridSearchCV

Perform cross-validation for more robust accuracy

Add visualizations for decision tree structure and feature importances

📌 How to Run
Clone this repo.

Open the notebook in Jupyter or Google Colab.

Run all cells in order.

Modify the classification logic for binary/multiclass prediction as needed.

📬 Contact
For any questions or collaboration, feel free to connect via LinkedIn {www.linkedin.com/in/nabeeha-nousheen

} or drop a message!
