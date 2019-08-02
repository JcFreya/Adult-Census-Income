# Adult-Census-Income

## Project Description

In this project we analyze a U.S. census data taken from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The goal of this project is to profile people in the above dataset based on available demographic attributes.

1) Construct a model that accurately predicts whether an individual makes more than $50,000.  
2) What are the key factors contributing to high vs. low income?  
3) Are there any significant gaps in these Census attributes by gender or race?  
4) Any underneath clusters (group) based on census data?

### Install

This project requires [**Python 3.x**](https://www.python.org/downloads/release/python-364/) and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

It's highly recommended to install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

The main code for this project is located in the `AF Data Science Project.ipynb` notebook file. Additionally, the `AF Data Science Project.html` file contains a snapshot of the main code in the jupyter notebook with all code cells executed.

### Run

In a terminal or command window, navigate to the top-level project directory `Adult-Census-Income/` (that contains this README) and run one of the following commands:

```bash
ipython notebook AF\ Data\ Science\ Project.ipynb
```  
or
```bash
jupyter notebook AF\ Data\ Science\ Project.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

- `adult.data`  
- `adult.test`  
48842 instances, mix of continuous and discrete    (train=32561, test=16281)  
45222 if instances with unknown values are removed (train=30162, test=15060)

**Features**  
- `age`: continuous.  
- `workclass`: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.  
- `fnlwgt`: final weight, continuous.  
- `education`: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.  
- `education-num`:  continuous.  
- `marital-status`: Represents the responding unit’s role in the family. Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.  
- `occupation`: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.  
- `relationship`: Represents the responding unit’s role in the family. Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.  
- `race`: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.  
- `sex`: Female, Male.  
- `capital-gain`: income from investment sources, apart from wages/salary, continuous.  
- `capital-loss`: losses from investment sources, apart from wages/salary, continuous.  
- `hours-per-week`: continuous.  
- `native-country`: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands. 

**Target**
- `income`: Income Class (<=50K, >50K)  
- clustering data set
