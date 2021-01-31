# SentimentAnalysis

SST-5 Malay is translated from SST-5 using Google translate API in **Google Translate (En-Malay).ipynb**.

**Process Data.ipynb** can extract the text by paragraph from Microsoft Word files in a directory. Manual deletion is needed to clean the data. Extraction from PDF is available but havent sort into paragraphs.


# Results 
![alt text](https://github.com/YuHengKit/SentimentAnalysis/blob/main/comparison.png?raw=true)

bert_en = trained SST (english) on BERT
bert_malay = trained SST(malay) on BERT
bert_en+malay= trained SST( english+malay) on BERT

English dataset = our pure 8k english dataset
Malay dataset = our pure 8k malay dataset
English + Malay dataset = 4k english + 4k malay dataset
