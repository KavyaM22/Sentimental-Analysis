Data Preprocessing, EDA, and Sentiment Analysis on Restaurant Reviews

1. Data Preprocessing
   
Missing Data: Rows with missing reviews or ratings were removed, resulting in 9,954 valid entries.
Text Cleaning: The review text was cleaned by removing special characters, converting to lowercase, and removing unnecessary spaces

2. Exploratory Data Analysis (EDA)
     Exploratory Data Analysis (EDA) is a crucial step in understanding the dataset before applying advanced modeling techniques. Here are the primary reasons why EDA is performed:

2.1. Understand Data Distribution
Rating Analysis: EDA helps identify trends in customer feedback, such as whether most reviews are positive or negative. In this case, the majority of ratings were positive (5 stars).
Outliers Detection: EDA reveals unusual patterns in the data, like extremely short or long reviews, which may need special handling or removal.
2.2. Identify Data Quality Issues
Missing Values: EDA helps in identifying missing values or incomplete data that need to be addressed (e.g., missing reviews or ratings).
Inconsistent Data: It uncovers irregularities, such as incorrect data types or entries, helping guide data cleaning efforts.
2.3. Feature Insights
Review Length: By analyzing review length, EDA shows whether longer reviews tend to be more detailed and emotional, which can impact sentiment analysis.
Frequent Words: Word frequency analysis provides insight into the core themes of the dataset. For restaurant reviews, words like "good," "food," and "service" indicate that these are the main areas of focus for customers.
2.4. Guide Modeling Approaches
Target Variable Distribution: By examining the rating and sentiment distributions, EDA helps in choosing appropriate machine learning algorithms. For example, highly imbalanced ratings (with many 5-star reviews) may require strategies like class balancing or resampling.
2.5. Gain Business Understanding
Common Review Topics: Identifying frequently used words can inform restaurant owners of what aspects customers care about most (e.g., food, service, ambiance), which helps in improving business decisions.

3. Sentiment Analysis
     We can now proceed to classify the sentiment of each review (positive, negative, or neutral) using supervised machine learning models. Based on the Rating column, we can assume higher ratings indicate positive sentiment and lower ratings indicate negative sentiment.
