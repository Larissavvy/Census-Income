# Census-Income

This dataset is taken from Kaggle :https://www.kaggle.com/overload10/adult-census-dataset

To Predict: If the individuals income is greater than 50k or lesser than 50k: a Classification Problem

## Dataset:
| Column ID |   Column Name  | Data type | Values type |          Description         |
|:---------:|:--------------:|:---------:|:-----------:|:----------------------------:|
|     0     |       age      |   int64   |  Continous  |         Age of person        |
|     1     |    workclass   |   object  |   Discrete  |      Workclass of person     |
|     2     |     fnlwgt     |   int64   |  Continous  |         Final weight         |
|     3     |    education   |   object  |   Discrete  |  Education Degree of person  |
|     4     |  education.num |   int64   |  Continous  | Number of years of education |
|     5     | marital.status |   object  |   Discrete  |   Marital status of person   |
|     6     |   occupation   |   object  |   Discrete  |     Occupation of person     |
|     7     |  relationship  |   object  |   Discrete  |    Relationship of person    |
|     8     |      race      |   object  |   Discrete  |        Race of person        |
|     9     |       sex      |   object  |   Discrete  |         Sex of person        |
|     10    |  capital.gain  |   int64   |  Continous  |    Capital gain of person    |
|     11    |  capital.loss  |   int64   |  Continous  |    Capital loss of person    |
|     12    | hours.per.week |   int64   |  Continous  |   Number of hours per week   |
|     13    | native.country |   object  |   Discrete  |   Native country of person   |
|     14    |     income     |   object  |   Discrete  |   Income category of person  |

Conclusion: I have used multiple Classification Models such as XGBoost, Logistic Regression, SVM and Hypertuned the parameter to give a better result.
