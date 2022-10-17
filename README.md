# Twitter-Sentiments

## Introduction
Now-a-days social networking sites are at the boom, so large amount of data is gen- erated. Millions of people are sharing their views daily on micro blogging sites, since it contains short and simple expressions. Twitter, a micro-blogging website, is a massive repository of public opinions expressed in the direction of numerous humans, offerings, companies, merchandise, etc.Twitter is a popular and one of the most used social media website. People usually use twitter to express their opinion or view or an emotion on particular subject.
Sentiment Analysis is the process of computationally determining whether a piece of writing is Positive , Negative or Neutral . Sentiment evaluation is the system of ana- lyzing one’s public evaluations. Sentiment analysis whilst combined with twitter offers beneficial insights into what’s expressed on Twitter. The big availability of online evalu- ations and postings in social media gives invaluable feedback for groups to make better knowledgeable choices in guidance their marketing techniques towards user’s pastimes and alternatives. Sentiment evaluation is, therefore, vital for determining the general public’s opinion toward selected services or products.Sentiment analysis is also referred as Opinion Mining.
Sentiment Analysis is mainly used for 3 main purposes namely :-

### •	Bussiness
In marketing field companies use it to develop their strategies, to understand cus- tomers’ feelings towards products or brand, how people respond to their campaigns or product launches and why consumers don’t buy some products.
### •	Politics
In political field, it is used to keep track of political view, to detect consistency and inconsistency between statements and actions at the government level. It can be used to predict election results as well.
 

### •	Public Actions
Sentiment analysis also is used to monitor and analyse social phenomena, for the spotting of potentially dangerous situations and determining the general mood of the blogosphere.

## Brief Methodology of the project

### •	Gathering Tweets :
The process of gathering data depends on the project and it includes collection of various datasets that are required for the project.Here , We will be creating our own dataset by parsing through the tweets in TWitter using the Twitter API functions called the TWeepy and Textblob .

### •	Division into positive and negative tweets :
Using Tweepy and Textblob the parsed through tweets are formed as a dataset and they are classified as positive, negative or neutral tweet .Which combined together forms a dataset .

### •	Data pre-processing :
Before entering into the project the datsets should be verified whether there are any missing values and so on.Some of the pre-processing techniques performed are checking the quality of the data and ensuring that there are no null or any missing values and next Tokenization stemming,countvectorzing and td-idf will be imple- mented .This pre-processing has to be done to both the negative tweets and the positive tweets .

### •	Training and testing :
Once the datasets are ready for the algorithm then the implementation of the model starts. Here datasets are divided into two training dataset,testing dataset .

### •	ML algorithms :
The data is then passed through various ML algorithms i.e:Logistic regression,MuliNomialNB,Ran Tree Classifier etc. Then the algorithm are compared based on their accuracy and
f1-scores and confusion matrix .The model is trained using trained dataset and then performed testing using test dataset.


