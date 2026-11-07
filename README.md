# NLP Spam Classification

This project fine-tunes `bert-base-uncased` to classify SMS messages as spam or legitimate using PyTorch and Hugging Face Transformers. It uses a stratified training/validation split and reports spam-class precision, recall, and F1 alongside accuracy to evaluate performance on an imbalanced dataset. The notebook includes training and validation loss analysis and code for visualizing four attention heads in layer 8.

Future iterations will transition this analytical notebook into a fully modular Python data pipeline to optimize inference and deployment.

**Language:** Python

**Frameworks & Libraries:** PyTorch, Hugging Face, Pandas, Scikit-learn, Matplotlib, Seaborn

**Model:** BERT (Bidirectional Encoder Representations from Transformers)

**Dataset:** SMS Spam Collection Dataset (UCI Machine Learning Repository)

## View the analysis

[Read the notebook](NLP-Spam-Classification-Analysis.ipynb) for the code, saved training/validation loss plot, and evaluation output. The attention-analysis cell contains the code to generate layer-8 heatmaps, but its heatmap outputs are not saved in this version.

The Colab export's widget metadata has been corrected to use the standard Jupyter `state`, `version_major`, and `version_minor` structure. All cells, execution counts, saved outputs, and widget records are preserved. GitHub provides a static notebook view; interactive widgets require a compatible notebook environment.

## Run the notebook

[Open in Google Colab](https://colab.research.google.com/github/kylehonke/NLP-Spam-Classification/blob/main/NLP-Spam-Classification-Analysis.ipynb) and run the cells in order. The notebook includes a Google Drive mount cell, downloads the UCI dataset and pretrained BERT weights, and saves model checkpoints locally. A GPU runtime is recommended for fine-tuning.

The original package versions are not recorded, and the saved training output includes checkpoint-loading key mismatch warnings. The saved metrics are validation results from the original run, not an independent test-set evaluation or a newly reproduced benchmark. Reproducing those values requires validating the training environment and checkpoint loading; this rendering correction does not rerun training.
