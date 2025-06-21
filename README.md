# Chatbot

Datasets= https://huggingface.co/datasets/pythontech9/banking-chatbot-enquiries

UIdesign= https://github.com/sergekamanzi/BankBotUI.git

FastApi= https://github.com/sergekamanzi/apiBANKBOT.git




---

#  Banking Chatbot with Sentence Transformers

This project is a **domain-specific banking chatbot** built using the `all-MiniLM-L6-v2` Sentence Transformer model. It supports natural, human-like interaction and understands user queries about banking services such as account status, fraud reporting, card issues, and more.

###  Features

* Fine-tuned sentence transformer with contrastive loss
* BLEU
* Memory-based personalization (e.g., remembers user name)
* Intent detection and dynamic responses
* Handles off-topic and unclear queries gracefully

### Dataset

Custom banking Q\&A dataset containing user inquiries and relevant responses. Data is split 80/20 for training and testing.

###  Technologies

* Python, PyTorch, Transformers
* NLTK, RapidFuzz, TextBlob
* Matplotlib & Seaborn for analysis
* Sentence Transformers (`all-MiniLM-L6-v2`)

### Evaluation Metrics

* Cosine similarity thresholding
* BLEU Score
* F1-Score
* Top-K Retrieval Accuracy

### How to Run

```bash
# Install dependencies
!pip install -r requirements.txt

# Run main script
python chatbot3.py
```

###  Sample Interaction

```
You: Hello!
Chatbot: Hi there! How can I help you today?
You: I lost my card.
Chatbot: I'm sorry to hear that. You can block your card via the app or call support at 123-456.
```





