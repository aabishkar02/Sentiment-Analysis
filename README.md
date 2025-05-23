# ✨ Sentiment Analysis Web App

A modern, user-friendly web application for sentiment analysis built with Flask and VADER Sentiment. This application provides real-time sentiment analysis with a beautiful, responsive interface and intuitive emoji-based feedback.


## 🌟 Features

- **Real-time Sentiment Analysis**: Instantly analyze the sentiment of any text input
- **Modern UI/UX**: Clean, responsive design with intuitive user interface
- **Emoji-based Feedback**: Visual sentiment indicators using emojis
- **Detailed Metrics**: Comprehensive sentiment breakdown including:
  - Positive score
  - Neutral score
  - Negative score
  - Compound score
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🛠️ Technologies Used

- **Backend**:
  - Flask (Web Framework)
  - VADER Sentiment (Sentiment Analysis)
  - NLTK (Natural Language Processing)
  - Scikit-learn (Machine Learning)
  - Python 3.x

- **Frontend**:
  - HTML5
  - CSS3 (Modern styling with CSS variables)
  - Google Fonts (Poppins)
  - Responsive Design

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Sentiment-Analysis-ML-Flask-App.git
cd Sentiment-Analysis-ML-Flask-App
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

The application will be available at `http://127.0.0.1:5002`

## 🎯 How It Works

### VADER Sentiment Analysis
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool specifically attuned to sentiments expressed in social media. It works well on texts from various domains and provides:

- Sentiment polarity scores (positive, negative, neutral)
- Compound score for overall sentiment
- Special handling for social media text, including:
  - Emoticons
  - Acronyms
  - Slang
  - Punctuation

### Sentiment Scoring
The application provides a comprehensive sentiment analysis with:

- **Overall Sentiment**: Displayed with intuitive emojis
  - 😊 Very Positive (≥80%)
  - 🙂 Positive (≥60%)
  - 😐 Neutral (≥40%)
  - 🙁 Negative (≥20%)
  - 😢 Very Negative (<20%)

- **Detailed Metrics**: Individual scores for:
  - Positive sentiment
  - Neutral sentiment
  - Negative sentiment
  - Compound score

## 💡 Use Cases

- **Social Media Monitoring**: Analyze public sentiment on social media platforms
- **Customer Feedback**: Process and analyze customer reviews and feedback
- **Market Research**: Understand public opinion about products or services
- **Content Analysis**: Evaluate the sentiment of articles, blogs, or comments
- **Academic Research**: Study sentiment patterns in text data

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- VADER Sentiment for the powerful sentiment analysis tool
- Flask for the web framework
- NLTK for natural language processing capabilities


