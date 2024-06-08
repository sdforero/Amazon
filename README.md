# YouTube
## Data Analysis Summary of Amazon Reviews
### Problematic Analyzed
The analysis focused on product reviews on Amazon. The main issue addressed was understanding trends and patterns in user opinions, identifying products with the best and worst ratings, and analyzing the frequency of recurring users. This enables businesses to optimize their product offerings and enhance customer satisfaction through a deep understanding of user feedback and experiences.

### Steps followed for data analysis
1. Data Loading: Reviews were imported in tabular format, containing fields such as Id, ProductId, UserId, ProfileName, among others.
2. Data Preprocessing:
- Filtering data to handle null values and inconsistent data.
- Extracting a sample of 50,000 rows to facilitate the analysis.
3. Sentiment Analysis: The TextBlob library was used to calculate the polarity of the reviews, determining the positive or negative sentiment of each opinion.
4. Product and User Analysis:
- Identifying products with the best and worst ratings.
- Analyzing frequent users to understand recurring behaviors.

### Technologies Used
Python: Primary language for analysis.
Pandas: For manipulation and analysis of structured data.
TextBlob: For sentiment analysis.
Jupyter Notebooks: For documenting and executing the analysis step-by-step.
Matplotlib and Seaborn: For data visualization and results.

### Analysis Conclusions
Sentiment Trends: The majority of reviews tend to be positive, with an average polarity reflecting general satisfaction with the products.
Highlighted Products: Certain products consistently received high ratings, serving as a reference for marketing and promotional strategies.
Frequent Users: Analysis of frequent users revealed behavior patterns that can be useful for loyalty programs and personalized offers.
Areas for Improvement: Products with low ratings were also identified, suggesting specific areas where sellers can focus their improvement efforts.
