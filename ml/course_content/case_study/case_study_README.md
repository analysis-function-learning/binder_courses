# Case Study Descriptions

There are 5 different case studies accompanying this course. It is recommended to complete all of them to consolidate your knowledge from the main chapters, and to gain exposure to some techniques "in the wild". 

The more work you put into the case studies, the more you will get out of them. Each case study has a minimum level to be achieved, with an example solution. However, each can be further explored using different techniques to improve model performance and gain more insight into the data and techniques covered.

Each case study has been chosen to explore different elements of the machine learning engineering tool belt. They are *broadly* listed in increasing difficulty.

Case studies A, B and C focus on supervised learning covered in chapters 1-3.

Case studies D and E focus on unsupervised learning, exploring concepts covered in chapters 4 and 5 respectively.


## Case Study A

**Task:** classification

**When to tackle:** directly after chapter 3.

**Style:** you are free to explore and impliment different techniques in any order. If you would like more support / guidance in the process see Case Study B.

**Topics:**
* KNN classification
* Resampling unbalanced data
* Encoding ordinal data

**Description**: using data from bank users, preduct whether a user has left the bank. Often called "Churn", each customer is labelled as whether or not they have left the company. Using a mix of categorical and numerical data relating to demographics, bank account qualities and quantities and a K-nearest neighbour classify try to predict this churn.

## Case Study B

**Task:** classification

**When to tackle:** directly after chapter 3.

**Style:** this case lets you follow along with example ML project exploration - helping you tackle individual elements of the process, rather than the whole thing all at once. If you are not feeling confident in the overall process it is worth starting with this course.

**Topics:**
* Data Processing
* Feature engineering
* Pipelines
* Model tuning / comparison

**Description:** using the classic titanic data set you will predict whether an individual survived the journey based on demographic characteristics, and information based on their trip. This case study will help you get familiar with coding elements of the machine leanring process and `sklearn`.

## Case Study C

**Task:** regression

**When to tackle:** after case studies A & B.

**Style:** This case study is open ended, with a range of directions of exploration to take. The focus of this case study is using supplementary data, and more advanced feature engineering to improve model performance. Due to the size of features, it will take longer to explore and build than the previous.

**Topics:**
* Supplementary data (joining informative geographic data)
* Feature engineering
* Unbalanced data
* Outlier impact
* KNN regressor
* Model comparison

**Description:** Using open source airbnb data predict the price of a property's nightly stay in Bristol and Manchester. Expanding on existing features of the data set, such as ammenities, you can bring in supplentary data sources (provided) based on the location of the properties. This data set exhibits non-linear characteristics which make the feature engineering extremely important to creating a good model.

## Case Study D

**Task:** dimension reduction, regression

**When to tackle:** after chapter 4, preferably after case studies A or B

**Style:** this case study will suggest exploratory analysis tasks incorporating dimension reduction techniques, followed by a modelling exercise using dimension reduction to improve a supervised learning task.

**Topics:**
* Exploratory dimension reduction (PCA, TSNE)
* Component analysis
* Scaling
* Dimension reduction for supervised learning

**Description:** using US New Mexico Covid federal Loan data with potentially large numbers of dimensions you will explore how dimension reduction techniques can provide insight. You will explore the effects of dimension reduction on a model's ability to learn relationships and produce good predictions.

## Case Study E

**Task:** clustering

**When to tackle:** after chapter 5, preferably after case studies A or B

**Style:** this case study kicks off with an in depth exploration of variables and their transformations. This is followed by using clustering to analyse groupings of the data.

**Topics:**
* Distribution transformations
* Feature engineering
* Covariances
* Clustering
* Model comparison
* Visualisation of high dimensional data

**Description:** using data from facebook live posts in Thailand you will create new features to derive insights from the data set, exploring relationships between the variables. Using a range of clustering methods you will evaluate clustering performance and understand the natural groupings in the data set across high dimensionality data.