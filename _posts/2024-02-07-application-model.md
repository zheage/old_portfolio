---
layout: post
author: Richard Guilherme
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque vel lacinia neque. Praesent nulla quam, ullamcorper in sollicitudin ac, molestie sed justo. Cras aliquam, sapien id consectetur accumsan, augue magna faucibus ex, ut ultricies turpis tortor vel ante. In at rutrum tellus.

# Sample heading 1

<figure>
  <img src="images\revolt.jpg" alt="Texto Alternativo">
  <figcaption>Legenda da Imagem ....</figcaption>
</figure>

```python
from xgboost import XGBClassifier
# read data
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
data = load_iris()
X_train, X_test, y_train, y_test = train_test_split(data['data'], data['target'], test_size=.2)
# create model instance
bst = XGBClassifier(n_estimators=2, max_depth=2, learning_rate=1, objective='binary:logistic', enable_categorical = True)
# fit model
bst.fit(X_train, y_train)
# make predictions
preds = bst.predict(X_test)

def Class():
  __init__()

  self.x = x

def funcao(a,b):
  return c
```