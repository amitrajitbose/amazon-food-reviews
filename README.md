## Amazon Fine Food Reviews
### Stanford Network Analysis Project | Kaggle
###### Author : `Amitrajit Bose`

#### Context

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

#### Contents

Reviews.csv: Pulled from the corresponding SQLite table named Reviews in database.sqlite <br>
database.sqlite: Contains the table 'Reviews'

#### [Data](https://www.kaggle.com/snap/amazon-fine-food-reviews)

- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews

![Wordcloud](https://www.kaggle.io/svf/137051/2ba35b1344041b4964fe12365b577999/wordcloud.png)

_This data was originally published on [SNAP](https://www.kaggle.com/snap)._
If you publish articles based on this dataset, please cite the following paper: - J. McAuley and J. Leskovec. [From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews. WWW, 2013.](http://i.stanford.edu/~julian/pdfs/www13.pdf)

The dataset was obtained from [Kaggle](https://www.kaggle.com). It was released under _CC0: Public domain_.

#### [Notebook](https://www.kaggle.com/amitrajitbose/amazon-food-reviews-using-linear-svc/notebook)

Sentiment analysis of 200000 reviews backed by efficient NLP data processing mechanisms and clean-up schemes. Achieved an aggregate accuracy over 91%, with ROC-AUC-Score over 93% using linear classification machine learning algorithms. Compared multiple classification algorithms, perform vectorization, feature engineering and hyperparameter tuning - all contained in the [notebook](https://github.com/amitrajitbose/amazon-food-reviews/blob/master/kernel.ipynb).

The accuracy can be further improved by using non-linear classification machine learning algorithms, neural networks and LSTMs. The goal of the project was to achieve maximum possible accuracy without using complicated non-linear classification algorithms.

#### Contributions

The repository is not currently open for collaborations. The [original version of the notebook on Kaggle](https://www.kaggle.com/amitrajitbose/amazon-food-reviews-using-linear-svc/notebook) is available for contributions. Please feel free to fork and improve.
