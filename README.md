# Intent Classification using Python
An introduction to imbalanced classification using Ensemble techniques and deployed on heroku.<br>

Resources at bottom👇🏻
### Context:<br>
Intents define an event in virtual assistant systems such as voice assistants, chatbots, etc.<br>
The dataset used available <a href='https://www.kaggle.com/stefanlarson/outofscope-intent-classification-dataset'>here</a>,
includes collections of json file consisting of train and test data, which in turn has 2 columns:
- the command a user gives
- and corrsponding intent<br> 

In total there are 151 intents including a special intent aka oos(out-of-scope) intent, it is difficult for chatbots to differentiate between an in scope intent from an out of scope intent. 
### Deployment:<br>
Model has been deployed using Flask on <a href='https://www.heroku.com'>Heroku SaaS</a><br>
*Visit to see live demo! --> <a>https://intent-classification-python.herokuapp.com/</a>*<br>
<br>
__First highlighted block in output specifies the guessed intent whereas the second block specifies whether the intent is with scope of bot or not i.e is it an inscope or outscope intent which might not always be accourate provided the training data, view IPy notebook for analysis.__
<br><br>
![](/images/1.png)
![](/images/2.png)
![](/images/3.png)
![](/images/4.png)

### Resources:<br>
* https://machinelearningmastery.com/what-is-imbalanced-classification/
* https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/
* https://www.analyticsvidhya.com/blog/2017/03/imbalanced-data-classification/
* https://imbalanced-learn.readthedocs.io/en/stable/generated/imblearn.ensemble.EasyEnsembleClassifier.html
* https://imbalanced-learn.readthedocs.io/en/stable/generated/imblearn.ensemble.RUSBoostClassifier.html


