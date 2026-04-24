# NLP Spam Classification

This project implements a bidirectional Transformer architecture using BERT to classify SMS messages as spam or legitimate, effectively addressing severe class imbalances through custom metric evaluation. By fine-tuning a pretrained sequence classification head and explicitly extracting final-layer attention weights, the model successfully identifies contextual threat indicators. 

Future iterations will transition this analytical notebook into a fully modular Python data pipeline to optimize inference and deployment.

**Language:** Python

**Frameworks & Libraries:** PyTorch, Hugging Face, Pandas, Scikit-learn, Matplotlib, Seaborn

**Model:** BERT (Bidirectional Encoder Representations from Transformers)

**Dataset:** SMS Spam Collection Dataset (UCI Machine Learning Repository)

## **NOTE:**

As a result of transfering this notebook from Google Colab to GitHub, there is an error when attempting to view the notebook via GitHub. This is due to the use of widgets in the notebook, which are not supported by GitHub's rendering of Jupyter notebooks. This will be resolved as soon as possible. If I'm unable to remedy the issue, I will clear cell outputs and upload rendered images to the repository after completing modularization of the code.