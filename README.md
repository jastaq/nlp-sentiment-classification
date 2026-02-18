# nlp-sentiment-classification


This is an educational project dedicated to classifying the emotional coloring of film reviews based on a dataset "IMDB".

Custom metric:

$$ \\frac{\\sum_{i=1}^{N} w(y_i) \\cdot 2^{-|y_i-\\hat{y_i}|^2}}{\\sum_{i=1}^{N}w(y_i) } $$
