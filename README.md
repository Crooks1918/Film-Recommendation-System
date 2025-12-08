# Film Recommendation System 
This project integrates two complementary datasets to create a comprehensive movie dataset. The first dataset, Movie Database 2024, contains information on over 1 million films, including vote averages, vote counts, release dates, revenue, and more. The second dataset, Movie Dataset 50,000 Credits, provides detailed information about each film’s cast and crew. By joining these two datasets, we generate a clean, unified dataset ready for analysis.

To ensure fair ranking of movies, a weighted rating is calculated. This prevents films with only a few votes from appearing disproportionately high in the rankings due to a small number of extreme ratings. The weighted rating balances a movie’s popularity with its quality.

For content-based similarity analysis, TF-IDF and CountVectorizer are applied to features such as cast, crew, keywords, and genres. These methods measure the similarity between movies based on the frequency and importance of terms, enabling effective content-based recommendations.
