<h1> Tutorial Modelling Data Titanic</h1>
    
<p> Tutorial ini akan mengolah data titanic menjadi data yang siap untuk dilakukan pemodelan</P>
    
<h2> Prerequisite</h2>

1. Download [here](https://www.kaggle.com/datasets/fossouodonald/titaniccsv)
2. Instalasi dengan `pip install requirements.txt`

## Geting Started
- Dataset Splitting
- Training
- Model Validation

### Dataset Spliting
split data into training, validation, test

```code
x_train, y_train, x_test, y_test = dataset_splitting()
x_train.shape, y_train.shape
```

