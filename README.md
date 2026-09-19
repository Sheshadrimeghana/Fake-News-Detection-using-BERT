# Fake News Detection Using RoBERTa

## Project Overview:

Fake news is misleading or false information presented as news. 
This project uses Natural Language Processing (NLP) and the RoBERTa 
transformer model to identify whether a given news article is Real or Fake.

## Objective

The main objective of this project is to develop an automated system 
that analyzes news text and classifies it as Real News or Fake News.

## Technologies Used

- Python
- Natural Language Processing (NLP)
- RoBERTa
- PyTorch
- Hugging Face Transformers
- Pandas
- NumPy
- Scikit-learn
- Streamlit

## Project Workflow

1. Collect the news dataset.
2. Clean and preprocess the text data.
3. Tokenize the news articles.
4. Fine-tune the RoBERTa model.
5. Test the trained model.
6. Evaluate the model using performance metrics.
7. Deploy the model using Streamlit.
8. Enter news text and get a Real/Fake prediction.

## Model

The project uses **RoBERTa**, a transformer-based language model 
that understands the context and meaning of text. The model is 
fine-tuned on the fake news dataset for binary classification.

## Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

## Application

A **Streamlit web application** is used for the demonstration. 
Users can enter a news article and click the **Predict** button 
to get the classification result.

### Example

**Input:**
```text
News article text
