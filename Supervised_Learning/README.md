## **Supervised Learning**

Supervised learning is used to predict a certain outcome from a given inputs, and we have examples of input/output pairs called training dataset. We make accurate predictions for new data. In supervised learning, the training data you feed to the algorithm includes the desired solutions, called labels. There are two major types of supervised machine learning problems, called classification and regression. In classification, the goal is to predict a class label, which is a choice from a predefined list of possibilities. For regression tasks, the goal is to predict a continuous number, or a floating-point number in programming terms (or real number in mathematical terms).

### **Generalization, Overfitting, and Underfitting**

In supervised learning, a model will be build on the training data and then be
able to make accurate predictions on new, which has the same characteristics (features) as the training set. If our model make accurate predictions on
unseen data, we say it as *generalized model*.

If the training and test sets have enough in common, the model will be accurate on the test set too. In some cases this may go wrong, if we allow ourselves to build very complex models, we can always be as accurate as we like on the training set (overfitting).
*   Building complex model for the amount of information may lead to **Overfitting**, this occurs when you fit a model too closely to the training set and the model that works well on the training set but is not able to generalize to new data.
*   If your model is too simple then you might not be able to capture all the aspects of our data, and our model will do badly even on the training set, this model is called underfitting.

![](https://github.com/Bluelord/Intro_to_ML_Python_Notes/blob/b0e0ae1644cf53ddb875f6c5233318a268a8a835/Images/Tradeoff_model_complexity_vs_training_test_acc.JPG)

Above figure shows the trade-off betweem overfitting and underfitting, if our model become too complex, it focused on individual data points in training test and our model is not generalized. the spot where we can get best generalization for our model is somewhere in between and this is the model we want to find while building the model. 

**Relation of Model Complexity to Dataset Size**

If our dataset has large variety of data points, the more complex model can be usded without overfitting, this can be done by collecting more data. However, simply duplicating the same data points or collecting very similar data will not help.
