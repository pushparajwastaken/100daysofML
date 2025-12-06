Field of Computer Science that uses statistical technique that allows computers to learn from data and perform tasks without explicitly programmed 


## Difference between Model based and Instance based Machine Learning 
![[Screenshot (2342) 1.png]]
## Challenges in Machine Language
1.Data Collection-fetching from API and Web-Scraping
2.Insufficient Data/Labelled Data
3.Non Representative Data
4.Poor Quality Data
5.Irrelevant Features-garbage in, garbage out
6.Overfitting-if the ml model just memorizes the data and doesn't learn from it
7.Underfitting-When a model is **too simple** to capture the underlying patterns in the data.
8.Software Integration
9.Offline Learning/Deployment
10.Cost Involved-
## Applications of Machine Learning
1.Retail
2.Transportation
3.Social-Media
4.Banking and Finance
5.Manufacturing
## Machine Learning Development Life Cycle
 1.Frame the problem
 2.Gathering the data
 3.Data Preprocessing -removing duplicates, remove missing, outliers, scale the values(standardization)
 4.Exploratory Data Analysis
 5.Feature Engineering and Selection
 6.Model Training, Evaluation and Selection
7.Model Deployment
8.Testing
9.Optimize
## Data Engineer Vs Data Analyst Vs ML Engineer
DE-scrape data from the given source 
DA-Cleaning and organizing the raw data, analyzing data to derive insights 
DS-ML Model, A data scientist is someone who is better at statistics than any software engineer and better at software engineering than any statistician

## Tensors
It is a data structure
#### 0D Tensors
aka Scalar
has no dimension
Tensors are n-dimensional array

#### Axis
No of dimensions
No. of axis=rank
shape
size
#### 1D Tensor/Vector
[1,2,3,4]
Jab bhi ek 1D tensor banate hai wo ek vector hai aur uss vector ke andar jitte element hote wo uska dimension hai,

### 2D Tensor/Matrices
Collections of vector 

# Understanding your data

## Asking Basic Questions
1. How big is the data?
  `df.shape()`
2. How  does the data look like?
`df.head()` - gives the first five rows of data
`df.sample(5)` - gives 5 random rows from the db
3. What is the data type of cols?
`df.info()` - gives information about every column
4. Are there any missing values?
 `df.isnull().sum()` 
 5. How does the data look mathematically?
 `df.describe()`
 6. Are there any duplicate values?
 `df.duplicated().sum()`
 7. How is the correlation between cols?
 `df.corr()`
 