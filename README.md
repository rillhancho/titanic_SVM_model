# 🚢 Titanic Survival Prediction

This project analyzes passenger data from the Titanic disaster to uncover survival patterns and build a machine learning model that predicts survival outcomes.

---

## 📁 Dataset

The dataset includes:

- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Age`: Age of the passenger
- `Sex`: Converted into `male` and `female` binary columns
- `Survived`: Target variable (0 = Did not survive, 1 = Survived)

---

## 🔧 Requirements

Install dependencies using pip:


---

## 🚀 How to Run

1. Clone the repository or download the notebook/script.
2. Open and run the code in a Jupyter Notebook or Python IDE.
3. Follow the steps: Data Preprocessing → EDA → Model Training → Prediction.

---

## 📊 Visualizations

### 🔹 Survival by Gender



Females had a significantly higher survival rate compared to males.

---

### 🔹 Survival by Embarkation Port



Cherbourg passengers had a higher proportional survival rate.

---

### 🔹 Survival by Passenger Class



1st class passengers had the best survival odds, while 3rd class suffered the highest casualties.

---

## 🤖 Model Training

We used a Support Vector Machine (SVM) classifier:



