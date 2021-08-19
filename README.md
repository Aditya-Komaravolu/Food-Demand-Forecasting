# Food Demand Forecasting 

A supply chain use case Machine Learning project. All the resources are cummulative collection of the work done by [**Aditya Komaravolu**](url).





# Food Demand Forecasting

### This project aims at predicting number of orders by the user based on the place of residence, region code, centre of dispatch and of course the user's past data. Completely based on Supply Chain Management.

#### To run this repo you will require following libraries(along with their versions):
```
absl-py==0.12.0
astunparse==1.6.3
backcall==0.2.0
cachetools==4.2.2
conda==4.3.16
cycler==0.10.0
decorator==5.0.9
flatbuffers==1.12
gast==0.4.0
google-auth==1.30.1
google-auth-oauthlib==0.4.4
google-pasta==0.2.0
grpcio==1.34.1
h5py==3.1.0
ipykernel==5.5.5
ipython==7.24.1
ipython-genutils==0.2.0
ipywidgets==7.6.3
jedi==0.18.0
joblib==1.0.1
jupyter==1.0.0
jupyter-client==6.1.12
jupyter-console==6.4.0
jupyter-core==4.7.1
jupyterlab-widgets==1.0.0
jupyterthemes==0.20.0
keras-nightly==2.5.0.dev2021032900
Keras-Preprocessing==1.1.2
kiwisolver==1.3.1
lesscpy==0.14.0
Markdown==3.3.4
matplotlib==3.4.2
matplotlib-inline==0.1.2
numpy==1.20.3
oauthlib==3.1.1
opt-einsum==3.3.0
pandas==1.2.4
parso==0.8.2
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.2.0
ply==3.11
prompt-toolkit==3.0.18
protobuf==3.17.2
ptyprocess==0.7.0
pyasn1==0.4.8
pyasn1-modules==0.2.8
pycosat==0.6.3
Pygments==2.9.0
PyParse==1.1.7
python-dateutil==2.8.1
pytz==2021.1
pyzmq==22.1.0
qtconsole==5.1.0
QtPy==1.9.0
requests-oauthlib==1.3.0
rsa==4.7.2
ruamel.yaml==0.17.7
ruamel.yaml.clib==0.2.2
scikit-learn==0.24.2
scipy==1.6.3
seaborn==0.11.1
six==1.15.0
tensorboard==2.5.0
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.0
tensorflow==2.5.0
tensorflow-estimator==2.5.0
termcolor==1.1.0
threadpoolctl==2.1.0
tornado==6.1
traitlets==5.0.5
typing-extensions==3.7.4.3
wcwidth==0.2.5
Werkzeug==2.0.1
widgetsnbextension

```

## [04/06/2021]
`Project requires 3 models for the given three parts.`
    
-   _Meal ID and Category of Food_

-   _Fulfilment Centers for a given region_  

-   _Model to predict the demand forecast_    
## [05/06/2021]
- Decided to go first model with _**DecisionTreeClassifier**_ for predicting type of food requirement for the user based on `meal_id`.

- target files --> `_meal_info.csv_` and `meal_info.ipynb`.
 
- Built a **DecisionTreeClassifier** which successfully predicts the type of `category` and `cuisine` the user is going to pick based on the user's `meal_id`.

## [09/06/2021]
- Decided to go second model with _**DecisionTreeRegressor**_ for predicting _`region_code`_, _`area_code`_, _`dispatch_warehouse(A,B and C)`_ and _`area of operation`_  based on `center_id`.

- target files --> `_fulfilment_center_info.csv_` and `_fulfilment_center_info.ipynb`.
 
- Built a **DecisionTreeRegressor** which successfully predicts the result with above requirements.





##  **Copyright (C) 2020-2021 by Aditya Komaravolu**.


 _**This Repo contains all my projects done in the area of Machine Learning**._

 _**Machine Learning**_ is free open source repository for self-learning: you can redistribute it and/or modify it under
 the terms of the GNU General Public License as published by the Free
 Software Foundation, either version 3 of the License, or (at your option)
 any later version.

 This repo is public in the hope that it will be useful, but **WITHOUT
 ANY WARRANTY**; without even the implied warranty of **MERCHANTABILITY** or
 **FITNESS FOR A PARTICULAR PURPOSE**.  See the **GNU General Public License** for
 more details.

 You should have received a copy of the **GNU General Public License** along with
 Machine Learning Repo.  If not, see <https://www.gnu.org/licenses/>.
