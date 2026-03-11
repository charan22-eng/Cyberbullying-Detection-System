# Cyberbullying Detection System

## 📌 Project Overview

The Cyberbullying Detection System is a machine learning based web application that detects cyberbullying content in user text. The system analyzes messages or posts and predicts whether the content contains abusive or harmful language.
This project helps in identifying toxic online behavior and promoting safer digital communication.

The application is built using **Python, Django, Machine Learning, and MySQL**.

---

## 🚀 Features

* Detects cyberbullying content in text
* Machine learning based prediction
* Multiple classification algorithms
* User-friendly web interface
* Dataset analysis and visualization
* Word cloud generation for abusive words
* Accuracy comparison of ML models
* Admin and user modules

---

## 🛠 Technologies Used

* Python
* Django Framework
* Machine Learning
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* WordCloud
* MySQL
* HTML / CSS / Bootstrap

---

## 📂 Project Structure

```
Cyberbullying-Detection-System
│
├── detection_of_cyberbullying
│   ├── Remote_User
│   ├── Service_Provider
│   ├── Template
│   ├── staticfiles
│   ├── manage.py
│   └── settings.py
```

---

# ⚙️ Installation and Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/charan22-eng/Cyberbullying-Detection-System.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd Cyberbullying-Detection-System
```

---

## 3️⃣ Install Required Libraries

Install all required Python packages.

```bash
pip install django
pip install pandas
pip install numpy
pip install scikit-learn
pip install matplotlib
pip install wordcloud
pip install mysqlclient
```

---

## 4️⃣ Setup MySQL Database

Open **MySQL Workbench** and run:

```sql
CREATE DATABASE detection_of_cyberbullying;
```

---

## 5️⃣ Configure Database

Open:

```
detection_of_cyberbullying/settings.py
```

Update the database section:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'detection_of_cyberbullying',
        'USER': 'root',
        'PASSWORD': 'your_password',
        'HOST': '127.0.0.1',
        'PORT': '3306',
    }
}
```

---

## 6️⃣ Run Database Migrations

```bash
python manage.py migrate
```

This will create all required database tables.

---

## 7️⃣ Start the Server

```bash
python manage.py runserver
```

---

## 8️⃣ Open the Application

Open your browser and go to:

```
http://127.0.0.1:8000/
```

---

# 📊 Machine Learning Models Used

The system evaluates multiple machine learning algorithms:

* Support Vector Machine (SVM)
* Logistic Regression
* Naive Bayes
* Random Forest

The system compares model accuracy to determine the best performing model for cyberbullying detection.

---

# 📈 System Workflow

1. User enters text message.
2. Text is preprocessed.
3. Machine learning model analyzes the text.
4. The system predicts whether the text contains cyberbullying.
5. Result is displayed to the user.

---

# 🔍 Dataset

The dataset contains social media text labeled as:

* Bullying
* Non-bullying

The dataset is used to train machine learning models for classification.

---

# 📊 Visualization

The system generates:

* WordCloud of abusive words
* Accuracy comparison charts
* Dataset analysis

---

# 🎯 Applications

* Social media moderation
* Online community monitoring
* Content filtering systems
* Digital safety platforms

---

# 👨‍💻 Author

Developed as a Machine Learning based web application project for detecting cyberbullying in online text.

---

# ⭐ Future Improvements

* Deep learning models (LSTM / BERT)
* Real-time social media integration
* API based detection service
* Multilingual cyberbullying detection
