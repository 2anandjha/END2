The text preprocessing can broadly be classified into two major steps:
Text Cleaning
Text to Vector Conversion

Text Cleaning involves 
a.Removing HTML tags
b.Removing Punctuation
c.Removing Stopwords
d.Stemming
e.Conversion to lower cases

Text to Vector 


The number of columns after merging all data sets
sentence_index	
sentence	
phrase	
phrase ids	
splitset_label	
sentiment values

Exploratory Data Anlayisis
![Unknown](https://user-images.githubusercontent.com/70034867/120689945-47121900-c4c2-11eb-96d7-96dd34235289.png)

Let’s plot the number of words appearing in each data frame phrase
![Unknown-2](https://user-images.githubusercontent.com/70034867/120690968-7d9c6380-c4c3-11eb-9c24-633325f2ef85.png)

It appears to be in 15 -17 the number of words in phrase

classifier(
  (embedding): Embedding(18010, 300)
  (encoder): LSTM(300, 100, num_layers=2, batch_first=True, dropout=0.2)
  (fc): Linear(in_features=100, out_features=3, bias=True)
)
The model has 5,644,903 trainable parameters

Accuracy is 70%
Train Loss: 0.832 | Train Acc: 71.98%
	 Val. Loss: 0.836 |  Val. Acc: 71.59% 
   
   

