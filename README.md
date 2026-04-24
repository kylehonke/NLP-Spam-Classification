# NLP Spam Classification

This project implements a bidirectional Transformer architecture using BERT to classify SMS messages as spam or legitimate, effectively addressing severe class imbalances through custom metric evaluation. By fine-tuning a pretrained sequence classification head and explicitly extracting final-layer attention weights, the model successfully identifies contextual threat indicators. 

Future iterations will transition this analytical notebook into a fully modular Python data pipeline to optimize inference and deployment.

**Language:** Python

**Frameworks & Libraries:** PyTorch, Hugging Face, Pandas, Scikit-learn, Matplotlib, Seaborn

**Model:** BERT (Bidirectional Encoder Representations from Transformers)

**Dataset:** SMS Spam Collection Dataset (UCI Machine Learning Repository)