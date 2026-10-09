# 📧 Email / SMS Spam Detector

A Machine Learning-powered Web Application built using **Flask** and **Scikit-Learn** that detects whether a given email or SMS message is **Spam** or **Not Spam (Ham)**.

---

## 🚀 Features

- **Machine Learning Model**: Built with `Multinomial Naive Bayes` and `CountVectorizer` for text classification.
- **Web Interface**: Clean, responsive frontend designed with HTML and CSS.
- **Input Validation**: Prevents blank inputs using both frontend (`required`) and backend Flask checks.
- **Real-time Prediction**: Instantly classifies entered text messages.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Machine Learning**: Scikit-Learn, Pandas, NumPy, Pickle
- **Frontend**: HTML5, CSS3, FontAwesome

---

## 📂 Project Structure

```text
├── static/
│   ├── styles.css
│   ├── spam-favicon.ico
│   └── images/
├── templates/
│   ├── home.html
│   └── result.html
├── app.py                  
├── spam.py                
├── model.pkl              
├── cv-transform.pkl       
├── EmailCollection.csv     
└── README.md