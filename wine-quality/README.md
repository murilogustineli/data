# Wine Quality Data Set
## Wine Quality
### Source
This dataset was obtained from the UCI Machine Learning Repository website at: **https://archive.ics.uci.edu/ml/datasets/wine+quality**

### Data description

	RangeIndex: 1599 entries, 0 to 1598
	Data columns (total 12 columns):
	 #   Column                Non-Null Count  Dtype  
	---  ------                --------------  -----  
	 0   fixed_acidity         1599 non-null   float64
	 1   volatile_acidity      1599 non-null   float64
	 2   citric_acid           1599 non-null   float64
	 3   residual_sugar        1599 non-null   float64
	 4   chlorides             1599 non-null   float64
	 5   free_sulfur_dioxide   1599 non-null   float64
	 6   total_sulfur_dioxide  1599 non-null   float64
	 7   density               1599 non-null   float64
	 8   pH                    1599 non-null   float64
	 9   sulphates             1599 non-null   float64
	 10  alcohol               1599 non-null   float64
	 11  quality               1599 non-null   int64  
	dtypes: float64(11), int64(1)
	memory usage: 150.0 KB

### Data Set Information:

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: [Web Link] or the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.


### Attribute Information:

For more information, read [Cortez et al., 2009].
Input variables (based on physicochemical tests):
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
Output variable (based on sensory data):
12. quality (score between 0 and 10)
