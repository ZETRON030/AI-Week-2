# AI-Week-2


---

AI for Sustainable Agriculture – Crop Failure Prediction

This project applies machine learning to help address Sustainable Development Goal (SDG) 2: Zero Hunger by predicting the likelihood of crop failure using environmental factors. Using a Random Forest classifier, this notebook identifies patterns that could lead to crop failure, enabling smarter agricultural decisions.


---

Dataset

File: Crop_recommendation.csv

Features:

N (Nitrogen), P (Phosphorous), K (Potassium)

temperature (°C)

humidity (%)

ph (soil pH level)

rainfall (mm)

label (crop type – not used in failure prediction)


Target (engineered): failure (1 = likely crop failure, 0 = healthy crop)


Failure is simulated based on:

Rainfall < 60 mm

pH < 5.5

Humidity < 45%



---

Model Overview

Model Used

Algorithm: RandomForestClassifier (from Scikit-learn)

Preprocessing: StandardScaler for feature normalization

Train/Test Split: 80/20


Metrics

Achieved perfect classification:

Accuracy: 1.00

Precision: 1.00

Recall: 1.00

F1-score: 1.00


A confusion matrix was generated to confirm the classifier's reliability.


---

Results

The model achieved 100% accuracy on both training and testing datasets.

No evidence of overfitting was observed, as test and train scores were identical.



---

Key Insight

By simulating crop failure conditions and training an ML model to classify them, farmers or agricultural policymakers can proactively identify high-risk conditions, enabling better planning, irrigation, and soil treatment to prevent yield loss.


---

How to Run

1. Clone this repo:

git clone https://github.com/Papi1997/AI-Week-2.git
cd AI-Week-2


2. Install dependencies:

pip install pandas scikit-learn matplotlib seaborn


3. Run the notebook: Week 2 AI.ipynb in Jupyter Notebook or Google Colab.




---

License

This project is for educational purposes under the AI for Sustainable Development program

Group Members/contributers
1.Albert Sipoi[albsipoi1564@gmail.com] 0703126498
2.
3.
