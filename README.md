## Data-Driven Brand Mastery: EABL's Social Analytics

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
6. ## Clustering the users based on sentiment
7. The folowing are the clusters represented
1. Cluster 0: Users in this cluster have  a lower average sentiment.(average :3.843131)
2. Cluster 1: Users in this cluster have  a moderate average sentiment.(average: 3.684777 )
3. Cluster 2: Users in this cluster have a higher average sentiment.(average: 922274)
 ![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/a3f4bea0-249c-4fe6-970c-7f653c0c7028)
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/f7f3ae1c-135d-4689-b3bb-89d070c38aa4)
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/0da296d3-5a75-4712-a8ad-77c65ad55856)
 Cluster 1: Users have high number of positive sentiments.
These customer may receive messages emphasizing brand loyalty, while negative segments may receive messages addressing concerns or offering solutions.
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/07eba0db-f504-4f19-8387-7df4cfb90900)
Develop marketing messages and promotions tailored to each segment's sentiment profile. Positive segments may receive messages emphasizing brand loyalty, while negative segments may receive messages addressing concerns or offering solutions.
## Correlation matrix of the engagement means
![image](https://github.com/JETshelf/EABL-Sentiment-Analysis/assets/133136216/1f343446-ad35-4d06-84ec-3265855446b5)
