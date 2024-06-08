# YouTube
## Data analysis summary of Amazon reviews
### Problematic Analyzed
The analysis focused on product reviews on Amazon. The main issue addressed was understanding trends and patterns in user opinions, identifying products with the best and worst ratings, and analyzing the frequency of recurring users. This enables businesses to optimize their product offerings and enhance customer satisfaction through a deep understanding of user feedback and experiences.

### Technologies used
- Python: Primary language for analysis.
- Pandas: For manipulation and analysis of structured data.
- TextBlob: For sentiment analysis.
- Jupyter Notebooks: For documenting and executing the analysis step-by-step.
- Matplotlib and Seaborn: For data visualization and results.
  
### Steps followed for data analysis
1. Data Loading: Reviews were imported in tabular format, containing fields such as Id, ProductId, UserId, ProfileName, among others.
2. Data Preprocessing: [2.1] Filtering data to handle null values and inconsistent data. [2.2] Extracting a sample of 50,000 rows to facilitate the analysis.
3. Sentiment Analysis: The TextBlob library was used to calculate the polarity of the reviews, determining the positive or negative sentiment of each opinion.
4. Product and User Analysis: [4.1] Identifying products with the best and worst ratings. [4.2] Analyzing frequent users to understand recurring behaviors.

### Images
|Image 1|Image 2|
|----|----|
|![Imagen1](https://github.com/sdforero/YouTube/blob/main/1.%20Products%20positives%20reviews.png)|![Imagen2](https://github.com/sdforero/YouTube/blob/main/2.%20Relation%20between%20quantity%20and%20score%20freq.png)|

|Image 3|Image 4|
|----|----|
|![Imagen3](https://github.com/sdforero/YouTube/blob/main/1.%20Products%20positives%20reviews.png)|![Imagen4](https://github.com/sdforero/YouTube/blob/main/2.%20Relation%20between%20quantity%20and%20score%20freq.png)|

### Analysis conclusions
- Sentiment trends: The majority of reviews tend to be positive, with an average polarity reflecting general satisfaction with the products.
- Highlighted products: Certain products consistently received high ratings, serving as a reference for marketing and promotional strategies.
- Frequent users: Analysis of frequent users revealed behavior patterns that can be useful for loyalty programs and personalized offers.
- Areas for improvement: Products with low ratings were also identified, suggesting specific areas where sellers can focus their improvement efforts.
