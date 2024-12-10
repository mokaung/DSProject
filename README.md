### Predicting IMDb Ratings and Box Office Earnings with Machine Learning

Northeastern University

DS 3000: Foundations of Data ScienceSunithi Krishnan, Komal Jain, Ian Menachery, Kaung Mo

Summary

This project uses machine learning to predict IMDb ratings and box office earnings of movies based on features like genre, Rotten Tomatoes scores, runtime, and director information. Data was collected and cleaned from TMDb and OMDb APIs, resulting in a dataset of 732 movies. Two models were employed:

Ridge Regression: Predicts IMDb ratings using features like Rotten Tomatoes scores, genre, and box office earnings. The model achieved a Mean Squared Error (MSE) of 0.38 and an R² value of 0.42.

Polynomial Regression: Predicts box office earnings using features like IMDb ratings and runtime. This model yielded an MSE of 0.63 and an R² value of 0.25.

While the models performed moderately well, results suggest the inclusion of additional factors (e.g., marketing efforts, production budgets) could improve accuracy. The analysis provides insights into what drives a movie's success and serves as a foundation for further exploration.
