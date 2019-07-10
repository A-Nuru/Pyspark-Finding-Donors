# Supervised Learning
## Pyspark-Finding-Donors

## Installation
The libraries employed in this project to run the code are Python 3.6,spark, java 1.8. It is  recommended 
that you use java 1.8 because java 11 is not compatible with other required libraries.

## Project Motivation
The motivation behind this project is to learn how to use spark for big data analysis since 
the rate real data are generated are so huge that our traditional system can not store and process
this data on the run. Spark makes it easier to work with big data by also providing paltform to build, 
deploy and automate our machine learning algorithms at higher efficiency. In this work, we will build machine learning 
models using the MLlib to find donors for a charity organisation in California
## File Descriptions
The files associated with this work include
* The jupyter ipython notebook 
* The census.csv file
* A readme file
### Description
* Employed supervised learning techniques on income census data collected  in California, US to  identify people more inclined to donate to  CharityML - a charity organisation. 
* Applied pre-processing and transformation techniques to manipulate the data to a workable format, evaluated several supervised learning methods, chose the best and optimized it.
* A model that could predict individual's income whether above or below $50,000 based on some available features was produced.  This allowed non-profit organizations to determine how much donation to request or not from indviduals.


### Data

The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Features**
- `age`: Age
- `workclass`: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- `education-num`: Number of educational years completed
- `marital-status`: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- `race`: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sex (Female, Male)
- `capital-gain`: Monetary Capital Gains
- `capital-loss`: Monetary Capital Losses
- `hours-per-week`: Average Hours Per Week Worked
- `native-country`: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Target Variable**
- `income`: Income Class (<=50K, >50K)
