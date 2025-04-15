# 📩 Spam Message Detection

A web application built using **Django** and **Machine Learning** to detect whether an SMS message is spam or not. This lightweight, open-source project demonstrates the power of text classification using a Naive Bayes model and CountVectorizer, ideal for beginners and developers exploring NLP.

## 🚀 Features of the project

- 🔍 Classifies user-inputted text messages as **Spam** or **Not Spam**
- ⚙️ Integrated ML model with Django backend
- 🌐 Simple and responsive frontend interface
- 🧠 Trained using CountVectorizer + Naive Bayes
- 🗃️ Open-source project hosted on GitHub

## 🛠️ Tech Stack Detaila 

- **Frontend:** HTML, CSS, Bootstrap (optional)
- **Backend:** Django (Python)
- **ML/NLP:** Scikit-learn, CountVectorizer, Naive Bayes
- **Version Control:** Git & GitHub

## 📂 Project Structure

Spam-Message-Detection/
├── manage.py
├── spamdetect/         # Django app
│   ├── views.py
│   ├── models.py
│   ├── templates/
│   │   ├── home.html
│   └── ...
├── static/             # CSS/JS files
├── templates/          # Base templates
└── requirements.txt

## 📦 Installation & Setup Steps

1. Clone the Repository

git clone https://github.com/saeehudli/Spam-Message-Detection.git
cd Spam-Message-Detection

2. Create Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install Dependencies

pip install -r requirements.txt

4. Run the Project

python manage.py runserver

Then open your browser and visit:  
👉 http://127.0.0.1:8000/

## 📈 Model Overview

- **Text Vectorization:** CountVectorizer (bag of words model)
- **Classifier:** Multinomial Naive Bayes
- **Dataset:** Preprocessed SMS spam collection dataset
- **Accuracy:** ~98% on validation set

## 🧪 Example Input & Output

- Input: “Congratulations! You've won a free iPhone. Call now!”  
  Output: **SPAM**

- Input: “Hey, are we still meeting for lunch today?”  
  Output: **NOT SPAM**

## 🐛 Known Issues / To Do

- [ ] Add user authentication
- [ ] Improve UI with React or modern frontend
- [ ] Add option to upload .txt files or message datasets
- [ ] Deploy to cloud (Heroku/Vercel/DigitalOcean)

## 🤝 Contributing

Contributions are welcome! Follow the steps:

1. Fork this repo
2. Create a feature branch `git checkout -b feature-x`
3. Commit changes: `git commit -m "Add feature"`
4. Push to branch: `git push origin feature-x`
5. Open a Pull Request

## 👩‍💻 Developed By

**Saee Hudli & SujayPunekar** 
GitHub: [@saeehudli](https://github.com/saeehudli)
GitHub:[@sujaypunekar](https://github.com/sujaypunekar592004)


## ⭐️ Show Your Support

If you like this project, give it a ⭐️ on GitHub!  
Your support motivates me to improve it further 💙
