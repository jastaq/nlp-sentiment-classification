# nlp-sentiment-classification


This is an educational project dedicated to classifying the emotional coloring of film reviews based on a dataset "IMDB".

Custom metric:

$$ \\frac{\\sum_{i=1}^{N} w(y_i) \\cdot 2^{-|y_i-\\hat{y_i}|^2}}{\\sum_{i=1}^{N}w(y_i) } $$


## Results

| Модель              | Score    | Training time (сек) |
| ------------------- | -------- | ------------------- |
| CatBoost            | 0.58896  | 158                 |
| Logistic Regression | 0.51896  | 17.84               |
| Linear SVC          | 0.48920  | 8.21                |
| Naive Bayes         | 0.42336  | 0.06                |
| Decision Tree       | 0.34083  | 8.88                |


