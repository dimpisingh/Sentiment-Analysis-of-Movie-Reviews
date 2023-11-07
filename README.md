## <br>**➲ Sentiment-Analysis-of-Movie-Reviews**
Sentiment Analysis of Movie Reviews is a project which is based on natural language processing, where we use NLP techniques to extract useful words of each review and based on these words we can use binary classification to predict the movie sentiment if it's positive or negative.

## <br>**➲ Prerequisites**
Install all required packages :
 ```sh
  pip install -r requirements.txt
  ```
## <br>**➲ The Dataset**
Human activites dataset contain about 50000 record which is a sample of movie's review<br>
and a target column "sentiment" which describe the sentiment of the viewer about the movie either it is positive or negative<br>

## <br>**➲ Coding Sections**
In this part we will see the project code divided to sections as follows:
<br>
- Section 1 | Data Preprocessing :<br>
In this section we aim to do some operations on the dataset before training the model on it,
<br>processes like :
  - Loading the dataset
  - Encoding ouput to binary (Positive : 1 , Negative : 0) 
  - Data cleaning : Remove HTML tags
  - Data cleaning : Remove special characters
  - Data cleaning : Convert everything to lowercase
  - Data cleaning : Remove stopwords
  - Data cleaning : Stemming<br><br>

- Section 2 | Model Creation :<br>
The dataset is ready for training, so we create a Naive Bayes model using scikit-learn and then fit it to the data.<br>

- Section 3 | Model Evaluation :<br>
Finally we evaluate the model by getting accuracy, classification report and confusion matrix.

## <br>**➲ Installation**
1. Clone the repo
   ```sh
   git clone https://github.com/dimpisingh/Sentiment-Analysis-of-Movie-Reviews.git
   ```
2. Run the code from cmd
   ```sh
   python movie_reviews_sentiment_analysis.py
   ```

## <br>**➲ References**
These links may help you to better understanding of the project idea and techniques used :
1. Natural Language Processing (NLP) : https://ibm.co/38bN03T
2. Sentiment analysis : https://bit.ly/3yi9BGq
3. Naive Bayes classifier : https://bit.ly/3zhoWIO
4. Model evaluation : https://bit.ly/3B12VOO