# online-news-popularity-prediction
This is a project for Machine Learning college course, which was implemented by a two person team consisting of
[@JakubDralus](https://github.com/JakubDralus) and [@Veczar](https://github.com/Veczar). <br>
It aims to predict the popularity of an article using random forest classifier.

Note: we have taken various appraches to this problem as seen in `model.ipynb` file.
We later discovered that random forest classifier to be the right model to use.

## Technologies
- Python 3.11.5
- Conda 23.10.00
- pandas
- numpy
- sklearn
- matplotlib
- seaborn

## Dataset

The dataset has 59 features and a target which is the number of shares in social networks (popularity). <br>
This is how it looks afret scailing:

![image](https://github.com/JakubDralus/online-news-popularity-prediction/assets/129612952/8a7ae692-822e-4c92-9bef-f90adad1729f)

# Results
We managed to get an accuracy of 0.67 using random forest classifier. In dataset description it is a recommended best model.
```txt
Accuracy: 0.67
              precision    recall  f1-score   support

           0       0.66      0.60      0.63      5591
           1       0.67      0.73      0.70      6303

    accuracy                           0.67     11894
   macro avg       0.67      0.67      0.67     11894
weighted avg       0.67      0.67      0.67     11894
```


## The Dataset Citation
https://archive.ics.uci.edu/dataset/332/online+news+popularity

K. Fernandes, P. Vinagre and P. Cortez. A Proactive Intelligent Decision
Support System for Predicting the Popularity of Online News. Proceedings
of the 17th EPIA 2015 - Portuguese Conference on Artificial Intelligence,
September, Coimbra, Portugal.

