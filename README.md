# Heart Disease Classification Project

In this project, we want to predict if a patient has a heart condition from previous data.
We examined the data with an EDA and made visualizations to find the correlation between features. 
After that, we trained various models to predict heart conditions. 

## Data

The data are in CSV format and are taken from Kaggle:  https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci

and is provided with a data dictionary that we have pasted in the EDA notebook.

## Exploratory Data Analysis
First of all, we reviewed the data statistics and, since the data were complete and all numeric we precede to an EDA. 

### Distribution of conditions
We can see that the outcome is quite balanced. 

![download](https://user-images.githubusercontent.com/109316190/203298617-1bd05de6-9339-434c-b2df-202e7d585dd1.png)

### Distribution of Sex 

![download](https://user-images.githubusercontent.com/109316190/203299955-b95ca816-2107-48f0-b1d6-4945bc454b47.png)


### Condition vs. Sex
We confronted condition and sex variables: as we can see the majority of conditions affected males and this is not surprising looking at the Sex distribution.

![download](https://user-images.githubusercontent.com/109316190/203299940-33d34a00-4b1d-466f-b814-bffd89427ee3.png)

### Condition vs. Age
Here is shown that most condition is strictly correlated to age.

![download](https://user-images.githubusercontent.com/109316190/203299904-7829cc7f-c583-4da3-811c-817bc5388477.png)

### Age vs. Max Heart Rate for Heart Disease

![download](https://user-images.githubusercontent.com/109316190/203300134-5ec7db1f-339d-4a90-8754-3ac4411aaff5.png)
