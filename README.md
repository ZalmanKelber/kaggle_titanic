# Titanic Tutorial

A collection of notebooks used for the [kaggle titanic dataset competition](https://www.kaggle.com/competitions/titanic) (an educational competition that is indefinitely open)

[Attempt No. 1](https://github.com/ZalmanKelber/kaggle_titanic/blob/main/titanic_tutorial_attempt_01.ipynb) was a notebook that resulted in my four first submissions, all with extremely modest results (the highest was around .77).  Main lessons learned: take cross validation seriously, *especially* in small datasets.  Not properly understanding how cross validation worked resulted in me submitting models that severely overfit the data

[Attempt No, 2](https://github.com/ZalmanKelber/kaggle_titanic/blob/main/titanic_tutorial_attempt_02.ipynb) resulted in several subsequent submissions.  Learning the lessons from the first notebook, I was able to improve my score significantly to just shy (one instance) of a score of .80, often considered the benchmark for beginners with this challenge.  Because I have still yet to meet my goals for this challenge, I have not yet gone back and refactored this code using the more formal `Pipeline` class in scikit-learn