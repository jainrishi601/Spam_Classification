# Spam_Classification
This Model Classifies that the message is spam or not
Recommended to download Stopwords from  https://www.nltk.org/nltk_data/.
Then code:
from import nltk

--->Set NLTK data path to the downloaded directory

nltk.data.path.append('/path/to/nltk_data')

--->Now you can import other NLTK modules

from nltk.corpus import stopwords

# Summary of Code:
import all necessary Libraries

Then text Preprocessing- Removing Characters, lowering, converting to words and then removing stopwors

Here I am using Bag of Words/(1,0)/Countvectorizer, since Classification model is their. You can use TD*IDF also

Naive Bias ...Probability wala is used as it is good for NLP Classification Problems.

Confusion Metrices is made
Accuracy =98%
