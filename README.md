📘 NLP News Article Classifier

An end-to-end News Article Classification App built using Natural Language Processing (NLP) and Machine Learning.
The app takes a news article as input and predicts its category (e.g., politics, sports, technology, entertainment, etc.).

🚀 Features

📰 Classifies News Articles into relevant categories.

⚡ TF-IDF Vectorization for feature extraction.

🤖 Machine Learning Model (e.g., Logistic Regression / Naive Bayes).

🎨 Interactive UI powered by Streamlit.

☁️ Deployed on Streamlit Cloud for public access.

📂 Project Structure
NLP-News-Classification-main/
│
├── app.py                  # Streamlit app file
├── news_classifier.pkl     # Trained ML model
├── vectorizer.pkl          # Saved TF-IDF vectorizer
├── requirements.txt        # Dependencies
├── README.md               # Project Documentation
└── dataset/                # (Optional) News dataset used for training

🛠️ Tech Stack

Language: Python 🐍

Libraries: scikit-learn, pandas, numpy, joblib, streamlit, spaCy

Modeling: TF-IDF + Machine Learning Classifier

Deployment: Streamlit Cloud

📊 How It Works

Input a news article in the text box.

The article is preprocessed and transformed using TF-IDF Vectorizer.

The trained Machine Learning model predicts the most relevant category.

Result is displayed instantly in the app.

⚙️ Installation & Setup (Local)

Clone the repository and run the app locally:

# Clone repo
git clone https://github.com/HARSHIT071004/NLP-News-Classification-main.git
cd NLP-News-Classification-main

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py

🌐 Deployment (Streamlit Cloud)

Push code + model (.pkl) to GitHub.

Go to Streamlit Cloud
.

Deploy repo → Select app.py as the main file.

📚 Future Enhancements

🔹 Support multi-label classification (articles with multiple topics).

🔹 Add more categories and a larger dataset.

🔹 Deploy as a full-fledged REST API.

🔹 Improve preprocessing with advanced NLP models (e.g., BERT).

👤 Author

Harshit Sharma
