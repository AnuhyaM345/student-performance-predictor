# 🎓 Student Performance Predictor

A Machine Learning powered web application that predicts a student’s final exam performance based on academic and behavioral factors such as previous grades, study time, failures, and absences.

---

### Deployed at https://student-performance-predictor-pi.vercel.app/

----

## 🚀 Features

- 🤖 ML Prediction using Random Forest Regressor  
- 🌐 Flask Web Application  
- 🎨 Modern Glassmorphism UI  
- 📊 Predicts Final Grade (G3)  
- ✅ Pass / ❌ Fail Classification  
- ⚡ Fast & Lightweight  

---

## 🧠 Machine Learning Details

| Component | Details |
|---|---|
| Model | Random Forest Regressor |
| Hyperparameter Tuning | GridSearchCV |
| Target Variable | G3 (Final Grade) |
| Metrics | R² Score, RMSE, Adjusted R² |

---

## 📂 Project Structure

student-performance-predictor/

│

├── app.py

├── train-model.py

├── predict.py

├── student_model.pkl

├── student-por.csv

├── requirements.txt

│

├── templates/

│ └── index.html

│

└── README.md



---

## 📊 Input Features

| Feature | Description |
|---|---|
| G1 | First Period Grade |
| G2 | Second Period Grade |
| absences | Number of Absences |
| failures | Past Class Failures |
| studytime | Weekly Study Time |

---

## 🎯 Output

- Predicted Final Grade (G3)  
- Pass / Fail Status  

---

## 🛠️ Tech Stack

- Python  
- Flask  
- Scikit-Learn  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- HTML + CSS  

---

## 📦 Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/AnuhyaM345/student-performance-predictor.git
cd student-performance-predictor
```

### 2️⃣ Create Virtual Environment (Recommended)
```bash
python -m venv venv
```
## Activate environment:
  ### Windows:
  ```bash
  venv\Scripts\activate
  ```
  ### Mac / Linux:
  ```bash
  source venv/bin/activate
  ```

### 3️⃣ Install Dependencies
 ```bash   
pip install -r requirements.txt
```

### 4️⃣ Run Application
```bash
python app.py
```
Open in browser: http://127.0.0.1:5000

------
### 📈 Model Training
To retrain the model:
```bash  
python train-model.py
```
This generates:
student_model.pkl

-----------

### 🔮 Example Prediction

Input:
  G1 = 12,
  G2 = 14,
  Absences = 4,
  Failures = 0,
  Study Time = 3 hrs/day,

Output:
Predicted G3 ≈ 13.6, 
Result = PASS

------
### 📚 Dataset Source
UCI Machine Learning Repository
Student Performance Dataset

------

### 🌟 Future Improvements
📱 Mobile Responsive UI

☁️ Cloud Deployment

📊 Prediction Confidence Visualisation

🧾 PDF Report Export

🤖 Explainable AI (Feature Contribution)

--------

👩‍💻 Author
------------
Anuhya Mattaparthi

CSE'26 at IFHE

ML & Full Stack Developer

------------

## If you like this project, give it a ⭐ on GitHub!
