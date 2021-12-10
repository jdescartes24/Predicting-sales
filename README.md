
# Sales Data Exploration and Modeling


#### -- Project Status: [Completed]

## Project Intro/Objective
What is the purpose of this project this Sales Data Exploration? The purpose of this data analysis is to explore the givien data and try to understand the data.
And to dive deep into this data to try to gain some insite using visualizations and statistical analysis, and final we will try to model the data using a Regression Model to try to predict future sales.  

### Author
* Jonathan Descartes
* My contact: 347-483-7739,  
* Email:jonathandescartes24@gmail.com
*

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling


### Technologies
* Python
* Sklearn
* Pandas, matplotlib, seaborn,
* Linear Regression


## Getting Started
## Pre processing:
first start with collection of our raw data.


![Screenshot (31)](https://user-images.githubusercontent.com/88171421/145506801-5639e3e7-6a3c-4b78-ab95-0172696ef54b.png)
* then we check the shape of are data set using the df.shape function
* we fallow with the df . dtypes function to see the different data types and to see if they correctly represent the data columns
* then we will chcek for duplicate data with the df.duplicate().and() my data set dis not have any duplicates
* we check for missing data in the data set , there were two columns missing data, we did analysis to fill in those missing data.

![Screenshot (33)](https://user-images.githubusercontent.com/88171421/145507429-4bf1613d-79a6-4f49-95dc-4f65e0cff937.png)
* There was more analysis done using df.value_counts() we noticied that there was inconsistencies in the columns , fixed them
## Data Visualizations
* Our first visual was to show witch size store yeilded the most sales
![Screenshot (35)](https://user-images.githubusercontent.com/88171421/145508200-e88f4329-9b19-4d2b-ad6f-4d5e40ce22cd.png)
* then we made a few more visualizations to see how different columns were ditributed.
Eg:
![Screenshot (37)](https://user-images.githubusercontent.com/88171421/145508463-9d92aa71-1aad-4042-8112-50f2466d9061.png)
* I then created a correlation heat map to seek out any correlations within our data sets.


## Machine Learning
* Fist we start with preping the model for Modeling creating our target featueres and our modeling features and passing the data into X and y variables

* Then  I will transform the data using OneHotenCoder for object columns , simple imputer to fill in missing values and MakeColumTransformet to transform the columsn

* we will then make an instance of a linear regresstion, put it with the columntransformer pipeline and fit that pipe onto the data
![Screenshot (42)](https://user-images.githubusercontent.com/88171421/145510057-bb1d2c2a-9675-4266-a7e9-1d240fdad54a.png)
* Then we will evaluate the model performance using recall, accuracy score , and a few more evaluations.
* A function was created to evaluate the model.
* I finaly ran a Descision Tree Model on my data and ran the same evaluation metrics as my linear regressor model to compare them.
* 



