# py_mcl_classifier

The file v1_OneVsRestClassifier(XGBClassifier)_Example1.py 
contains example of multiclass classifier: OneVsRestClassifier(XGBClassifier)
which predicts the number of bedrooms given 'total_floor_area', 'number_habitable_rooms','estimated_min_price'.
The code is written in Python 3.7.

Required Python libraries:
json, pandas, numpy, 
from xgboost import XGBClassifier
from sklearn.multiclass import OneVsRestClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.metrics import classification_report,confusion_matrix
