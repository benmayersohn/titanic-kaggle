# Titanic Kaggle Competition

Predicting survival in Titanic passengers is the introductory competition on Kaggle, and is typically used as a learning tool for newbies to data science and the Kaggle platform. A dataset of passengers on the Titanic is provided [here](https://www.kaggle.com/c/titanic/data), along with the following description:

>The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

>One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

>In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to **apply the tools of machine learning to predict which passengers survived the tragedy**.

So we are expected to use a binary classifier model for the outcome (`Survival`) that we can train on the provided `train.csv` file, and test on the provided `test.csv` file.

My analysis is in the Jupyter notebook `Titanic.ipynb`. It can be viewed [here on nbviewer](https://nbviewer.jupyter.org/github/benmayersohn/titanic-kaggle/blob/master/Titanic.ipynb)

Below is a breakdown of the files in this repository.
<pre class="language-bash"><code class="language-bash">titanic
|____Titanic.ipynb              # jupyter notebook
|____test.csv                   # test data
|____train.csv                  # training data
|____submission_logistic.csv    # output submission
|____README.md                  # this
</code></pre>