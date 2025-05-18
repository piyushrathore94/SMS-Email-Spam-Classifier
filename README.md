---

# 📩 SMS-EMAIL Spam Classifier

This project is a simple and effective **Spam Classifier** for SMS and Email messages using **Natural Language Processing (NLP)** and **Machine Learning (ML)**. It uses a Multinomial Naive Bayes model trained on preprocessed message data and provides predictions via a clean and responsive **Streamlit** web app.

---

## 🧠 How It Works

1. **Data Preprocessing**:
   - Convert text to lowercase
   - Remove punctuation and stopwords
   - Tokenize and stem words

2. **Feature Extraction**:
   - TF-IDF Vectorization is used to convert text into numerical features.

3. **Model Training**:
   - Trained using the **Multinomial Naive Bayes** algorithm, a common choice for text classification tasks.

4. **Web Interface**:
   - Developed using **Streamlit** for real-time predictions and interaction.

---

## 🖼️ Demo

Run the app locally using the instructions below and test out your own SMS or Email messages!

---

## 🛠️ Installation & Setup

```1. **Clone the repository**:
   bash
   git clone https://github.com/Kanishk00551/SMS-EMAIL_Spam-Classifier.git
   cd SMS-EMAIL_Spam-Classifier


2. **Create a virtual environment (optional but recommended)**:

   ~~~bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
 

3. **Install the dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**:

   ```bash
   streamlit run app.py
   ```

---

## 📁 Project Structure

```
SMS-EMAIL_Spam-Classifier/
│
├── app.py                  # Streamlit web app
├── model.pkl               # Trained Naive Bayes model
├── vectorizer.pkl          # Fitted TF-IDF Vectorizer
├── spam.csv                # Dataset used
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## ✅ Requirements

* Python 3.7+
* scikit-learn
* pandas
* nltk
* streamlit

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset

* The dataset used is a collection of SMS/Email messages labeled as **spam** or **ham**.
* You can find it in the `spam.csv` file.

---

## ✨ Features

* Real-time spam detection
* Clean user interface
* Lightweight and fast
* Fully open-source

---

## 📌 Future Improvements

* Add support for additional classification models
* Improve preprocessing with lemmatization
* Deploy the app online via Streamlit Cloud or Render

---

## 🤝 Contributing

Pull requests are welcome! If you'd like to improve something, feel free to fork the repo and submit a PR.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---


![image](https://github.com/user-attachments/assets/b30f08dc-fa4c-40de-9961-e8f3e788f5ba)
![image](https://github.com/user-attachments/assets/a4dbe209-4979-4bc6-966c-48d3307608cf)
