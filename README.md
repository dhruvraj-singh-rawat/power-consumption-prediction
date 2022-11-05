## power-consumption-prediction

The [dataset](https://archive.ics.uci.edu/ml/datasets/Power+consumption+of+Tetouan+city) related to power consumption of three different distribution networks of Tetouan city which is located in north Morocco is used for analysis and the dataset doesnot contain any missing values. Firstly, the relative importance of each feature is calculated using SelectKbest and Permutation Importance. Since, its regression problem, following metrics were used for measuring the performance of the model:

- Mean Absolute Error 
- Root Mean Squared Error
- Mean Squared Error 
- R-Squared 
- Scatter-Plot (Visual Evaluation)

In this work, listed below algorithms were used for building the model:

- Decision Tree
- Random Forest
- Adaboost
- Xgboost 



### Installing

Following are the step by step to get a development env running

    1. Visit the Anaconda homepage.
    2. Click “Anaconda” from the menu and click “Download” to go to the download page.
    3. Choose the download suitable for your platform (Windows, OSX, or Linux):
    4. Follow the Installation wizard.
    5. Open the Anaconda Prompt and enter the following to create a python env
```
conda create -n myenv python=3.5
```
    6. Then enter the following commands to install the required dependencies for this project. 
```
conda install -n myenv scikit-learn
conda install -n myenv pandas
```

## Running the Code 

1. Download/Clone this repository.
2. Go the location and open Anaconda Prompt/Termial and start the environment by 
```
activate myenv
```
3. After this you can run the program by executing the following line.
```
jupyter notebook
```

## Built With

* [scikit-learn](http://scikit-learn.org/) - Python Machine Learning Framework
* [Pandas](https://pandas.pydata.org/) - Python Data Analysis Library
