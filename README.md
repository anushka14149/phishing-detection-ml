# 🔐 Phishing Website Detection using Machine Learning

This project uses a **Random Forest Classifier** to detect phishing websites using 12+ behavioral features.

---

## 📁 Dataset

- `phishing_dataset_sample.csv`
- Based on the UCI Phishing Websites Dataset

---

## 🧠 Features Used

- Presence of IP address
- Length of the URL
- Use of shortening services
- Use of '@' symbol
- Redirection in URL (`//`)
- SSL certificate validity
- Domain registration length
- Favicon consistency
- Open ports
- HTTPS token in the domain
- Website traffic
- ...and more

---

## 💻 Tech Stack

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

---

## ⚙️ How to Run

### ▶️ On Google Colab

1. Upload the dataset using:
```python
from google.colab import files
files.upload()
