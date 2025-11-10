# 🎬 Movie Review Sentiment Analysis (Simple RNN - IMDB Dataset)

🔍 **Predict whether a movie review is Positive or Negative using Deep Learning (Simple RNN).**

---
---

## 📌 Project Summary

This project performs **sentiment analysis** on IMDB movie reviews using a **Simple Recurrent Neural Network (RNN)** built with **TensorFlow & Keras**.  
The model learns from 50,000 labeled movie reviews and predicts whether a given review expresses **positive or negative sentiment**.

---

## 🧠 Key Features
- ✅ Converts text into embeddings
- ✅ Uses Simple RNN layer to capture sequence information
- ✅ Trained on IMDB dataset (`tensorflow.keras.datasets.imdb`)
- ✅ Deployed on Streamlit Cloud for real-time predictions


---

## 📊 Model Architecture

| Layer            | Type       | Details                     |
|------------------|------------|-----------------------------|
| Input            | Embedding  | Vocabulary size = 10,000    |
| Hidden Layer     | SimpleRNN  | 128 neurons (ReLU activation)|
| Output Layer     | Dense      | Sigmoid (0 to 1 probability) |



| Input Review | Output |
|--------------|--------|
| `"This movie was amazing! Great acting and story."` | ✅ Positive |
| `"Worst movie ever. Waste of time."` | ❌ Negative |

---

Hosted link - https://movie-review-sentiment-analysis-rnn-fk.streamlit.app/

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Language | Python |
| DL Framework | TensorFlow / Keras |
| Deployment | Streamlit |
| Dataset | IMDB Movie Reviews (50,000 reviews) |
| Preprocessing | Tokenization, Embeddings, Padding |

---

## 📦 Repository Structure

📂 Movie-review-sentiment-analysis-RNN/
│── app.py # Streamlit app
│── model/
│ └── simple_rnn_imdb.h5 # Saved model
│── training_notebook.ipynb # Jupyter notebook (model training)
│── requirements.txt # Dependencies
│── README.md # Project documentation


---

▶️ How to Run Locally

1️⃣ Clone this repository
```bash
git clone https://github.com/your-username/Movie-review-sentiment-analysis-RNN.git
cd Movie-review-sentiment-analysis-RNN

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run Streamlit
streamlit run app.py

✨ Future Enhancements

✔ Improve vocabulary coverage
✔ Add LSTM/GRU model comparison
✔ Build a UI to display sentiment score graph

📩 Contact

👤 Farhan Khan
📧 Email: fkkhan6878@gmail.com

🔗 GitHub: https://github.com/farhan1321

🔗 LinkedIn: www.linkedin.com/in/farhan-khan-bb230b243

⭐ If you like this project, please give it a star on GitHub! ⭐


