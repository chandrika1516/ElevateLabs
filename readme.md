# 🧠 Logistic Regression - Breast Cancer Classification

This project is a part of the AI & ML Internship Task 4: **Classification using Logistic Regression**.

## 📌 Objective
Build a binary classifier using **Logistic Regression** to predict whether a tumor is **malignant (M)** or **benign (B)** using the Breast Cancer Wisconsin dataset.

---

## 📁 Dataset

- Dataset used: **Breast Cancer Wisconsin (Diagnostic) Dataset**
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- Format: CSV with 32 columns including ID, diagnosis, and various features.

---

## 🛠 Tech Stack Used

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Matplotlib-206b8f?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Seaborn-6A5ACD?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn" />
</p>

---

## 🔍 Steps Followed

1. **Data Loading**  
   Loaded the dataset from CSV and converted the diagnosis label to binary (M → 1, B → 0).

2. **Data Preprocessing**
   - Dropped ID column
   - Feature scaling with `StandardScaler`
   - Train/test split (80/20)

3. **Model Training**
   - Used `LogisticRegression` from Scikit-learn

4. **Evaluation Metrics**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC Curve and AUC Score

5. **Threshold Tuning**
   - Demonstrated prediction change using different probability thresholds

6. **Sigmoid Function**
   - Plotted sigmoid curve to show probability mapping in logistic regression

---

## 📈 Results

| Metric            | Value         |
|------------------|---------------|
| Accuracy          | ~96%          |
| Precision         | High          |
| Recall            | High          |
| ROC-AUC Score     | ~0.99         |

> Note: Exact values depend on the random train-test split.

---

## 📊 Visuals

- Confusion Matrix  
- ROC Curve  
- Sigmoid Function Plot  

All visuals are generated using `matplotlib` and `seaborn`.

---

## 🗂 File Structure

├── data.csv # Dataset file
├── task_4.py # Python script for training & evaluation
├── README.md # This file


---

## 📝 How to Run

1. Clone this repo or download the files.
2. Make sure Python is installed with required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

# run task_4.py



---

Let me know if you'd like:
- The README customized further (e.g., with screenshots or GitHub badges).
- A version in Jupyter Notebook format.
- Help deploying it on GitHub.


🤝 Contributing
Feel free to:

🍴 Fork this repo

📢 Submit Pull Requests

⭐ Star the project if you find it helpful!

💡 References & Resources
Kaggle Titanic Tutorial

Pandas Docs

Scikit-learn Preprocessing Docs

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

Happy Learning! 🎉
(Created by Rohith S D)



🎯 ✅ *Next Steps*:
- Copy this into your README.md.

💡 Would you also like me to help you generate a requirements.txt file? Let me know!

# 💖 Thanks for checking this out!
If you find this helpful, don’t forget to give it a ⭐ on GitHub.

