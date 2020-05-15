# nlp_Kaggle_Quora_insincere
Proposition for Kaggle's Quora Insincere question classification challenge. 

In this Notebook, the whole process is described, from data processing to model creation, training and testing.

We have used RNN and BERT.

REQUIREMENTS:
- PyTorch,
- Numpy,
- transformers (from Hugging Face)
- sklearn,
- Google Drive access.

Works fine on Google Colaboratory.

Remark: For now, the embedding dictionnaries are saved on our google drive the link being written in the notebook. In case the file isn't there anymore, you can download the embeddings yourself on https://www.kaggle.com/c/quora-insincere-questions-classification, and used the functions: create_dict_glove, create_dict_wiki and the commented code for word2vec to generate the .npy files, load these files in your Googe Drive, generate and replace the links and it wil work.

This notebook is the result of the work of:

Joachim DUBLINEAU & Samuel MONTINI
