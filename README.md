![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/916dbc81-cb2e-431b-9d7a-3dfce0334fbd)## Data-Driven Brand Mastery: EABL's Social Analytics

## Business Overview
### Introduction:
East African Breweries Limited (EABL) stands as a preeminent player in the Fast-Moving Consumer Goods (FMCG) sector, particularly within the competitive beverage industry. Operating across East Africa, EABL has established a robust market presence in countries such as Kenya, Uganda, Tanzania, Rwanda, and South Sudan. The company boasts a diverse and iconic portfolio of brands, including Tusker Lager, Pilsner Lager, WhiteCap Lager, Johnnie Walker, Smirnoff, Gilbey's Gin, Richot Brandy, Bond 7 Whiskey, and Baileys Irish Cream. (EABL, 2023)

### Strategic Approach:
EABL has adopted a forward-thinking approach, recognizing the pivotal role of data science in shaping its business strategies. The company understands that leveraging data analytics is instrumental in brand monitoring, enhancing brand perception, and driving meaningful customer engagement.
### Data Science in Brand Monitoring:
EABL employs cutting-edge data science techniques to monitor its brand performance in real-time. By harnessing data from social media, market surveys, and other relevant sources, the company gains valuable insights into consumer sentiments, emerging trends, and competitive landscapes. This enables EABL to proactively respond to market dynamics and fine-tune its branding strategies accordingly.

##  Problem Statement:

EABL faces challenges in effectively gauging and understanding customer sentiments expressed across various channels, including social media, online reviews, and customer feedback. The current methods for manually analyzing textual data are resource-intensive and may not capture the nuances and real-time dynamics of customer sentiments.
### Key Challenges:

1. <b>Sentiment Understanding</b>: The current approach to understanding customer sentiments lacks precision, leading to potential misinterpretation of feedback and an inability to promptly address concerns or capitalize on positive sentiments.

2. <b>Real-time Analysis</b>: Manual sentiment analysis is time-consuming and cannot keep pace with the rapid and dynamic nature of online discussions and customer interactions, hindering timely response strategies.
3. ## Objective
<b>Main Objective</b> :Develop an automated sentiment analysis system to accurately classify customer sentiments expressed in textual data.


<b>Specific Objectives</b> :
1. Analyze sentiments expressed by consumers regarding EABL products, marketing campaigns, and brand image.Categorize sentiments as positive, negative, or neutral to derive actionable insights.

2. Leverage sentiment insights to inform marketing strategies, product enhancements, and overall customer engagement initiatives Leverage sentiment insights to inform marketing strategies, product enhancements, and overall customer engagement initiatives.

3. Implement sentiment-driven customer segmentation to tailor marketing messages and promotions based on distinct customer sentiment profiles
###  Success Criteria
<b>Sentiment Analysis Accuracy</b>:Evaluate the accuracy of the sentiment analysis model by comparing predicted sentiments against manually labeled data.(at least 85% )
Aim for high precision and recall, especially for identifying positive and negative sentiments.

<b>Segmentation Model Performance</b>:Assess the effectiveness of the customer segmentation model in accurately grouping users based on sentiment and additional features.

### Stakeholders

<b>Marketing Team:</b> Benefit from insights to optimize marketing strategies and refine campaigns.

<b>Product Development Team:</b> Utilize feedback for continuous product improvement and innovation.

<b>Executive Leadership:</b> Receive regular reports on brand health and public perception for strategic decision-making.
## Data Understanding

#### 1. Brand Mentions:

Social media posts, comments, and mentions related to EABL and its brands.

Data sources: Twitter,(Likes, shares, comments, EABL relevant hashtags.) and Google News 


#### Product Feedback:

Comments and discussions regarding specific EABL products.

#### Data sources:

Social media platforms, review sites, online forums.

Data on taste, packaging, pricing, and overall satisfaction.

#### Campaign Reactions:

Public reactions to EABL's marketing campaigns and promotions.

Data sources: Social media platforms.

#### Event Participation:

Social media mentions related to EABL-sponsored events and promotions.

#### Customer Service Interactions:

Social media interactions with EABL's official customer service handles.
### Data Cleaning
1. Handling missing values
2. Checking for duplicates
3. Correcting data types
4. Checking for outliers

   ![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/a3c7c0f9-90cf-4359-9300-15c4b24d84df)


5. Removing unnecessary text

# EXPLORATORY DATA ANALYSIS
1. Checking length of text
2. Separating datetime features
3. Getting the total engagement

   ![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/b8df113c-43d6-4b72-9a89-ecd15018e2e5)


4. Distribution of tweets based on the day of week.

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/f3cb54b5-65b6-4844-88d7-fb10435ee0a4)

   
   <b>Fridays</b> is the peak of people contribution of the EABL tweeter(X) platform. People tend to tweet more about alcohol on Fridays due to the end-of-week celebration, social gatherings, popular hashtags like #FridayFeeling, the association of Fridays with relaxation, and cultural norms that encourage discussions about alcohol-related activities on certain days.  

<b>Mondays</b>, has the least tweets. This is partially due to people, generally focused on the start of the workweek, responsibilities, and may have a more serious or work-oriented mindset. There's often less emphasis on celebratory or leisure activities like alcohol consumption. Additionally, Monday is often associated with recovering from the weekend, setting professional goals, and a lower inclination for socializing compared to the more relaxed atmosphere on Fridays
## Distribution of tweets by hour of the day

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/30f0c453-62ef-491e-8411-56ce8ace7396)

1. End of Workday: Many users tweet around 5 PM as it marks the end of the workday, providing a convenient time for them to engage in social media activities.
2. Commute Time:People tweet during their commute home, making 5 PM a popular time for sharing thoughts and updates.
3. Break Time:Individuals take breaks in the late afternoon to unwind, with 5 PM becoming a common time for social media engagement.
4. Global Connectivity:5 PM aligns with peak online activity, connecting users from different time zones and contributing to increased Twitter usage.
5. Social Interaction:Twitter is used for social interactions, and 5 PM serves as a time for connecting with friends and colleagues, sharing daily updates.
 ## Clustering the users based on sentiment
 The folowing are the clusters represented
 Cluster 0: Users in this cluster have  a lower average sentiment.(average :3.843131)
 Cluster 1: Users in this cluster have  a moderate average sentiment.(average: 3.684777 )
 Cluster 2: Users in this cluster have a higher average sentiment.(average: 922274)
 
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/a3f4bea0-249c-4fe6-970c-7f653c0c7028)
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/f7f3ae1c-135d-4689-b3bb-89d070c38aa4)
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/0da296d3-5a75-4712-a8ad-77c65ad55856)
 
 Cluster 1: Users have high number of positive sentiments.

These customer may receive messages emphasizing brand loyalty, while negative segments may receive messages addressing concerns or offering solutions.

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/07eba0db-f504-4f19-8387-7df4cfb90900)

Develop marketing messages and promotions tailored to each segment's sentiment profile. Positive segments may receive messages emphasizing brand loyalty, while negative segments may receive messages addressing concerns or offering solutions.
## Correlation matrix of the engagement means
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/1f343446-ad35-4d06-84ec-3265855446b5)

## Data preprocessing
Before conducting sentiment analysis, it is imperative to follow these essential steps: eliminating stop words, removing tags, URL links, and other extraneous words, tokenizing the text, and lemmatizing words.

##### Checking for tweet Length Consistency
We notice that some tweets consist of less than five words therefore won't be instrumental in constructing our predictive model.
We note tht there are 64260 tweets with characters greater than 5 and  1523 tweets with characters less than 5 characters.
### Checking for Duplicates in the dataset
It is not evident if there are duplicated tweets. We chose to retain the duplicates.
For cleaning our text we are gling to use the NeatText Library. NeatText is a simple NLP package for cleaning textual data and text preprocessing. It offers a variety of features for cleaning unstructured text data, reducing noise (such as special characters and stopwords), and extracting specific information from the text. It can be used via an object-oriented approach or a functional/method-oriented approach, providing flexibility in its usage. The package includes classes such as TextCleaner, TextExtractor, and TextMetrics for different text processing tasks. 
We also removed specisl characters, whitespaces and emojis.

###  Contractions

Contractions in a tweet refer to shortened forms of words or phrases that are created by combining two words and replacing one or more letters with an apostrophe. Contractions are commonly used in informal writing, including tweets, to save space and make the text more conversational.
### Language Processing (Clean Text)
This involves Tokenization, Stemming / Lemmatization, Parts of Speech Tagging and Calculating Sentiment Based on Polarity & Subjectivity.
### Lemmatization
Lemmatization is a linguistic processing technique that involves reducing words to their base or root form, known as the lemma.The purpose of lemmatization is to standardize and simplify words, considering different inflections or variations of a word as a single base form. This aids in tasks such as text analysis, natural language processing, and information retrieval by treating related forms of a word as identical
### Calculatition of Sentiments Based on Polarity & Subjectivity
TextBlob is a Python library used for processing textual data, including sentiment analysis. It uses natural language processing (NLP) and the Natural Language Toolkit (NLTK) to achieve this task. When a sentence is passed into TextBlob, it returns two outputs: polarity and subjectivity. The polarity score is a float within the range [-1, 1], where -1 indicates a negative sentiment and 1 indicates a positive sentiment. The subjectivity score is a float within the range, where 0 is very objective and 1 is very subjective. Getting the count of varying sentiments. (positive, negative and neutral)
Neutral     37687
Positive    20049
Negative     6524
Name: sentiment, dtype: int64
We note that we have some missing values in our dataset. We chose to drop them since we won't be losing a good chunk of data.

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/f36c9249-5e3b-48b2-ad3b-76274a64af08)

The histogram shows that the most common word count is between 20 and 50. The distribution is skewed to the left, meaning that there are more tweets with lower word counts than higher word counts.

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/d6a2b5bc-bb5e-4141-8fc4-79c6b6aa623d)

### Sentiment Analysis
Distribution of Sentiments

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/be284ffa-90ed-4927-98df-6550d601bcd4)

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/5ede79d8-b798-46fe-9884-6a8614b7ca92)
 This is a tree map of the most common positive words.
### Negative Sentiment Analysis
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/45038262-3585-49de-8e2e-0c150453f63d)

This is a tree map of the most common negative words.

### Neutral Sentiment Analysis

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/a42043b8-8ae4-4d76-972d-0e908a665df3)

This is a tree map of the most common neutral words.
### Dealing with sample imbalance
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/915905cd-b61d-42e9-9505-1c95549ee9a7)

Initial distribution of sentiment analysis.
Below is the balanced sentiments after using RandomOverSamepler

![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/a8566171-2556-4a29-92b6-60366fbf5f79)

# Modeling
Data is now balanced.
### Data Preparation
### Spliting Data into Train and Test

## Naive-Bayes Model
Accuracy: 0.7813286587558432

Classification Report:
               precision    recall  f1-score   support

    Negative       0.72      0.85      0.78      7358
     Neutral       0.85      0.67      0.75      7491
    Positive       0.80      0.82      0.81      7399

    accuracy                           0.78     22248
   macro avg       0.79      0.78      0.78     22248
weighted avg       0.79      0.78      0.78     22248
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/45146828-a073-4756-bfc3-4e45154e6634)

Above is the confusion matrix for the same.

## Recommendations:
##### 1.  Brand Perception and Engagement:
EABL should capitalize on the positive sentiments expressed by customers, especially around popular brands like Tusker and Gilbey's by developing effective marketing strategies to amplify and maintain the positive image.
The company should also consider targeted campaigns/Events to address issues raised in negative sentiment in the different brands.

##### 2. Marketing Campaign Effectiveness:

EABL should continue monitoring social media reactions to marketing campaigns/Events to gauge effectiveness by using insights to refine future campaigns and promotions and ensuring they resonate positively with the target audience.
They should also encourage user-generated content and interaction to increase positive experiences.

##### 3. Continuous Social Media Monitoring & Regular Surveys:

The company should implement a real-time social media monitoring system to stay updated on evolving social media sentiments and Conduct periodic surveys to gather structured feedback from customers then use the insights to identify/address areas for innovation and enhancement.

### Conclusion:

In conclusion, the sentiment analysis revealed valuable insights into public perception of EABL brands & their sponsored campaigns/Events on social media. Positive sentiments around brands indicate strong brand loyalty, while negative sentiments point to specific areas that require attention. EABL should leverage positive sentiments, address concerns, and continue monitoring social media for ongoing improvement.

### Limitations:

##### 1. Data Source Limitations:

The sentiment analysis relies on data primarily from Twitter and Google News. This didn't fully capture the diverse opinions of all customers in different social media platforms.

##### 2. Bias in Social Media Data:

Social media data may have inherent biases and may not represent the views of the entire customer base. The analysis might be skewed towards more active users on these platforms.

### Next Steps:

##### 1. Diversify Data Sources:

Expand data collection to include other social media platforms and online forums such as Facebook, Instagram, this will ensure a more comprehensive understanding of public sentiment.

##### 2.  Continuous Model Improvement:

To continue refining the models to improve accuracy and explore  more advanced natural language processing techniques.

##### 3.  Real-time Monitoring:

Implement a real-time monitoring system to track sentiments and reactions promptly. This will allow EABL to respond swiftly to emerging trends and issues.







