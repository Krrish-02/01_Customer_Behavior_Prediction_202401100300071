# 01_Customer_Behavior_Prediction_202401100300071
Classify retail customers as “bargain hunters” or “premium buyers” using a Random Forest model in Python
Customer Classification Using Random Forest
This project demonstrates how to build a machine‐learning pipeline that automatically segments customers into bargain hunters and premium buyers based on their purchase history. By leveraging three key features—total spending, average purchase value, and monthly visit frequency—we train and evaluate a Random Forest classifier to help retailers tailor promotions and improve targeting.

🔍 Key Features--->

Data Preprocessing->
     Label encoding of customer types
     Standardization of numerical features
     
Modeling ->
     Train/test split (80/20)
     Random Forest classifier for robust, ensemble-based predictions

Evaluation->
    Accuracy, precision, recall, F1‑score
    Confusion matrix heatmap for error analysis

🚀 Getting Started
Clone the repo

bash
Copy
Edit
git clone https://github.com/<your-username>/customer-classification-random-forest.git
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook
Open customer_classification.ipynb in Google Colab or Jupyter and execute each cell.

📁 Repository Contents
customer_classification.ipynb – Step‑by‑step implementation in Google Colab

customer_behavior.csv – Sample dataset of 100 customers

README.md – Project overview and instructions

📈 Results
Accuracy: ~60%

Strengths: High recall for bargain hunters

Opportunities: Improve premium buyer detection via feature engineering or balanced sampling

📚 References
scikit‑learn documentation

pandas documentation

Seaborn visualization library


![Screenshot 2025-04-22 105330](https://github.com/user-attachments/assets/f25196c0-7224-4743-b014-242cd140998a)
![Screenshot 2025-04-22 105337](https://github.com/user-attachments/assets/1a429f71-b3a0-4312-bc77-80d6ad7c73d9)




