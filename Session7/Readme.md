
The data set 
has three files 
1. Dictionary
2. Satement lables
3. Senatnce

The three datas sets merge to find the lables and senatnces.
Whole data sets label are categorised into five categories .

if label <= 0.2: return 0
    if label <= 0.4: return 1
    if label <= 0.6: return 2
    if label <= 0.8: return 3
    return 4

The total prametrs for the models evalutes to 500k prmetrs on the classifcation model.

The data is partially imbalanced and mostly in class 2 and class 4.

Hyper parmeters are 
Embedding dim
hiddeln layer
batch
epochs
