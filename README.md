# bert-for-document-sentiment-analysis

## Dataset
Stanford University's Large Movie Review Dataset (https://ai.stanford.edu/~amaas/data/sentiment/)

Contains 25,000 labelled movie reviews for training and 25,000 labelled movie reviews for testing.
## Scripts
### Dataset creation
load_dataset.ipynb: 
- Splits the data : Train 80% (40,000 examples), Validation 10%(5,000 examples), Test 10%(5,000 examples)
- Creates .csv files for the datasets: train.csv, validation.csv, test.csv
