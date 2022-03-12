## Simple Chatbot from Scratch in Python (using NLTK)

---
- ### Pre-requisites
<b> NLTK(Natural Language Toolkit) </b>
(https://www.nltk.org/)[NLTK] is a Python library for working with human language data. It provides a wide range of functionality for text analysis. A lot of the data that you could be analyzing is unstructured data and contains human-readable text. Before you can analyze that data programmatically, you first need to preprocess it. In this tutorial, you’ll take your first look at the kinds of text preprocessing tasks you can do with NLTK so that you’ll be ready to apply them in future projects. You’ll also see how to do some basic text analysis and create visualizations.

---

- ### Installing required packages
```bash
pip install -r requirements.txt
```

```bash
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet')
```

---
- ### How to run? 
    - Through Terminal
    ``` bash
    python chatbot.py
    ```