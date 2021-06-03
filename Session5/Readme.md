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


classifier(
  (embedding): Embedding(18010, 300)
  (encoder): LSTM(300, 100, num_layers=2, batch_first=True, dropout=0.2)
  (fc): Linear(in_features=100, out_features=3, bias=True)
)
The model has 5,644,903 trainable parameters

Accuracy is 70%
Train Loss: 0.832 | Train Acc: 71.98%
	 Val. Loss: 0.836 |  Val. Acc: 71.59% 
   
   

