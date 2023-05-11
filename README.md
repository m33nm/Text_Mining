# Text_Mining
Sentiment Analysis on restaurants in Patong, Thailand applied text mining and
sentiment analysis on 30 restaurant reviews in Patong. It employs the VADER (Valence Aware
Dictionary for Sentiment Reasoning) model to analyze text data from tourist reviews to reveal
the sentiment scores of the selected restaurants and the Bag-of-words model to extract and
show the frequency of the words in the reviews.

Deciding on what to eat has always been a hurdle for travelers. The
result of this analysis would further guide tourists in selecting restaurants with excellent reviews,
thereby saving costs and resources. The research explores tourist reviews to extract positive and
negative sentiments from the selected restaurants.

Exploratory data analysis and preparation tasks were carried out on the dataset before and after creating a subset of the
dataset with 30 selected restaurants. It shows that Patong has 164 unique Hotels/Restaurants, which formed the data for the analysis. 

# Results Analysis
The sentiment scores revealed that the restaurant reviews are primarily positive. The median compound score is 0.83
– which means that over 50% of the reviews have a compound score of more than 0.83, suggesting a strong positive sentiment.
The sentiment varies across the selected restaurants. It compares the
proportion of positive and negative reviews and displays the wordcloud results and frequency
distribution of words in the reviews.

_**Sentiment Analysis Results**_

A compound score less than/equal to zero was classified as negative, and the opposite as a
positive review. The positive review analysis revealed that No. 6 Restaurant has the
highest score with 186 remarks, and Ali Baba Restaurant has the least positive remark with 68
reviews. Of course, the number of positive reviews for each restaurant doesn’t tell us much
unless we know how many reviews there are. Hence, the number of positive reviews as a
proportion of the total number of reviews per restaurant (Figure 1) shows that Salute Italian
Restaurant has the highest percentage of positive reviews, with Ali Baba Restaurant still having
the least.

![image](https://github.com/m33nm/Text_Mining/assets/54365936/8a633751-b5d0-430f-a5ab-85f6c39f50de)

Figure 1: Percentage of Positive Reviews

_**Text Mining Results**_

Text mining technique was applied to the Salute Italian Restaurant to understand and visualize
the more frequently used words in positive reviews because the restaurant has the highest
positive compound score. And the Ali Baba Restaurant in negative reviews because it has the
highest negative compound score. 

![image](https://github.com/m33nm/Text_Mining/assets/54365936/6215c003-94d3-40a6-8485-5489bc9149d5)

Figure 2: Wordcloud for Salute Italian Restaurant Lemmatized Positive Reviews

In Figure 2, the words ‘food’, ‘italian,’ ‘great,’ and ‘pizza’ have been mentioned several
times – perhaps the food/pizza is great, given that it is an Italian restaurant


![image](https://github.com/m33nm/Text_Mining/assets/54365936/5b08b0db-e6f5-4aa6-bc9c-138b8028b26a)
Figure 3: Wordcloud for Ali Baba Restaurant Lemmatized Negative Reviews

In Figure 3, the words ‘food’, ‘restaurant,’ ‘place,’ ‘indian,’ ‘service,’ ‘horrible,’ and ‘good’
have been mentioned several times – perhaps the restaurant is run by Indians even though they
are good people, the food or service quality could be poor.

# Ethical Considerations
• **Fairness**: The outcome of this analysis is a result of the reviews from the tourists’
experiences. It is not favorable to any specific restaurant, and the selection of the 30
restaurants under review was utterly random.

• **Privacy**: All the reviews are not associated with a particular individual. The collected data
does not violate privacy, and I believe the tourists consent to providing their opinions
without undue pressure.

# Conclusion
Patong, a prominent tourist destination in Thailand, has hundreds of more restaurants than any
other business. First-time visitors are more likely to waste resources in an attempt to purchase
quality food worth every penny. Thus, this analysis would guide first-timers, tourists, or
explorers in choosing restaurants with excellent reviews, thereby saving costs and resources.
The research explores tourist reviews from 30 selected restaurants in Patong to extract positive
and negative sentiments. Although some words are not entirely informative, the results would
still infer meaningful choices. However, the analysis can be implemented using more restaurants for further research.
