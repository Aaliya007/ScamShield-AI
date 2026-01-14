# ScamShield-AI
A Fake News Detector that also predicts Financial Scams. 
<br>
USER INTERFACE:
<img width="1043" height="818" alt="image" src="https://github.com/user-attachments/assets/095ce063-de70-480e-9a0c-ec9f5282834e" />

Prediction: REAL or FAKE
<br>
Probability bar visualization
<br>
Adjustable fake-detection threshold
<br>
<br>
## Project Structure

```
fake-news-detector/
│
├── data/
│   ├── fake.csv       # Fake news
│   ├── true.csv        # Verified news       
│
├── src/
│   ├── streamlit_app.py        # Streamlit user interface
│   ├── detect_fake_news.py     # Prediction logic
│   ├── train_model.py          # Model training script
│   ├── text_clean.py           # Text preprocessing & cleaning
│   └── utils.py                # Helper functions
│
├── output/
 ├── text_clean.py   
│
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation
└── .gitignore
```

---

## 🔧 Installation

### Clone the Repository
```bash
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

Or install manually:
```bash
pip install pandas numpy scikit-learn matplotlib streamlit joblib
```

---

## Running the Streamlit App

### Launch the App
```bash
streamlit run src/streamlit_app.py
```

Then open the local web interface:
```
http://localhost:8501
```
## Technologies Used

- **Python 3.10+**
- **scikit-learn** → TF-IDF Vectorizer, Logistic Regression  
- **pandas / numpy** → Data manipulation  
- **matplotlib** → Model visualization  
- **joblib** → Model persistence  
- **Streamlit** → Web interface

  
## Future Improvements 


- Integrate real-time news scraping from trusted financial news sources.
- Enhance detection accuracy using advanced NLP models like LSTM, BERT, or Transformer-based architectures.
- Add scam keyword highlighting to explain why a news article is classified as fake.
- Implement multilingual support to detect financial scams in regional languages.
- Introduce user feedback to improve model performance over time.
- Deploy the application on cloud platforms such as Streamlit Cloud or AWS.
- Add API support for integration with external applications and browsers.
- Include sentiment analysis to strengthen scam detection.
- Create a browser extension for real-time financial scam alerts.
---


