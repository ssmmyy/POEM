## POEM: Position Order Enhanced Model for Session-based Recommendation Service

**Requirements**
* Python 3.6
* Pytorch 1.+

**Datasets**

* YOOCHOOSE: http://2015.recsyschallenge.com/challenge.html
* DIGINETICA:http://cikm2016.cs.iupui.edu/cikm-cup
* RETAILROCKET:https://www.kaggle.com/retailrocket/ecommerce-dataset

**Processing code**
* python preprocess_ours.py for the length of session greater than 2
* python preprocess.py for the length of session greater than 1
* python preprocess_rr.py for RETAILROCKET dataset before above preprocessing.
