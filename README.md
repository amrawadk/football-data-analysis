# Football data analysis

This project aims to clean up football data inside a [kaggle database](https://www.kaggle.com/hugomathien/soccer/data) and then train 3 machine learning models to predict match results. 

The [data clean up](./build_database.ipynb) was done with Pandas and contained some complex manipulation due to the original dataformat vs. the desired output.

The trained models are:
1. [ADA Boost](./ada_boost.ipynb)
2. [Random Forest](./random_forest.ipynb)
3. [Tensorflow NN](./tensorflow_nn.ipynb)

**Note:** The ML part only shows the code & data flow, no model optimization was done.

## Setup

1. Inside the project directory, Create a virtual environment.
```
C:\Python36\python.exe -m venv venv
```

2. activate the virtual environment and install the required packages.
```
venv\Scripts\activate
# the prompt should change and have (venv) before the path
python -m pip install -r requirements.txt
```

3. Run Jupyter notebook
```
jupyter notebook
```
