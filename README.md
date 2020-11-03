# bert-for-document-sentiment-analysis

## Dataset
Stanford University's Large Movie Review Dataset (https://ai.stanford.edu/~amaas/data/sentiment/)

Contains 25,000 labelled movie reviews for training and 25,000 labelled movie reviews for testing.
## Scripts

### Dataset creation
load_dataset.ipynb: 
- Splits the data : Train 80% (40,000 examples), Validation 10% (5,000 examples), Test 10% (5,000 examples)
- Creates .csv files for the datasets: train.csv, validation.csv, test.csv

### BERT Base with an output layer
trained_bert_base_model.ipynb:
- Model from Hugging Face's Transformers Library (https://huggingface.co/transformers/):
  - Embedding Layer (Contextualized word embeddings)
  - 12 transformers
  - Output Layer
- Hyperparameter tuning, Regularization, and Optimization
  - Optimizer: AdamW
  - Learning Rate: 2e-5
  - Epochs: 10
  - Batch-size: 32

