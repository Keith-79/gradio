# SVM-Based Sentiment Analysis with Gradio Demo

This project implements a Sentiment Analysis system using Support Vector Machines (SVM) integrated with a Gradio UI for real-time user interaction.  
It demonstrates how a traditional ML model can be wrapped into an interactive web interface for text-based sentiment prediction and interpretability.

---

## ⚙️ Environment Setup

```bash
python -m venv venv
source venv/bin/activate   # (Mac/Linux)
venv\Scripts\activate      # (Windows)
pip install -r requirements.txt
```
Train the model using the default dataset:
```
python sentiment_training.py
```
Launch the interactive UI for sentiment prediction:
```
python sentiment_app.py
```
You can enter text and view:

The predicted sentiment (Positive / Negative / Neutral)

Token-level importance visualization

Model confidence score

Run Tests
```
pytest tests/test_sentiment.py -v
```
