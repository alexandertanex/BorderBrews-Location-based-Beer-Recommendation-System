# BorderBrews: Location-based Beer Recommendation System

**For a more detailed documentation, please refer to the attached project report.**

---

## Introduction

BorderBrews is a novel beer recommendation system that enhances user experience by utilizing a hybrid model incorporating both location-based and user-specific feature preferences. This system aims to help beer enthusiasts discover beers that match their taste preferences, particularly in unfamiliar locales.

## Significance

The project addresses the challenge beer consumers face due to the overwhelming variety available in the market. By helping users discover beers they are likely to enjoy, the system enhances consumer experience and fosters a deeper appreciation of the beer culture globally.

## Novelty

1. **Location Filters:** Incorporates brewery location into the recommendation process, reflecting the significant influence of geographical and cultural factors on beer preferences.
2. **User Preference Specification:** Allows users to specify preferences for beer features like aroma or taste, leading to more personalized recommendations.
3. **Advanced Similarity Metrics:** Combines Pearson correlation and cosine similarity in a hybrid model to capture different aspects of similarity, improving the accuracy and relevance of recommendations.

## Data Collection & Preprocessing

The system uses data from the BeerAdvocate database, enhanced by scraping geographical details. We ensured data integrity by processing over 1.5 million reviews, focusing on those that are complete and represent well-reviewed beers.

## Methodology

The recommendation algorithm is a hybrid of Singular Value Decomposition (SVD) and Term Frequency-Inverse Document Frequency (TF-IDF) models. This blend helps mitigate common issues like the cold start problem and over-specialization.

## Experimental Results

The system was evaluated using Root Mean Square Error (RMSE) and Mean Absolute Error (MAE) metrics. Our hybrid model demonstrates superior performance compared to individual SVD or TF-IDF models, particularly in terms of accuracy and user satisfaction.

## Conclusion

BorderBrews integrates location-based filtering and user-specific preferences into its recommendation system. Future improvements may focus on expanding the dataset and refining the models to incorporate additional consumer preferences and enhance the recommendation quality.

## Appendices and References

- **Dataset Links:** Access to BeerAdvocate and location datasets.
- **Model Comparisons:** Detailed statistical analysis and model performance evaluation.

