# Phishing Website Detection System

## 📌 Overview
This project is a machine learning-based web application designed to detect whether a given URL is **phishing or legitimate**. It analyzes various features extracted from URLs and predicts their authenticity using trained ML models.

The goal of this project is to help users identify malicious websites and enhance online security.
---
## 🚀 Features
* 🔍 Detects phishing websites in real-time
* ⚡ Instant prediction by entering a URL
* 🤖 Multiple ML models used for high accuracy
* 🌐 User-friendly web interface
* 📊 Achieves over **95% accuracy**
---
## 🧠 Machine Learning Models Used

* Logistic Regression
* Random Forest
* Decision Tree
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* XGBoost

---

## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS, JavaScript
* **ML Libraries:** scikit-learn, XGBoost
* **Other Tools:** Pandas, NumPy
---
## ⚙️ How It Works
1. User enters a URL in the web application
2. The system extracts relevant features from the URL
3. These features are passed to the trained ML model
4. The model predicts whether the URL is **Phishing** or **Legitimate**
5. The result is displayed instantly to the user
---
## 📂 Project Structure
```
Phishing-Detection/
│── static/              # CSS, JS files
│── templates/           # HTML files
│── newmodel.pkl               # Trained ML model
│── app.py               # Main Flask application
│── feature.py# Feature engineering logic
|── Phishingproject.ipynb #Training the model with differnt ml algorithms
│── requirements.txt     # Dependencies
│── README.md            # Project documentation
```
---
## ▶️ Installation & Setup
### 1. Clone the repository
```bash
git clone https://github.com/your-username/phishing-detection.git
cd phishing-detection
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the application
```bash
python app.py
```
### 4. Open in browser
```
http://127.0.0.1:5000/
```
---
## 📊 Results
* Achieved **95%+ accuracy** using ensemble models
* Improved prediction reliability through feature engineering
---
## 🔐 Use Cases
* Detect malicious URLs before accessing them
* Enhance cybersecurity awareness
* Can be integrated into browsers or security tools
---
## 📈 Future Improvements
* Deploy as a live web application
* Integrate real-time threat intelligence APIs
* Improve model performance with deep learning
* Browser extension support
---
## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.
---
## 📬 Contact
**Nithin Reddy**
🔗 GitHub: https://github.com/Nithin136
🔗 LinkedIn: https://linkedin.com/in/nithin-reddy-path1319

---
## ⭐ If you found this project useful, give it a star!
