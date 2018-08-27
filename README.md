# RedditClassifier


  This is a classifier that classifies posts to certain subreddits. The classifier is trained on posts that belong to 5 Subreddits, and is tested on different posts in those same 5 Subreddits.
  
  The data is scraped using selenium because of the infinite scrolling of the subreddits which needed something to constantly scroll down and unroll posts, that then can be detected and extracted using the BS4 HTML parser, and stored using a CSV writer.
  
  A few models are used and the optimal algorithm was logistic regression which came at an accuracy of 92.022 percent. The ROC curves and other testing metrics are used to depict the accuracy of results.
