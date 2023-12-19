# Resume-screener
A repository containing a resume screening software build in Python & NLP.
- To run the app:-
```
streamlit run app.py
```
- Choosing the right people for your job is the biggest responsibility of every business, since choosing the right set of people can accelerate business growth exponentially.

This is a simple web application built with Streamlit that serves as a "Resume Screener." The main functionality is to upload a resume file (either a text or PDF file) and use a pre-trained machine learning model to predict the category or job role associated with the content of the resume. The predictions are displayed in the web interface along with the predicted category name.

**Libraries Used:**
- streamlit: A Python library for creating web applications with minimal effort.
- pickle: Used for serializing and deserializing Python objects (here, it's used to load pre-trained machine learning models).
- re: The regular expression module for pattern matching and text manipulation.
- nltk: The Natural Language Toolkit for natural language processing tasks.

**Model Loading:**
- The code loads a pre-trained machine learning model (clf.pkl) and a TF-IDF vectorizer (tfidf.pkl). The model is a text classification model trained on resume data.

**Text Cleaning Function:**
- clean_resume(resume_text): This function takes a raw resume text and performs several cleaning steps, including removing URLs, mentions, special characters, non-ASCII characters, and extra whitespaces.

![2023-12-19 18_14_51-](https://github.com/Marx-wrld/Resume-screener/assets/105711066/e69aba16-f59c-4e4c-a0e3-9750f97e70f9)
